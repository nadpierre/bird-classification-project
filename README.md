# Bird Image Classification Project

## Description

The goal of this project is to build an image classification model with the best possible performance.

## Dataset

The data comes from the [Bird Species dataset from Kaggle](https://www.kaggle.com/datasets/umairshahpirzada/birds-20-species-image-classification/data).

## Libraries Used

- datasets
- evaluate
- huggingface_hub
- matplotlib
- numpy
- pandas
- PIL
- sklearn
- tensorflow
- transformers

## Model

The pretrained model used is a [Vision Transformer (ViT) from Google](https://huggingface.co/google/vit-base-patch16-224). It has been fine-tuned with the dataset. After training, the [new model](https://huggingface.co/nadpierre/bird_classifier) reached an 100% accuracy.

## Featured Notebook

[Image Classification](./image_classification.ipynb)
