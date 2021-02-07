# Computer Vision - Image recognition via Deep Learning

## Project's objective

Identify handwritten digits with the highest accuracy possible.

## Data

The data used for this project comes from the MNIST dataset which is a very good basis for people who want to try learning techniques and pattern recognition method on real-world data.

The data contains contains 70,000 instances of labeled images (28x28 pixels) representing handwritten digits going from 0 to 9.

![image-2.png](attachment:image-2.png)

These image-label pairs are divided into 60,000 training examples and 10,000 testing examples.

## Methodology

For this project, the classification problem is tackled via Supervised Deep Learning. 
First of all, a data pre-processing step will be performed to explore the MNIST dataset and prepare data for analysis via encoding, formatting, and normalizing.
Then, two neural networks will be built: 

* Multi-Layer Perceptron (MLP)
* Convolutional Neural Network (CNN)

Models' hyperparameters configuration will be tuned to maximize performances while preventing classic issues such as overfitting. 
Results will be finally compared to identify which model yields the highest accuracy.

