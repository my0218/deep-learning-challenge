# deep-learning-challenge
Overview of the Analysis:

The purpose of this analysis is to develop a deep learning neural network model for Alphabet Soup, with the goal of predicting the success of funding applications. The model is trained on a preprocessed dataset containing various features and the target variable indicating the success of the funding applications. The analysis aimed to optimize the model's performance and accuracy through appropriate data preprocessing, model architecture selection, and hyperparameter tuning.

Results:

Data Preprocessing:
Target Variable: The target variable for the model is "IS_SUCCESSFUL," which indicates the success (1) or failure (0) of funding applications.
Features: The remaining variables in the dataset, excluding the target variable, are considered as features for the model.
Variables to Remove: The "EIN" and "NAME" columns were removed from the input data as they were neither targets nor features.
Compiling, Training, and Evaluating the Model: Neurons, Layers, and Activation Functions: For the neural network model, two hidden layers were chosen with 80 and 30 nodes, respectively. The first hidden layer used the 'relu' activation function, and the second hidden layer used the 'sigmoid' activation function. The output layer consisted of a single node with the 'sigmoid' activation function, suitable for binary classification tasks. These choices were made to allow the model to learn complex patterns while avoiding issues like vanishing gradients.
Target Model Performance: The target model performance was 72.5%
Steps to Increase Model Performance: Several steps were taken to improve the model's performance: Increasing epochs, adding one more layers and using different activation functions. Unfortunately, none of these optimization method didn't increase the performace over 75%.

Summary:
The deep learning neural network model performed well in predicting the success of funding applications. The model's architecture was designed with two hidden layers and appropriate activation functions to capture complex patterns in the data. The achieved model performance, in terms of accuracy, met the target expectations.

A recommendation for a different model to solve this classification problem would be to explore ensemble methods, such as random forest or gradient boosting. These techniques combine multiple models to improve prediction accuracy. Considering the availability of a diverse set of features, these ensemble methods could potentially leverage different aspects of the data to make more accurate predictions.

Overall, the deep learning neural network model presented a promising solution for predicting funding application success. The recommendation for exploring ensemble methods allows for further exploration and potentially enhanced accuracy in this classification problem.
