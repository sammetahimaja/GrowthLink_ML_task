#  GrwothLink_ML_Task
# Spam Detection Project

## Overview

This project develops a machine learning model to classify SMS messages as either **spam** or **ham** (not spam). It involves data loading, preprocessing, visualization, handling class imbalance, training and evaluating multiple classification models, and testing the best model on new data.

## Key Features

* **Data Handling:** Loads and explores SMS message data from a CSV file.
* **Text Preprocessing:** Cleans and prepares text data for machine learning.
* **Data Visualization:** Provides insights into class distribution and common words.
* **Class Imbalance Handling:** Utilizes SMOTE to address potential class imbalance.
* **Model Training:** Trains and evaluates SVM, Naive Bayes, and Decision Tree classifiers.
* **Performance Evaluation:** Reports key metrics (accuracy, precision, recall, F1-score, confusion matrix, ROC curve, AUC).
* **Model Comparison:** Visualizes the performance of different models.
* **New Data Prediction:** Demonstrates the classification of unseen SMS messages using the best model (SVM).

## Getting Started

### Prerequisites

* Python 3.7+
* pip (Python package installer)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/sammetahimaja/GrowthLink_ML_task
    cd GrwothLink_ML_task
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Linux/macOS
    venv\Scripts\activate  # On Windows
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Ensure the dataset (`spam.csv`) is in the project directory.**

### Running the Code

1.  **Open the Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

2.  **Navigate to and open `Spam_detection.ipynb`.**

3.  **Run the notebook cells sequentially to execute the spam detection pipeline.**

## Project Structure
Spam Detection Project/

├── Spam_detection.ipynb   # Jupyter Notebook with the project code

├── requirements.txt           # List of Python dependencies

├── spam.csv                   # Dataset of SMS messages

└── README.md                  # This README file

## Code Highlights

* **Data Loading & Exploration:** Functions to load and understand the dataset (`load_data`, `basic_data_exploration`).
* **Text Preprocessing:** Functions for cleaning and preparing text (`combine_text_columns`, `preprocess_text`).
* **Visualization:** Functions to display class distribution and word clouds (`plot_class_distribution`, `generate_word_cloud`).
* **Model Training & Evaluation:** Functions to prepare data, initialize, train, and evaluate models (`prepare_data`, `train_and_evaluate_models`).
* **Model Comparison:** Function to visualize model performance (`plot_model_comparison`).
* **New Data Testing:** Function to test the best model on new examples (`test_svm_model`).
* **Main Execution:** The `main()` function orchestrates the entire pipeline.

## Results

The Jupyter Notebook will output:

* Exploratory data analysis insights.
* Visualizations of class distribution and word frequencies.
* Performance reports (classification reports, confusion matrices, ROC curves) for each trained model.
* A comparison of the models' accuracy.
* Predictions on new, unseen SMS messages using the SVM model.

## Libraries Used

* pandas: Data manipulation
* numpy: Numerical computation
* re: Regular expressions
* scikit-learn (sklearn): Machine learning
* wordcloud: Word clouds
* matplotlib.pyplot: Plotting
* imblearn: Imbalanced data
* collections: Counting
* joblib: Saving/loading objects

## Author

[sammetahimaja]
