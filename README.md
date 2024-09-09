# PySpark Credit Card Fraud Detection

This repository contains a notebook for detecting credit card fraud using machine learning techniques with PySpark. The project includes data preprocessing, feature engineering, model building, and evaluation of results. This analysis is aimed at building an accurate model to identify fraudulent transactions.

## Dowload and Extract the dataset from Kaggle: 
[[dataset link](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)].
## Project Structure

- `PySpark_Credit_Card_Fraud_Detection.ipynb`: The main notebook that contains all the code for the project, including data loading, processing, model training, and evaluation.
- `requirements.txt`: A file containing all the necessary dependencies required to run the notebook.

## Installation

1. Clone the repository:
    ```bash
    git clone <this-repo-url>
    cd <repository-directory>
    ```

2. Create a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## How to Run

1. Ensure that you have the required dependencies installed by following the above instructions.
2. Open the Jupyter notebook:
    ```bash
    jupyter notebook PySpark_Credit_Card_Fraud_Detection.ipynb
    ```
3. Run the notebook cells step by step to see the full credit card fraud detection pipeline.

## Key Features

- **Data Preprocessing**: Includes handling missing values, scaling features, and encoding categorical data.
- **Feature Engineering**: Extracts meaningful features to improve model performance.
- **Model Building**: Utilizes machine learning models like Logistic Regression, Random Forest, etc., to detect fraud.
- **Evaluation**: Assesses model performance with metrics such as accuracy, precision, recall, and F1-score.

## Dataset

The dataset used in this project contains credit card transactions labeled as fraudulent or non-fraudulent. The dataset is not included in this repo. You can download it from [[dataset link](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)].

## Requirements

All required packages are listed in the `requirements.txt` file. Key dependencies include:
- PySpark
- Pandas
- Scikit-learn
- Matplotlib

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
