# Task 31: Features and Target Selection

**Internship:** AI & ML Internship - Veda Technology  
**Tools:** Python, Pandas, Scikit-learn, Jupyter Notebook / Google Colab  
**Dataset:** Iris Dataset

## Objective
To understand the basic structure of a supervised machine-learning problem by selecting input features and a target variable.

## Dataset
This project uses the Iris dataset available through Scikit-learn. It contains 150 flower records, four measurement columns, and a species category. No external dataset download is required.

## Selected Features (X)
- `sepal length (cm)`
- `sepal width (cm)`
- `petal length (cm)`
- `petal width (cm)`

These measurements describe each flower and are used as model inputs.

## Selected Target (y)
- `species`

This is the flower category that a supervised machine-learning model would learn to predict.

## Reason for Selection
The four measurements provide information about each flower, while `species` is the output category to be predicted. Therefore, the measurements are stored in `X` and the species column is stored separately in `y`. The target is not included in the input features.

## Implementation
1. Load the Iris dataset using `load_iris()` from Scikit-learn.
2. Convert the measurements into a Pandas DataFrame.
3. Add species labels as the target column.
4. Select the four measurement columns as `X`.
5. Select `species` as `y`.
6. Validate that the target is not in `X` and both contain 150 rows.

## Expected Output
- Dataset shape: `(150, 5)`
- X shape: `(150, 4)`
- y shape: `(150,)`
- Target categories: `setosa`, `versicolor`, and `virginica`
- Validation: successful

## How to Run
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload `Task_31_Features_and_Target_Selection.ipynb` or copy its code into a cell.
3. Run the cell. Pandas and Scikit-learn are normally preinstalled in Colab.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Jupyter Notebook / Google Colab

## Learning Outcomes
- Understood features and target variables.
- Learned the difference between `X` and `y`.
- Practised selecting columns from a DataFrame.
- Understood why the target must be kept separate from input features.

## Interview Questions
**1. What is a feature?**  
A feature is an input variable used by a machine-learning model to make a prediction.

**2. What is a target variable?**  
A target variable is the output value that a supervised machine-learning model tries to predict.

**3. What is the difference between X and y?**  
`X` contains the input features, while `y` contains the target or output variable.

## Project Structure
```text
Features-and-Target-Selection/
├── Task_31_Features_and_Target_Selection.ipynb
└── README.md
```
