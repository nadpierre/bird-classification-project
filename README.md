# Bird Image Classification Project

## Description

The goal of this project is to build an image classification model with the best possible performance.

## Dataset

The data comes from the [Bird Species dataset from Kaggle](https://www.kaggle.com/datasets/umairshahpirzada/birds-20-species-image-classification/data). It's a dataset of 20 bird species, containing 3208 training images, 100 test images (5 images per species) and 100 validation images(5 images per species). All images are 224 X 224 X 3 color images in jpg format.

## Libraries Used

- matplotlib
- numpy
- pandas
- PIL
- sklearn
- tensorflow

## Model

The pretrained model used is VGG16 from TensorFlow. After fine-tuning with the birds dataset, the new model reached an 95% accuracy. The exported model can be found [here](https://drive.google.com/drive/folders/1SIbYeXf8KVzzHdRh7KMZ02T0NrTEUkBa?usp=sharing).

## Featured Notebook

[Transfer Learning](./transfer_learning_vgg.ipynb)
