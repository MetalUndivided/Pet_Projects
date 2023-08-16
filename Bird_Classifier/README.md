# Bird Classifier

A ResNet50 fine-tuned for identifying birds in photos.

## Description

This is a fun project is done primarily to get myself acquainted with PyTorch. The model used here is a custom implementation of ResNet50 fine-tuned with IMAGENET 1K weights.

[Dataset source](https://www.kaggle.com/datasets/gpiosenka/100-bird-species).

## Getting Started

### Installation and use

The environemt can be set up using Anaconda and the provided yml file:

* ```bash
  conda env create -f environment.yml
  ```

## Structure

* Classifier_Torch.ipynb - Jupyter Notebook with data loaders, EDA, training and testing loops. May need to replace the paths to your location of the dataset.

* ResNet50_imagenet_finetuned_bird_classifier.torch - saved fine-tuned PyTorch model.

* species_count - pickled dictionary of number of pictures per species in the dataset.