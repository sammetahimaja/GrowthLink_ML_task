# GrowthLink_ML_task
# Spam Detection Project - README

## 1. Task Objectives

This project aims to develop a machine learning model capable of accurately classifying SMS messages as either "spam" or "ham" (not spam). The specific objectives include:

* **Data Acquisition and Understanding:** Load and explore a dataset of SMS messages to understand its structure and characteristics.
* **Text Preprocessing:** Clean and prepare the text data for machine learning by handling noise and inconsistencies.
* **Data Visualization:** Visualize the distribution of spam and ham messages and identify common words in each category.
* **Handling Class Imbalance:** Address the potential imbalance between spam and ham messages using appropriate techniques.
* **Model Development and Evaluation:** Train and evaluate multiple classification algorithms to identify the most effective model for spam detection.
* **Hyperparameter Optimization:** Fine-tune the parameters of the best-performing model to maximize its predictive accuracy.
* **Model Persistence:** Save the trained model and necessary preprocessing tools for future use.
* **Prediction on New Data:** Demonstrate the model's ability to classify new, unseen SMS messages.
* **Performance Reporting:** Clearly present the performance metrics of the trained models.

## 2. Steps to Run Your Project

To execute this spam detection project, follow these structured steps:

1.  **Environment Setup:**
    * Ensure you have Python 3.x installed.
    * Install the required libraries using pip. It is highly recommended to use a virtual environment:
        ```bash
        python -m venv venv
        source venv/bin/activate  # On Linux/macOS
        venv\Scripts\activate  # On Windows
        ```
    * Install the dependencies from the `requirements.txt` file:
        ```bash
        pip install -r requirements.txt
        ```
    * Place the `spam.csv` dataset in the same directory as the Python script.

2.  **Execution:**
    * Open your terminal or command prompt.
    * Navigate to the project directory.
    * Run the main Python script:
        ```bash
        python your_script_name.py
        ```
        (Replace `your_script_name.py` with the actual filename of the script).

3.  **Output Interpretation:**
    * The script will output the following:
        * Data loading and exploration information.
        * Visualizations of class distribution and word clouds.
        * Class distribution after applying SMOTE.
        * Performance reports (confusion matrix, classification report, ROC curve) for each trained model (SVM, Naive Bayes, Decision Tree).
        * Results of hyperparameter tuning for the SVM model.
        * Performance of the final trained SVM model.
        * Predictions on a set of new, unseen messages.
        * A bar chart comparing the accuracy of the different models.
        * Confirmation messages upon saving the best model and vectorizer.

## 3. Code Structure and Comments

The Python script (`your_script_name.py`) is organized into well-defined functions and sections to enhance readability and maintainability:

```python


