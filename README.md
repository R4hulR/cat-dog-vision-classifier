# Cat-Dog Vision Classifier

A deep learning image classifier using fastai to distinguish between cats and dogs with improved accuracy. Built with ResNet18 and fine-tuned on custom dataset.

## Overview

This project implements a robust image classifier that can distinguish between cats and dogs using deep learning techniques. It leverages transfer learning with a pre-trained ResNet18 model, fine-tuned on a custom dataset of cat and dog images.

## Features

- Custom dataset creation using DuckDuckGo image search
- Data preprocessing and augmentation techniques
- Transfer learning with pre-trained ResNet18 model
- High accuracy in classifying cats and dogs
- Simple web interface for easy image upload and classification using Gradio

## Usage

1. Clone the repository
2. Install the required dependencies
3. Run the Jupyter notebook or Python script to train the model
4. Use the trained model to classify new images of cats or dogs
5. Access the Gradio interface for real-time classification

## Results

The model achieves improved accuracy on the validation set after 5 epochs of fine-tuning.

Final epoch statistics:
- Train loss: 0.114325
- Validation loss: 0.064768
- Error rate: 0.040000 (4%)
- **Accuracy: 96.0%**

## Model Architecture

This project uses a ResNet18 architecture, which is known for its efficiency and effectiveness in image classification tasks. The model is pre-trained on ImageNet and fine-tuned on our custom cat and dog dataset.

## Web Interface

You can try the classifier using the simple web interface built with Gradio. Upload an image of a cat or dog, and the model will classify it.

[Try the classifier on Hugging Face Spaces](https://huggingface.co/spaces/iamrahul/minimal)

## Future Improvements

- Expand the dataset with more diverse images of cats and dogs
- Experiment with different model architectures (e.g., ResNet50, EfficientNet)
- Implement more data augmentation techniques to improve model generalization
- Enhance the web interface with additional features and better styling

## Acknowledgements

This project is inspired by and based on the fastai course. It utilizes the fastai library for efficient implementation of deep learning techniques.

## License

[GNU General Public License v3.0](LICENSE)
