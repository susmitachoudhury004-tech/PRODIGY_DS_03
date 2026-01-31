# Prodigy InfoTech Data Science Internship

Welcome to my repository for the Prodigy InfoTech Data Science Internship. This repository documents the tasks and projects I completed during the program.

## Project Overview: Task 3 - Bank Marketing Prediction
The goal of this project is to build a classification model to predict whether a customer will subscribe to a term deposit based on their demographic and behavioral data.

### Dataset
The dataset used is the **Bank Marketing Dataset** (`bank-additional.csv`), which contains 4,119 entries and 21 features, including:
- **Demographics:** Age, Job, Marital Status, Education.
- **Financials:** Default, Housing, Loan.
- **Campaign Info:** Contact type, Month, Day of week, Duration, Campaign frequency, etc.
- **Target Variable:** `deposit` (whether the client subscribed to a term deposit).

### Implementation Steps
1. **Data Loading & Exploration:** Initial inspection of data types, missing values (none found), and descriptive statistics.
2. **Feature Engineering:** Handling categorical variables and renaming columns for clarity.
3. **Data Visualization:**
   - Distribution of numerical features using histograms.
   - Analysis of customer demographics and their relationship with the target variable.
4. **Model Building:** Implementing a Decision Tree Classifier to predict customer behavior.
5. **Evaluation:** Visualizing the Decision Tree to understand the classification rules.

### Technologies Used
- **Python** (Pandas, NumPy)
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn (DecisionTreeClassifier)

## How to Run
1. Clone the repository.
2. Ensure you have Jupyter Notebook or Google Colab installed.
3. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn`
4. Run the `.ipynb` file to see the analysis and results.

## Author
**Susmita Choudhury**
*Data Science Intern at Prodigy InfoTech*
