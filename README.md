### Rumour Detection using Machine Learning

## Introduction
The following project aims to detect whether a piece of news is fake or real by using Machine Learning algorithms. The dataset has been provided in the repository itself. The Python code for the project has been uploaded as well, which includes data preprocessing, training of the model, and testing.

## Technologies Used
The following technologies and libraries have been used in the project:

- Python 3
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

## Dataset
The dataset used for this project has been uploaded in the repository. It contains two columns, i.e., headlines and bodies, and a label column indicating whether the news is fake or real.

## Installation and Setup
The following libraries need to be installed to run the project:

- Scikit-learn
- Pandas
- NumPy
- Matplotlib

## To set up the project, follow the steps given below:

1. Clone the repository to your local machine.
2. Open the terminal and navigate to the project directory.
3. Run the `rumordetectionusingmachinelearning.py` file using the following command: 
`python rumordetectionusingmachinelearning.py`

## Data Preprocessing
The following steps have been taken to preprocess the data:

1. The dataset has been read using Pandas.
2. The label column has been separated from the dataset.
3. The headline and body columns have been concatenated.
4. The data has been split into training and testing data.
5. The CountVectorizer and TfidfVectorizer have been used to convert the text data into numerical data.

## Model Training
The following Machine Learning algorithms have been used for training the model:
1. Random Forest Classifier
2. K-Nearest Neighbors Classifier
3. Passive Aggressive Classifier
4. Support Vector Classifier

## Model Evaluation
The accuracy of the model has been evaluated using the accuracy score and confusion matrix. The confusion matrix has been plotted using the plot_confusion_matrix() function.

## Conclusion
The project aims to detect fake news using Machine Learning algorithms. **The accuracy of the model has been calculated to be around 94%.** The confusion matrix plotted shows that the model is good at detecting fake news.
