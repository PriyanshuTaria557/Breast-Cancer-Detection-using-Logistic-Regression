<h1 align="center">🔬 Breast-Cancer-Detection-using-Logistic-Regression 🧠</h1>


A Machine Learning project that applies Logistic Regression to detect Breast Cancer (Benign or Malignant) from numerical datasets.
The project is implemented in Google Colab and supports CSV dataset inputs as well as batch predictions from text files.

## *📌 Project Overview*

Demonstrates how Logistic Regression can classify breast cancer as Benign (0) or Malignant (1).

Trained on the Breast Cancer dataset with excellent accuracy.

Accepts manual single-row input or batch input from .txt files.

## *📊 Dataset*

Breast Cancer dataset (from scikit-learn or CSV).

Target variable:

0 = Benign

1 = Malignant

## *✨ Features*

✔ Logistic Regression model for classification

✔ CSV input support

✔ Text file batch prediction support

✔ Single-row user input prediction

✔ Training & testing accuracy reporting

## *🛠 Technologies Used*

✅ Python – Core Programming Language

✅ NumPy – Numerical Computation

✅ Pandas – Data Analysis & Cleaning

✅ Scikit-learn – Machine Learning Library

✅ Google Colab / Jupyter – Notebook Environment


## *📂 Project Structure*

Breast-Cancer-Detection-Logistic-Regression/

├── LOGISTIC_REGRESSION_TEXT_DATA_ML_MODEL.ipynb     # Main Colab notebook

├── dataset.csv                                      # Dataset file (optional)

├── requirements.txt                                 # Dependencies

└── README.md                                        # Project documentation

## *🔄 Workflow*

🔹 Step 1: Load Dataset

Import dataset either from a CSV file or use the sklearn built-in breast cancer dataset.

🔹 Step 2: Preprocess Data

Rename columns for consistency (e.g., diagnosis → label).

Check for missing values and handle them if necessary.

Explore dataset (shape, info, statistics).

🔹 Step 3: Split Dataset

Split into Training set (80%) and Testing set (20%) using train_test_split.

🔹 Step 4: Train Model

Initialize the Logistic Regression model.

Train the model using the training data.

🔹 Step 5: Evaluate Model

Predict on training set → calculate training accuracy.

Predict on testing set → calculate test accuracy.

🔹 Step 6: Make Predictions

Single Input Prediction: Provide one row of feature values → model predicts Benign / Malignant.

Batch Input Prediction: Upload a .txt file with multiple rows → model predicts for all rows.


## *📈 Results*

Training Accuracy: ~98%

Testing Accuracy: ~96%

## *🧪 Example Prediction*

13.54,14.36,87.46,566.3,0.09779,0.08129,0.06664,0.04781,
0.1885,0.05766,0.2699,0.7886,2.058,23.56,0.008462,0.0146,
0.02387,0.01315,0.0198,0.0023,15.11,19.26,99.7,711.2,
0.144,0.1773,0.239,0.1288,0.2977,0.07259
## *Output:*
The Breast Cancer is Benign


### *👨‍💻 Author*

Priyanshu Taria
📧 Email: 	priyanshutaria7327@gmail.com

🔗 LinkedIn: www.linkedin.com/in/er-priyanshu-taria-055774283





