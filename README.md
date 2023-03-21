# SONAR Rock vs Mine Prediction Model
## Problem Statement
The detection and classification of underwater objects, such as rocks and mines, are crucial in naval operations, underwater surveillance, and environmental monitoring. Traditional methods of detecting underwater objects, such as sonar imaging, can be time-consuming and labor-intensive, requiring trained personnel to interpret the data. Therefore, there is a need for an accurate and efficient model that can predict whether a given sonar image represents a rock or a mine. A reliable and efficient model for detecting rocks and mines would improve the safety of underwater operations, prevent environmental damage, and reduce the cost and time associated with manual analysis of sonar images.
## Data Information
The dataset can be download using this [link](https://drive.google.com/file/d/1pQxtljlNVh0DHYg-Ye7dtpDTlFceHVfa/view)

The dataset contains SONAR values of objects which are classified as either mine or rock. R indicates a rock and M indicates a mine.
## Project Pipeline
* Understanding the Data:  We load the data into a dataframe using Pandas and understand the features present in it. This helps in choosing the features that will be needed for the final model.
* Data Preprocessing: Data preprocessing is the essential step of cleaning and transforming raw data to make it suitable for machine learning models. As the current dataset is balanced and numerical without much variations in values, we can use the data as is.
* Train/Test Split: The data is split into two sets: one for training the model and the other for testing its performance. We use the train_test_split function available in the sklearn library to perform the operation.
* Model Training and Evaluation: Here we can try different models until we get the desired level of performance on the given dataset. We use the Decision Tree Classifier as our model available in the sklearn library. We also need to evaluate the models using appropriate evaluation metrics.
