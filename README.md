# Whale-Identification-using-Convolutional-Neural-Networks
The project titled "Whales Identification Using Convolutional Neural Network" aims to automate the process of identifying individual humpback whales based on their fluke patterns. Manual identification of whales is time-consuming and prone to errors, so the goal is to create a CNN model that can accurately recognize and classify humpback whales.
**Dataset Description** 
Images of humpback whales taken by drones are included in the dataset for humpback whale
identification. As humpback whales have distinctive markings on their tails called flukes, the
dataset's goal is to help researchers and marine biologists identify specific whales.
A total of 25,000 photos of humpback whale flukes are included in the dataset, each of which
has been labelled with the whale's unique individual identification number.
The dataset was preprocessed to eliminate unnecessary images, reshape them to a standard
dimension, and augment it by horizontally and vertically rotating images.
     o The train set contains 9851 images.
     o The test set contains 15,610 images
Dataset Links: https://www.kaggle.com/competitions/humpback-whale-identification/data

**Implementation**
The model is trained using the training dataset with 9851 images. The training process involves running the complete training dataset through the model for 200 epochs. The batch size determines the number of samples used in each iteration to update the model weights. The training progress is printed to the console, and the model's performance on the validation set is evaluated after each epoch.
