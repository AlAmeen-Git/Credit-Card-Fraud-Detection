Credit Card Fraud Detection using Machine Learning

  1. Overview:
    This project builds and evaluates several machine learning models to detect fraudulent credit card transactions from a highly imbalanced dataset. The script handles data pre-processing (scaling and SMOTE for class imbalance), trains Logistic Regression, Decision Tree, and Random Forest models, and evaluates their performance.
    The dataset used contains transactions by European cardholders in September 2013 and is available on Kaggle.

  2. Results:
    The Random Forest classifier was the best-performing model, achieving a balanced and high performance in identifying fraudulent transactions.

    Best Model: Random Forest
    
    F1-Score: 0.8377
    
    Precision: 0.8602
    
    Recall: 0.8163

  3. How to Run the Code
    3.1 Prerequisites
    Ensure you have Python 3 and the following libraries installed:

    pandas
    
    numpy
    
    matplotlib
    
    seaborn

    scikit-learn

    imbalanced-learn

    3.2 Installation
    Install dependencies using pip:

    pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn

    3.3 Execution
    Save the code as a Python script (e.g., fraud_detection.py) or a Jupyter Notebook (.ipynb).

    To run as a script:

    python fraud_detection.py

    To run in a notebook:
    Open and execute the cells sequentially.

    The script will automatically download the data, train the models, and display the evaluation results.
