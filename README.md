# Cat-Dog Vision Classifier

A deep learning image classifier using fastai to distinguish between cats and dogs with 93.5% accuracy. Built with ResNet18 and fine-tuned on custom dataset.

## Overview

This project implements a robust image classifier that can distinguish between cats and dogs using deep learning techniques. It leverages transfer learning with a pre-trained ResNet18 model, fine-tuned on a custom dataset of cat and dog images.

## Features

- Custom dataset creation using DuckDuckGo image search
- Data preprocessing and augmentation techniques
- Transfer learning with pre-trained ResNet18 model
- High accuracy in classifying cats and dogs

## Usage

1. Clone the repository
2. Install the required dependencies
3. Run the Jupyter notebook or Python script
4. The model will be trained on the downloaded images
5. Use the trained model to classify new images of cats or dogs

## Results

The model achieves 93.52% accuracy on the validation set after 5 epochs of fine-tuning.

Final epoch statistics:
- Train loss: 0.062250
- Validation loss: 0.211431
- Error rate: 0.064815

## Model Architecture

This project uses a ResNet18 architecture, which is known for its efficiency and effectiveness in image classification tasks. The model is pre-trained on ImageNet and fine-tuned on our custom cat and dog dataset.

## Future Improvements

- Expand the dataset with more diverse images of cats and dogs
- Experiment with different model architectures (e.g., ResNet50, EfficientNet)
- Implement data augmentation techniques to improve model generalization
- Create a simple web interface for easy image upload and classification

## Acknowledgements

This project is inspired by and based on the fastai course. It utilizes the fastai library for efficient implementation of deep learning techniques.

## License
[GNU General Public License v3.0]
