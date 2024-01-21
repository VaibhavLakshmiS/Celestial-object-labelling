
# Setup Instructions for Running the Celestial Objects Classification Code

## Prerequisites
- A Python environment (preferably an interactive environment like Jupyter Notebook)
- Access to the internet for downloading datasets and Python packages
- The dataset files (`celestial_train.csv` and `celestial_test.csv`) available locally

## Steps

### 1. Installing Required Libraries
Ensure the following Python libraries are installed:
- pandas
- numpy
- scikit-learn
- TensorFlow

You can install these libraries using pip, for example:
```bash
pip install pandas numpy scikit-learn tensorflow
```

### 2. Loading the Dataset
- Place your dataset files (`celestial_train.csv` and `celestial_test.csv`) in an accessible directory.
- Update the file paths in the code to match the location where you have stored these files.

### 3. Running the Code
- Copy the Python code from the notebook into your Python environment.
- Run each code cell in sequence to ensure proper execution of the steps.

### 4. Model Training and Evaluation
- The code will train a neural network model on the training dataset.
- The model's performance will be evaluated using K-Fold Cross-Validation.

### 5. Generating Predictions
- After training, the model will be used to generate predictions on the test dataset.
- The predictions will be saved to a CSV file, whose path you can specify in the code.
