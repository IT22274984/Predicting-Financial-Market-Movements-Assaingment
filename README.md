#  Predicting Financial Market Movements Using the NASDAQ Historical Daily Prices Dataset 
 

This project involves preprocessing energy data, feature engineering, and training a model to analyze the dataset. The steps provided below outline how to set up and run the code.
---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Setup Instructions](#setup-instructions)
3. [Running the Code](#running-the-code)
   - [Using Jupyter Notebook](#using-jupyter-notebook)
4. [File Structure](#file-structure)

---

## Project Overview
This assessment focuses on:
- Exploratory Data Analysis (EDA) and Data Preprocessing
- Feature Engineering
- Model Training and Evaluation

Generated datasets:
- `NASDAQ_Scaled_Full.csv`
- `final_features_model_input.csv`

---

## Setup Instructions
1. **Dependencies**: Ensure all required libraries are installed. Use the `requirements.txt` file:
   ```bash
   pip install -r requirements.txt
   ```
2. **Tools**: Ensure you have either:
   - Jupyter Notebook (installed locally)
   
---

## Running the Code

### Using Jupyter Notebook
1. **Setup Environment**:
   - Install the libraries in `requirements.txt`.  
   - Open the terminal, navigate to the project folder, and start Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
2. **File Modifications**:
   - Open `EDA & Data Preprocessing.ipynb` and:
     local directory paths:
       - Example:
         ```python
         processed_file_path="C:\\Users\\shant\\Downloads\\quant-nasdaq-project\\data\\NASDAQ_Scaled_Full.csv"
         ```
   - Repeat the above step for:
     - `Feature Engineering.ipynb`
     - `model_and_train.ipynb`
3. **Run the Code**:
   - In each notebook, select **Run All Cells** or execute cells sequentially.
   - After running:
     - `EDA & data_preprocessing.ipynb` → Generates `NASDAQ_Scaled_Full.csv`.
     - `feature engineering.ipynb` → Generates `final_features_model_input.csv`.
     - `model_and_train.ipynb` → Trains and evaluates the model.

---



## File Structure
```
quant-nasdaq-project/
│
├── data/
│   ├── final_features_model_input.csv
│   └── NASDAQ_Features_X.csv
│   ├── NASDAQ_Target_y.csv
│   ├── NASDAQ_Scaled_Full.csv
│   ├── model_training.csv
│   

├── notebooks/
│   ├── EDA & Data Preprocessing.ipynb
│   ├── Feature Engineering.ipynb
│   ├── model_and_train.ipynb
│   └── .ipynb_checkpoints/
│       └── EDA & Data Preprocessing-checkpoint.ipynb
│
├── src/
│   ├
│
├── models/
│   ├── gru_model.pth
│   └── cnn_lstm_model.pth
│   ├── linear_regressor.pkl
│   ├── lstm_model.pth
│   └── random_forest.pkl

├── reports/
│   ├── eda_report.html
│   
│   
│
├── requirements.txt
├── README.md


```

Thank you for reading!

