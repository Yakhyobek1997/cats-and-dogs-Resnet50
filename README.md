# cats-and-dogs-Resnet50-
This project involves building and training a convolutional neural network (CNN) model to classify images of cats and dogs. which is a pre-trained CNN, and adapts it to distinguish between two classes: cats and dogs.



Project Overview:
Data Preparation:

The dataset contains images of cats and dogs, divided into training and test sets.
Images are preprocessed by resizing to a standard size, cropping to the center, converting to tensor format, and normalizing.
Model Creation:

The ResNet50 model is modified to classify the images into two classes (cats and dogs).
Model Training:

The model is trained on the training dataset using the cross-entropy loss function and the Adam optimizer.
During training, both training and validation losses and accuracies are tracked.
Model Evaluation:

The model is evaluated on the test dataset, and results are visualized using a confusion matrix to show how well the model classifies the images.
Results Visualization:

Training and validation losses and accuracies are plotted over the training epochs.
A confusion matrix is displayed, showing the model's correct and incorrect classifications.
