# Group 3, Project 4
University of Denver Data Analytics Bootcamp: Project 4

Group Members:
Evan Cromwell
Alex Heilman
Emily Notaro
Jennifer Vincent

## Project Background:
- For this project, our group aimed to create a data model that can differentiate between different images of food. We used the food101 dataset from TensorFlow. This dataset includes pictures of food which fall into a wide range of 101 labeled categories, including everything from escargot to chocolate cake. There are 750 training images and 250 testing images of each category of food, for a total of 101,000 images.

- We specifically were interested in this topic because throughout class, we have discussed whether Americans prefer Italian or Mexican food. Although we are not answering this question with our model, we thought it would be fun to make our project related to that topic, and there are plenty of Italian and Mexican foods in this dataset. We narrowed the data down to just pictures of pizza and tacos to represent those two cuisines.

## Project Execution:
- In a Python script, we used tensorflow_datasets to load in our dataset, and then we split the dataset into training and validation sets. Then, we reduced the dataset to just pictures of pizza and tacos. This reduced the number of training images to 1500 and testing images to 500.  Then we built our Convolutional Neural Network using multiple layers of convolutional 2D layers and max pooling layers. Then we used a flatten layer to change the 2D output to 1D. We also included a Dropout layer to help prevent overfitting. We set the batch size and number of epochs. Then we preprocessed the data by normalizing the pixel values and image sizes. We then trained our model. Finally, we evaluated our model by printing the validation accuracy. At first, our validation accuracy was about 20%, but we made modifications to our model and were able to achieve the desired accuracy level of over 75%.

## Requirements and Point Values
- Data Model Implementation (25 points)
- Data Model Optimization (25 points)
- GitHub Documentation (25 points)
- Group Presentation (25 points)

## Additional Support and Resources Used:
stackoverflow.com
paperswithcode.com
