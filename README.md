## Introduction and Problem Statement
Human facial expression recognition (FER) is one of the most powerful and challenging 
tasks in social communication. In general, facial expressions are a natural and direct 
means for people to communicate their feelings and intentions. Facial expressions are 
key features of non-verbal communication. The performance of different FER 
techniques is compared based on the number of expressions identified and the 
complexity of the algorithms.
Our task is to make a machine learning model to identify human facial recognition. using 
digital image processing, facial emotions can be detected efficiently. these technologies 
are currently used on various social platforms. here we use the Kaggle platform to 
analyze facial data and train our machine learning model.

## Details of the Dataset
The dataset we are going to use in our model is publicly available on the Kaggle 
platform. Over 35,000 photographs were collected in the data in 2013, some of the 
existing photographs were taken from various media publications and some of them 
consist of stock photographs. Our goal here is to recognize 7 different emotions through 
photographs with a convolutional neural network.

- The dataset consists of 7 different Human facial expression classes. (angry, happy, scared, disgust, fear, fear natural, etc.)
- Data consists of 48x48 pixel grayscale images of faces.
- Faces are automatically registered so that the face is more or less centered and occupies the same amount of space in each image.

## Preprocess Techniques
We use the following data preprocessing techniques to prepare our data set before training our model to improve data quality.
- Check the data formats 
- Checking value counts 
- Checking and handling null values 
- Visualizing random images from training set
- Visualizing Distribution of Labels
- Converting String pixel values to images of 48 x 48
- Label encoding to convert categorical variable into numerical variables
- Balancing unbalance data set with image generating
- Splitting the dataset into a training set and testing set

## Summary of the finalized dataset
After the preprocessing process, we are left with a dataset that has over 50000 images. because we did an image-generating process on data to balance the classes. And all the training and testing images are 48 x 48 NumPy arrays. And finally, our dataset is divided into 80% for the training set and 20% for the testing set.
