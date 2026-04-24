# linear-regression-advertising
A beginner-friendly machine learning project demonstrating Simple Linear Regression using TV advertising data to predict sales. Includes data analysis, visualization, model training, and evaluation using Python.
📊 Simple Linear Regression using Advertising Dataset

📌 Project Description

This project demonstrates Simple Linear Regression using Python and Scikit-learn to predict Sales based on TV advertising budget. It covers the complete machine learning workflow including data understanding, visualization, model training, and evaluation.

---

🚀 Objective

The main goal of this project is to:

- Analyze the relationship between TV advertising and sales
- Build a regression model to predict sales
- Evaluate the model's performance
- Visualize actual vs predicted values

---

🗂️ Dataset Information

- Dataset Name: "Advertising.csv"
- Features used:
  - TV → Independent Variable (Input)
  - Sales → Dependent Variable (Output)

---

🛠️ Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

🔍 Project Workflow

1. Data Understanding

- Loaded dataset using Pandas
- Checked dataset structure using ".info()"
- Viewed shape and summary statistics

2. Data Visualization

- Created scatter plot of TV vs Sales
- Observed a positive linear relationship

3. Data Preparation

- Defined:
  - "X = TV"
  - "y = Sales"
- Split data into training and testing sets (70% training, 30% testing)

4. Model Training

- Used "LinearRegression" from Scikit-learn
- Trained the model on training data

5. Model Evaluation

- Predicted values using test data
- Evaluated model using:
  - Mean Squared Error (MSE)
  - R² Score

---

📈 Regression Equation

Sales = 6.99 + 0.0465 × TV

Interpretation:

- Intercept (6.99): Base sales when TV advertising budget is zero
- Coefficient (0.0465): Sales increase by ~0.0465 units for every unit increase in TV budget
- R² Score (~0.59): Around 59% of variation in sales is explained by TV advertising

---

📊 Results

Metric| Value
Mean Squared Error (MSE)| ~7.98
R² Score| ~0.59

---

📉 Visualizations Included

- Scatter plot (TV vs Sales)
- Actual vs Predicted line plot
- Actual vs Predicted scatter plot

---

📁 Project Structure

simple-linear-regression-advertising/
│
├── Advertising.csv
├── linear_regression_advertising.ipynb
└── README.md

---

▶️ How to Run the Project

1. Clone the repository:
   git clone https://github.com/your-username/simple-linear-regression-advertising.git

2. Navigate to the project folder:
   cd simple-linear-regression-advertising

3. Install required libraries:
   pip install pandas numpy matplotlib seaborn scikit-learn

4. Run the Jupyter Notebook:
   jupyter notebook

---

🎯 Key Learnings

- Basics of Simple Linear Regression
- Data preprocessing and visualization
- Model training using Scikit-learn
- Evaluation using MSE and R² score

---

🚧 Future Improvements

- Extend to Multiple Linear Regression (add Radio & Newspaper features)
- Perform feature scaling
- Deploy model using Streamlit or Flask
- Improve accuracy with advanced techniques

---

📜 License

This project is open-source and available for learning purposes.

---

🙌 Acknowledgements

This project is inspired by beginner-friendly machine learning datasets commonly used for learning regression concepts.
