# Predicting document class from images

## Description
Given a set of grayscale document images, the task is to classify each image into one of the 16 classes or document types. The training dataset consists of 16000 images with 1000 images belonging to each class. The dataset was collected from the RVL-CDIP dataset

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

