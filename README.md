# Decision Tree Classifier - Bank Marketing Dataset
  📌Task-03: 

##  Objective

The aim of this task is to build a **Decision Tree Classifier** that predicts whether a customer will subscribe to a term deposit based on their **demographic** and **behavioral** data. The model is trained and tested using the **Bank Marketing Dataset** provided by the UCI Machine Learning Repository.


##  Dataset Overview

- **Source**: [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- **Format**: CSV (`;` semicolon separated)
- **Target Column**: `y` (binary classification: 'yes' or 'no')

**Features include**:
- Personal attributes: age, job, marital status, education
- Financial history: default, housing loan, personal loan
- Contact and campaign data: contact type, duration, campaign count
- Economic indicators: employment variation rate, consumer price index, etc.


## Technologies Used

- Python 3
- Pandas
- Scikit-learn
- Matplotlib


##  Implementation Steps

1. **Data Loading**
   - Read the dataset using `pandas` from a local CSV file.

2. **Preprocessing**
   - Handled categorical variables using `LabelEncoder`.
   - Defined features (`X`) and target (`y`).

3. **Model Training**
   - Used `DecisionTreeClassifier` from `sklearn`.
   - Split data into training and test sets (80/20 split).

4. **Evaluation**
   - Evaluated performance using Accuracy and Classification Report.
   - Interpreted precision, recall, and F1-score metrics.

5. **Visualization**
   - Visualized the decision tree structure using `plot_tree()`.


##  Results

- Achieved an accuracy of approximately **88%**.
- The model performed well in classifying the majority class.
- Visualization helps in interpreting model decisions.


##  How to Run the Project

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/bank-marketing-decision-tree.git
   cd bank-marketing-decision-tree
