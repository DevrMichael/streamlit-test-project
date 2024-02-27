
# Machine Learning Classifier with Streamlit

## Description

This project is a web-based machine learning application designed to classify data from different datasets using various machine learning models. It utilizes Streamlit for the user interface, allowing users to select datasets and classifiers, and view the classification results, including accuracy metrics. The application supports three datasets (Iris, Breast Cancer, Wine) and three machine learning models (K-Nearest Neighbors, Support Vector Machine, Random Forest) for classification tasks.

![Streamlit-readme](https://github.com/DevrMichael/streamlit-test-project/assets/88589247/e0863fba-9fef-4b4b-a683-ed4ae4b61784)


## Features

- Interactive Streamlit web interface
- Supports classification on Iris, Breast Cancer, and Wine datasets
- Includes K-Nearest Neighbors, Support Vector Machine, and Random Forest classifiers
- Dynamic hyperparameter tuning through the Streamlit sidebar
- Displays dataset shape, number of classes, and classification accuracy

## Installation

To run this project, you will need Python installed on your system. It's recommended to use a virtual environment for Python projects to manage dependencies effectively.

1. **Clone the repository to your local machine:**
```bash
  git clone https://github.com/DevrMichael/streamlit-test-project.git
```
   
2. **Install the required dependencies:**
 ```bash
   pip install -r requirements.txt
   ```
   This command will install Streamlit and scikit-learn among other necessary packages.

## Usage

To start the application, run the following command in your terminal from the project directory:
```bash
  streamlit run app.py
  ```
After running the command, Streamlit will automatically open your default web browser and navigate to the local server address (typically `http://localhost:8501`) where the application is running. Use the sidebar to select the dataset and classifier you wish to use, adjust the model parameters as needed, and view the classification results and accuracy on the main page.

