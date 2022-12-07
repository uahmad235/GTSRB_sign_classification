# GTSRB_sign_classification
Pytorch-based classification of different models on [GTSRB sign dataset](https://pytorch.org/vision/main/generated/torchvision.datasets.GTSRB.html).

## Requirements:
* The notebook requires only one dependnecy: `pytorch`

## Models Architectures:
1) Custom model without regularizations - serves as a baseline

2) Improving baseline model performance with regularizations and optimization technique (dropout, better activation functions, and BatchNormalization)

3) Use VGG16 for transfer learning (with full parameters)

4) Prune VGG16 by dropping some intermediate layers for faster execution. The goal here is to retain maximum performance of the original model while reducing memory and resources used while training and inference.



* Model train/val/test loss & f1-score are being logged on tensorboard for easier comparison.

