
# MNIST Handwritten Number Recognition

This repository contains a model trained on the MNIST dataset consisting of over 50,000 grayscale images of handwritten numbers. The model achieves a peak accuracy of 99.18%.

## Overview

The MNIST dataset is a well-known dataset in machine learning and image recognition, comprising 70,000 images of handwritten digits (0-9). This project aims to recognize these digits using a neural network model trained on this dataset.

## Model Performance

- **Accuracy:** 99.18% "for the 16b model (best)"
- **Dataset:** MNIST
- **Images:** 50,000+ grayscale images

### Best model in the accuracy score is the "mnist_cnn_model_100e_16b_10sp_5rp"

## Dataset

The MNIST dataset is available on Kaggle and consists of the following:

- **Training set:** 60,000 images
- **Test set:** 10,000 images
- Each image is a 28x28 pixel grayscale image of a single handwritten digit.

## Model Training

The model was trained using the following steps:

1. **Data Preprocessing:** 
   - Normalizing the pixel values to a range of 0 to 1.
   - Splitting the dataset into training and validation sets.

2. **Model Architecture:**
   - A simple Convolutional Neural Network (CNN) with the following layers:
     - Convolutional layer
     - Max pooling layer
     - Dropout layer
     - Fully connected layers

3. **Training:**
   - Using an optimizer such as Adam.
   - Loss function: Categorical Cross-Entropy.
   - Training for a number of epochs with early stopping and scheduled learning rate until the model achieves optimal performance on the validation set.

## Usage

### To use the model you must open it on Kaggle if you want to train your own or clone it and install the dependencies in the requirments.txt then run the part for "test" on jupyter notebook


## Results

Here are some sample predictions made by the model:

| Image | Predicted Label |
|-------|-----------------|
| ![img1](sample_images/img1.png) | 7 |
| ![img2](sample_images/img2.png) | 2 |
| ![img3](sample_images/img3.png) | 1 |

## Contributing

Contributions are welcome! If you have any improvements or suggestions, please create a pull request or open an issue.

## License

This project is licensed under the apache 2.0 License.

## Acknowledgements

- The MNIST dataset is provided by Yann LeCun and the Courant Institute, NYU.
- The model was developed using Kaggle.

## Contact

For any questions or inquiries, please contact [ahed9x](https://github.com/ahed9x).


