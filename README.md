# Real vs Fake Faces Classification

This project aims to classify images into real and fake faces using Convolutional Neural Networks (CNNs) and transfer learning with the XceptionNet model. The dataset used contains 140k real and fake faces.

## Dataset

The dataset consists of images of both real and fake faces. It is split into training, validation, and test sets. The distribution of images in each dataset is as follows:

- Training: 100,000 images
- Validation: 20,000 images
- Test: 20,000 images

## Preprocessing

Images are resized to 256x256 pixels and normalized before feeding them into the models.

## Models

### CNN Model

The CNN model consists of several convolutional and pooling layers followed by fully connected layers. It achieves an accuracy of [accuracy] on the test set.

### XceptionNet Model

The XceptionNet model is used with transfer learning. It is pre-trained on ImageNet and fine-tuned on the dataset. It achieves an accuracy of [accuracy] on the test set.

### ForensicTransfer Model

The ForensicTransfer model is also used with transfer learning. It is based on XceptionNet and achieves an accuracy of [accuracy] on the test set.

## Results

Confusion matrices and classification reports for each model are provided to evaluate their performance.

## Usage

1. Clone the repository.
2. Install the required dependencies.
3. Download the dataset from [Kaggle](https://www.kaggle.com/xhlulu/140k-real-and-fake-faces).
4. Preprocess the dataset using the provided code.
5. Train the models using the preprocessed dataset.
6. Evaluate the models on the test set.

## License

This project is licensed under the [MIT License](LICENSE).

