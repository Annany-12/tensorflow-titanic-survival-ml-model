# TensorFlow Titanic Survival ML Model

This project uses a machine learning model built with TensorFlow to predict the survival rate of passengers on the Titanic. The dataset used for this project is the well-known Titanic dataset, which includes features such as age, gender, class, and fare.

## Features

- **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.
- **Model Training**: Using TensorFlow's `LinearClassifier` to train a logistic regression model for survival prediction.
- **Survival Prediction**: Allowing users to input passenger details and predict their survival probability.

## Methodology

The project follows a standard machine learning pipeline:

1. **Data Preprocessing**:
   - Load the Titanic dataset.
   - Handle missing values.
   - Encode categorical variables using one-hot encoding.
   - Scale numerical features.

2. **Feature Engineering**:
   - Select relevant features.
   - Define feature columns using TensorFlow's `tf.feature_column`.

3. **Model Training**:
   - Build a logistic regression model using TensorFlow's `LinearClassifier`.
   - Train the model on the preprocessed data.

4. **Model Evaluation**:
   - Evaluate the trained model on a test dataset.
   - Calculate performance metrics like accuracy, precision.

5. **Prediction**:
   - Allow users to input passenger details.
   - Predict their survival probability.

## Dataset

The dataset used in this project can be found [here](https://www.kaggle.com/c/titanic/data).

## Installation

To run this project, you need to have Python installed along with the following libraries:

- TensorFlow
- pandas
- matplotlib
- seaborn

You can install these dependencies using the following command:

```bash
pip install tensorflow pandas matplotlib seaborn
```

## Usage

1. **Clone the Repository**:
   ```git clone https://github.com/your-username/tensorflow-titanic-survival-ml-model.git```
2. **Navigate to the project directory**:
   ```cd tensorflow-titanic-survival-ml-model```
3. Open the notebook.
4. Run the notebook cells to preprocess the data, train the model, and make predictions.

## Future Improvements

- Explore other machine learning algorithms like decision trees or ensemble methods.
- Implement more advanced feature engineering techniques.
- Deploy the model as a web application or API for easier user interaction.
