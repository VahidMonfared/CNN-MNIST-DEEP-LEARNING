# **Fashion MNIST Image Classification using CNNs**
In this application, we will continue to work on the Fashion MNIST dataset and will try to figure out how CNNs are applied to the image data.
Here, we will create a simple model with only a limited set of features and talk about the architecture. Please feel free to add/modify the architecture as per your understanding.


# **MNIST Handwritten Digit Classification using a CNN**
**This notebook will help you understand the below points:**
*   A brief introduction to the MNIST Dataset and its importance in Computer Vision
*   Building a baseline classification model using a CNN
*   Evaluating the CNN model
*   Building an improved CNN
*   Finalizing the improved model for prediction on the test dataset
The **MNIST** dataset is an acronym that stands for the **Modified National Institute of Standards and Technology** dataset.
*   **This dataset consists of 60,000 grayscale images**, which are small 28x28 pixel images.
<br> **These are images of handwritten digits from 0 to 9.**
*   **The task is to correctly classify the image of a handwritten digit into the right number**, that is - one of the 10 numbers from 0 to 9.
*   These numbers are mutually exclusive choices and we have over two choices in number, and hence **this represents a multi-class classification** problem in supervised learning.
*   **MNIST has been an important and widely-used dataset in machine learning and computer vision.** It is sometimes called the "Hello World" of computer vision, and is one of the first image datasets that all deep learning based computer vision practitioners learn to work with. A great amount of research have been carried out to outperform the existing state-of-the-art and achieve the best possible accuracy in classifying the images in MNIST.
<br> It is hence a benchmark of sorts, to test the latest deep learning architectures in the field of computer vision.
*   More importantly for us, **MNIST is a dataset where Convolutional Neural Network (CNN) based approaches have shown excellent performance**, and that is what we will try to implement as part of this case study.
