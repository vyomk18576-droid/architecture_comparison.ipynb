# Comparing small cnn vs small vgg vs small resnet

## Project overview
## The goal of this project is to classify natural images into six categories.
### Buildings
### Forest
### Glacier
### Mountain
### Sea
### Street

## We explore how model complexity affects performance by comparing:
### Basic CNN
### VGG-style mini CNN
### Residual Network (Resnet)

## Dataset
### Source : Kaggle Intel Image Classification Dataset
### Total Classes: 6
### Image Size : 128 x 128
### Training Samples: ~14,000
### Validation Samples: ~3,000
### https://www.kaggle.com/datasets/puneet6060/intel-image-classification
### Dateset is downloaded using Kaggle API


## Tech Stack
### Tensorflow / Keras
### Numpy
### Matplotlib
### Google Colab

## Models Implemented

## Basic CNN
### 3 convolutional layers
### Batch Normalization
### Global Average Pooling
### Fully connected classifier
### Validation Accuracy: ~73.7 %


## VGG-style CNN
### Deeper architecture with stacked conv layers
### Batch Normalization + Dropout
### Inspired by VGG design
### Validation Accuracy: ~79.9 %


## ResNet (Custom)
### Residual blocks with skip connections
### Handles vanishing gradient problem
### Deeper and more stable training
### Validation Accuracy: ~80.3 % (Best Model)


| Model     | Validation Accuracy |
| --------- | ------------------- |
| Basic CNN | 73.7%               |
| VGG-style | 79.9%               |
| ResNet    | 80.3%               |

## Training Visualization
### Accuracy vs Epochs
### Loss vs Epochs
### Helps analyze overfitting and convergence

## Predictions
### The model is tested on unseen images and outputs predicted classes with visualization

## How to Run
### Copy paste the code given architecture_comparison.ipynb and add your kaggle.json file (kaggle API key) when asked

## Key Learnings
### Deeper models improve performance but increase computation
### Residual connections significantly stabilize training
### Data augmentation improves generalization
### Batch normalization speeds up convergence


## Future Improvements
### Use pretrained models (Transfer learning)
### Hyperparameter tuning
### Add confusion matrix and classification 
### Deploy using Flask/ FastAPI


## Contributing
### Feel free to fork this repo and improve it . Pull requests are welcome!



















