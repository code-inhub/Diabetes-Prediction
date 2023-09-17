# Diabetes Prediction Model

This Python script implements a diabetes prediction model using a Support Vector Machine (SVM) classifier. The model is trained on a dataset containing various health-related features to predict whether a person is diabetic or not. This README provides an overview of the code and how to use it.

## Dependencies

The following Python libraries are used in this project:

- `numpy` and `pandas` for data manipulation.
- `sklearn` for machine learning operations, including data preprocessing and SVM classification.
  
You can install these libraries using pip:

```bash
pip install numpy pandas scikit-learn
```

## Data Collection and Analysis
The dataset used for this project is loaded from a CSV file named diabetes.csv. It contains information on various health parameters and the diabetes outcome. The dataset is analyzed to understand its structure and characteristics.

## Training the Model
The SVM classifier is used to train the model. The SVC (Support Vector Classification) with a linear kernel is employed for this purpose.

## Model Evaluation
The model's accuracy is evaluated using two sets of data: training data and test data. The accuracy score on both datasets is calculated and displayed.

## Making Predictions
The trained model can make predictions on new data. An example input data point is provided, and the script predicts whether the person is diabetic or not based on the trained model.

## How to Use
1. Clone this repository to your local machine.
```bash
git clone https://github.com/your-username/diabetes-prediction.git
```
2. Navigate to the project directory.
3. Install the required dependencies.

```bash
pip install numpy pandas scikit-learn
```
4. Run the script.

```bash
python diab_predic.py
```
5. The script will provide the accuracy scores on the training and test datasets and make a prediction based on the example input data.
