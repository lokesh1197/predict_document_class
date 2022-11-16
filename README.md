# Predicting document class from images

## Description
Given a set of grayscale document images, the task is to classify each image into one of the 16 classes or document types. The training dataset consists of 16000 images with 1000 images belonging to each class. The dataset was collected from the RVL-CDIP dataset (A. W. Harley, A. Ufkes, K. G. Derpanis, "Evaluation of Deep Convolutional Nets for Document Image Classification and Retrieval," in ICDAR, 2015)

### Files
**train** - this folder consists of the training images as .tiff file. DO NOT change the ids of the individual image files as they are used for mapping to the corresponding classes.
**validation** - this folder consists of 900 images as .tiff file for the participants to check their performance.
**train_labels.csv** - map of the images to the corresponding classes.
**metaData.csv** - supplemental information about the data

### Columns
- `id` -> image id, part of the image file. (E.g., if the image file 1234.tiff -> 1234)
- `label` -> class label for the corresponding image, In total 16 classes indexed from 0 to 15

### Test
- [Google Colaboratory](https://colab.research.google.com/drive/1mLCkQZyK5hJIKIUbCDlJy-kHF8R_uyMt?usp=sharing)

## Reference
- [Kaggle Datathon](https://www.kaggle.com/competitions/datathonindoml-2022/overview)
- [Code from kaggle](https://www.kaggle.com/code/rahuldshetty/datathon)
- [Data](https://storage.googleapis.com/kaggle-competitions-data/kaggle-v2/38137/4103414/bundle/archive.zip?GoogleAccessId=web-data@kaggle-161607.iam.gserviceaccount.com&Expires=1668841955&Signature=x17AJG%2F6FRbXjW5NIlnS5bU%2B%2FB0v4yLgHip7DccFsbS%2F1dFmWqDsr2Cx6XeO40yBeuN43o71ydvG5UXcBQuwt2Y1tkGjDM0YwjfnlUDvMfJ7GHwQSFj327M%2Bcca%2FZmEdcBgqwq%2F%2B%2FfEcgQ1TH3uIK8X11vBulTuWf9f%2F3L%2BnO8AazfhxmVblN9DxshvJ2EK6mG1Vhzfwx%2FxhvqsYsZkzcdYBWCUNj7m6s8UOsjUeZDjj8k84nX04LLJcChP9JHsCm8F20%2BMDW8Csu2YTvXoSlHMC2JdFqz4I7zjxlmqlkWIcaWyH%2BpywH2vJBB8XQFP4QNC2LRX8mHIQ12HUXnFHIQ%3D%3D&response-content-disposition=attachment%3B+filename%3Ddatathonindoml-2022.zip)

