# Face Recognition and Movie Review Sentiment Analysis

## Face Recognition
### Dataset
**Olivetti faces dataset (AT&T Laboratories Cambridge)**

The original dataset consisted of 92 x 112, while the version available here consists of 64x64 images.

- Classes: 40
- Samples per class: 10
- Samples total: 400
- Dimensionality: 4096 (64x64 pixels)
- Pixel values: real, between 0 and 1

### Model
**Convolutional Neural Network (CNN) with data augmentation**

Accuracy: 96%

## Movie Review Sentiment Analysis
### Dataset
**[IMDB Movie Reviews Dataset](https://www.tensorflow.org/datasets/catalog/imdb_reviews)**

Large Movie Review Dataset. This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. We provide a set of 25,000 highly polar movie reviews for training, and 25,000 for testing. There is additional unlabeled data for use as well.

### Model
**Logistic Regression**

Accuracy: 88%