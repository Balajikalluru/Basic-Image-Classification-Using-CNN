# Basic-Image-Classification-Using-CNN

This project implements a Convolutional Neural Network (CNN) for image classification using the CIFAR-10 dataset, which contains 60,000 images across 10 categories, such as airplanes, cars, birds, and more. The model consists of three convolutional layers with ReLU activation, followed by max-pooling layers to reduce dimensionality. The final layers include a fully connected layer and a softmax output layer for classification into the 10 categories. The dataset is preprocessed by normalizing pixel values to improve model performance.

The model is compiled using the Adam optimizer and sparse categorical cross-entropy loss. After training for 100 epochs, the model achieves approximately 67% accuracy on the test set. Visualization of the training and validation accuracy/loss is provided to track model performance. Additionally, a comparison of actual versus predicted images is displayed, showcasing the model's ability to classify test images.
