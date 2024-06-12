# Object-Centric Image Classification with Deep Learning

## Overview
Object-centric image classification involves training a model to classify images based on the objects present within them. The objective is to teach the model to recognize various objects within an image accurately and classify the image based on those objects. This task finds applications in real-world scenarios such as security camera feeds, online shopping catalogs, and medical image analysis. The primary challenge lies in training the model to identify objects under different conditions like orientations, sizes, lighting, and handling multiple objects within the same image.

## Final Project Description
In this final project for the course Deep Learning, we implemented an Object-Centric Image Recognition task using deep convolutional neural networks (CNNs) with Autoencoder. The project aims to classify images based on the objects they contain using a dataset comprising CIFAR10, CalTech101, and CalTech256.

## Dataset
The project utilizes three different datasets:
1. **CIFAR10:** A dataset containing 10 classes of images, including various animals, vehicles, and everyday objects.
2. **CalTech101:** A dataset consisting of images across 101 object categories, such as faces, animals, and household objects.
3. **CalTech256:** A more extensive dataset extending the CalTech101 dataset to 256 object categories, offering a wider variety of objects for classification.

## Approach
1. **Data Preprocessing:** The datasets are preprocessed to ensure consistency and compatibility with the deep learning model.
2. **Model Architecture:** A deep CNN architecture is designed and implemented, incorporating an Autoencoder for object-centric image classification.
3. **Training:** The model is trained on the combined dataset using appropriate training techniques and optimization algorithms.
4. **Evaluation:** The trained model's performance is evaluated on test data to assess its accuracy and effectiveness in classifying object-centric images.

## Results
The project aims to achieve high accuracy in classifying object-centric images across the CIFAR10, CalTech101, and CalTech256 datasets. The results obtained from the trained model are analyzed to measure its performance and identify areas for improvement.

## Repository Structure
- **data:** Contains the CIFAR10, CalTech101, and CalTech256 datasets.
- **code:** Includes the code for data preprocessing, model implementation, training, and evaluation.
- **results:** Contains the results and performance metrics obtained from the trained model.
- **README.md:** Provides an overview of the project, dataset, approach, and instructions for running the code.

## Usage
1. Clone the repository
2. Navigate to the project directory
3. Install dependencies
4. Run the code files in the colab to preprocess the data, implement the model, train, and evaluate its performance.

## Contributors
Aarthi Lakshmipathy.  

Archana Jayaraman.  

Chandrasekaran Subramanian Ravichandran.  

