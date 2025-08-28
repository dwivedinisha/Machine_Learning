📊 First Machine Learning Model – Linear Regression (CGPA vs Package)
📌 Project Overview

This project demonstrates how to build a Simple Linear Regression model using Python, Pandas, Matplotlib, and Scikit-learn.
We use a placement dataset where:

Independent variable (X): CGPA (student’s grade point average)

Dependent variable (y): Package (salary in LPA)

The goal is to predict a student’s expected package based on their CGPA.

⚙️ Features Implemented

Load dataset (placement.csv) using pandas.

Display first 5 rows for quick inspection.

Plot a scatter plot between CGPA and Package.

Train a Linear Regression model with CGPA as input.

Derive the regression line equation (slope & intercept).

Plot the regression line over the scatter plot.

Compute R² score and Mean Squared Error (MSE) to evaluate fit.

Predict package for a student with CGPA = 8.5.

Plot the prediction point on the regression line.

🛠️ Tech Stack

Python 3.x

Libraries:

pandas → Data handling

matplotlib → Data visualization

scikit-learn → Linear regression & evaluation

numpy → Numerical operations

▶️ How to Run

Clone or download this repository.

Install dependencies (if not installed):

pip install pandas matplotlib scikit-learn numpy


Open the Jupyter Notebook:

jupyter notebook first_ml_model.ipynb


Run all cells sequentially.

📈 Example Output

Regression Equation:

Package = m * CGPA + c


(values of m and c will be shown after training)

Model Evaluation:

R² Score: measures how well CGPA explains Package.

MSE: measures average squared prediction error.

Prediction:
For CGPA = 8.5, the model predicts the expected Package.

Plots generated:

Scatter Plot (CGPA vs Package)

Regression Line with data points

Prediction point highlighted on regression line

📂 Dataset

File: placement.csv

Columns:

CGPA → Student’s academic score

Package → Placement package (in LPA)

🚀 Future Improvements

Split dataset into train/test sets for realistic evaluation.

Try multiple regression (include more features like aptitude, interview score).

Apply polynomial regression for non-linear relationships.

✍️ Author: Nisha Dwivedi
