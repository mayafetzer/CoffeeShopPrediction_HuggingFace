# Project: Coffee Shop Prediction Using Machine Learning - Hugging Face

## Author
Maya Fetzer  
Semester: Fall 2024  
Course: CHEG 472  

## Purpose
This repository holds the code to run an app that will predict whether a customer will order a latte, cappuccino, or espresso based on different independant variables like order time, caffiene tolerance, etc. 

## Files In This Repository
app.py - Python code to create the Hugging Face interface

best_model.pkl - a pickle file that contains the best ML model for the dataset

coffee_recommendation_dataset.xlsx - the training dataset

label_encoder.pkl - a pickle file that encodes the data

requirement.txt - requirements file

## Prerequisites

### Python
Ensure you have Python 3.10 or later installed.

### Libraries
Install the following libraries using pip:

```
pip install gradio
pip install pandas
pip install numpy
pip install sklearn
pip install openpyxl
pip install pickle5
```

## Explanation

- **Streamlit**: Provides a simple way to create interactive web applications with Python.
- **Matplotlib**: Used for creating visualizations like plots and charts.
- **Pandas**: Offers data structures and analysis tools for working with tabular data.
- **NumPy**: Provides efficient numerical operations and arrays.
- **Sklearn**: Machine learning library.
- **Gradio:** A user-friendly library for building and sharing interactive web interfaces for machine learning models and data science projects.
- **Openpyxl:** A library for reading and writing Excel files in the XLSX format, making it easy to work with spreadsheets directly from Python.
- **Pickle5:** An enhanced version of Python's pickle module for object serialization and
