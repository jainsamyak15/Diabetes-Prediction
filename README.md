# Diabetes Prediction using PySpark

This project aims to build a machine learning model for predicting diabetes using PySpark, a distributed computing framework for big data processing. The model is trained on a diabetes dataset, and the entire process involves data exploration, cleaning, feature selection, model building, evaluation, and prediction.

## Project Overview

1. **Install Dependencies & Run Spark Session**: Install the required dependencies (PySpark) and create a Spark Session for distributed computing.

2. **Clone & Explore Dataset**: Clone the diabetes dataset from a GitHub repository, check its existence, create a Spark DataFrame, and explore the dataset by displaying the schema, summary statistics, and class distribution.

3. **Data Cleaning & Preparation**: Check for null values, identify and replace unnecessary values with the mean, and prepare the dataset for further processing.

4. **Correlation Analysis & Feature Selection**: Analyze the correlation among input and output variables, and select the most relevant features for model building.

5. **Split Dataset & Build the Model**: Create the final dataset, split it into training and testing sets, and build a machine learning model (e.g., Logistic Regression, Random Forest, etc.) for diabetes prediction.

6. **Evaluate and Save the Model**: Evaluate the model's performance using appropriate metrics (e.g., accuracy, precision, recall, F1-score), and save the trained model for future use.

7. **Prediction on New Data**: Load the saved model, create a new Spark DataFrame with unseen data, and make predictions using the trained model.

## Requirements

- Python
- PySpark
- Jupyter Notebook or Google Colab

## Usage

1. Clone the repository or download the project files.
2. Install the required dependencies (PySpark).
3. Open the `Diabetes_Prediction.ipynb` notebook in Jupyter Notebook or Google Colab.
4. Follow the instructions in the notebook to run the code cells and complete each task.

## Results

The project demonstrates the end-to-end process of building a machine learning model for diabetes prediction using PySpark. The trained model can be used to make predictions on new, unseen data, enabling early detection and preventive measures for diabetes.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
