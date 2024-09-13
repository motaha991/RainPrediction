# Weather Data Classification

This project involves classifying weather data to predict whether it will rain today using a Logistic Regression model. The dataset used in this project contains daily weather observations and includes features such as wind direction, wind gust direction, and rainfall information.

## Project Overview

The main steps of this project are:

1. **Data Preparation**:
   - Loading the dataset
   - Dropping irrelevant columns
   - Mapping categorical values to numerical values

2. **Feature Engineering**:
   - Encoding categorical variables using predefined mappings
   - Splitting the dataset into training and testing sets

3. **Model Training and Evaluation**:
   - Training a Logistic Regression model
   - Evaluating the model using various metrics

## Dependencies

The code requires the following Python libraries:

- `pandas`
- `numpy`
- `scikit-learn`

You can install these dependencies using pip:


```pip install pandas numpy scikit-learn ```

## Usage

### 1. Load the Dataset

Ensure that the dataset `Weather_Data.csv` is placed in the `/kaggle/input/daily-weather-observations/` directory.

### 2. Run the Code

Execute the code in a Python environment. The code performs the following tasks:

- **Reads the dataset**
- **Processes and maps categorical values**
- **Splits the data into training and test sets**
- **Trains a Logistic Regression model**
- **Evaluates the model's performance**

### 3. Evaluation Metrics

The model's performance is evaluated using:

- **Accuracy Score**
- **Jaccard Score**
- **F1 Score**
- **Log Loss**

### Code

Code can be found in .ipynb file in repo
