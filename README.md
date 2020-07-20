# Neural-Networks-and-Deep-Learning-Models

#### In this project we had to create a binary classifier that is capable of predicting whether or not an applicant will be successful if funded by Alphabet Soup using the features collected in the provided dataset.

#### The goals of this project are for you to:

- Import, analyze, clean, and preprocess a “real-world” classification dataset.
- Select, design, and train a binary classification model of your choosing.
- Optimize model training and input data to achieve desired model performance.

#### Technologies used in the project:
- Python
- TensorFlow
- Jupyter Notebook
- GitHub
- a CSV file with data

### Summary:
##### - Neurons and layers selected for the neural network model
In this project I used a few steps and options to perform the training. Starting with one hidden layer and few neurons and increasing the number gradualy with different variation. The maximum number of neurons used in the first hidden layer was equal to the input pions multiplied by 2. The maximum number of hidden layers was three.
##### - The target model performance is predictive accuracy 75% or higher.
To be able to increase model performance I took many steps starting from one hidden layer and optimized the model by increasing hidden layers number, applying different activation functions in hidden layers and output layer, and increasing the numbers of neurons. Also, non-feature variables were eliminated.

##### - What other options of different models could be implemented to solve this classification problem?
There are several models of supervised ML that can process and train such data sets. I used Random forest and Logistic Regression to see how it works on this data. In this case Neural network excels over Logistic Regression because the data is pretty big and more compex. Random Forest is very similar to deep learning model though much faster and requires less code. But neither Random Forest nor Logistic Regression gave better result. So even though the neural network and deep learning result is not reaching 75%, it is still better than these two models. 
There is SVM model as well that can be applied. And perhaps there are many more models in ML that can be used for this project. With more study more options come.

This data set may not be perfect for funding success prediction. The max result that we could get is 74.47% accuracy and 17.61% loss.
In the file "Extension_challenge_experiment.ipynb" I was doing an analysis with reduced features based on my own judgment - I droped "Classification" column. The goal was to test how it impacts the training. The thought process behind was that this data attribute may not be relevant to the applicant status. This feature is more like an identification because this is a goverment organization classification.
