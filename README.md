**Traffic Sign Recognition Using CNN and Keras**

This repository contains a project that implements traffic sign recognition using Convolutional Neural Networks (CNN) with Keras and TensorFlow.

**Features**

CNN architecture with multiple layers and data augmentation.

Dataset with 58 traffic sign classes.

Easy to train, evaluate, and use the model for traffic sign recognition.


**Installation**

To set up the project, clone this repository and install the required dependencies by running:

pip install -r requirements.txt

**Dataset**

Download and unzip the dataset into the data/traffic-sign-dataset/ directory. Ensure the dataset has 58 traffic sign classes in separate folders.

**Usage**

To train the traffic sign recognition model, simply run:

python main.py

The script will load the dataset, preprocess it, and train a CNN model for classification.

**Results**

Once trained, the model achieves high accuracy in recognizing various traffic signs. You can view the accuracy progression through plots generated after training.
