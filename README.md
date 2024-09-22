# deep-learning-challenge
This project involves building a deep learning model to predict the success of charity funding applications based on various features in the dataset. The model aims to help organizations identify the most promising applications for funding. The dataset includes several features related to the charity applications, such as application type, affiliation, classification, and funding request amount. A deep neural network model is developed using TensorFlow and Keras for classification purposes.

The project begins with data preprocessing, which includes cleaning the dataset by dropping non-beneficial columns and handling categorical variables through one-hot encoding. The data is then split into features and target arrays, followed by dividing it into training and testing sets. The model consists of two hidden layers and is compiled with the Adam optimizer and binary cross-entropy loss function. After training the model on the scaled training data for 100 epochs, its performance is evaluated on the test data, providing loss and accuracy metrics.

Finally, the trained model is exported in HDF5 format for future use. This project demonstrates the application of deep learning techniques to solve a real-world problem in charity funding applications, with the model's predictions aiding organizations in making informed funding decisions.