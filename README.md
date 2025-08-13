# Titanic Data Analysis

## 📌 Objective
The goal of this project is to clean and analyse the Titanic dataset to uncover patterns in passenger demographics, ticket classes, fares, and survival rates.

## 🗂 Dataset Description
The Titanic dataset contains details of passengers aboard the Titanic.  
**Key columns:**
- **PassengerId**: Unique ID for each passenger
- **Survived**: 0 = Did not survive, 1 = Survived
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Passenger name
- **Sex**: Gender
- **Age**: Age of the passenger
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Price of the ticket
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## 🛠 Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔍 Steps Performed
1. **Data Loading**: Imported the Titanic dataset into Pandas DataFrame.
2. **Data Cleaning**: Handled missing values, removed inconsistencies, and formatted columns.
3. **Exploratory Data Analysis (EDA)**: Performed descriptive statistics and visualisations.
4. **Visualisations**: Created count plots, histograms, bar charts, and correlation heatmap.
5. **Observations**: Noted key patterns and trends in the dataset.

## 📊 Key Insights
- Only about **38%** of passengers survived.
- **Females** had a much higher survival rate compared to males.
- **1st class** passengers had the highest survival rate; **3rd class** had the lowest.
- Most passengers were aged between **20–35 years**.
- Higher ticket fares were linked to better survival chances.
- Strong negative correlation between `Pclass` and `Fare`.

## 📂 Project Structure
```
titanic-data-analysis/
│
├── Titanic_Data_Analysis_Improved.ipynb   # Jupyter Notebook with code and analysis
├── titanic_cleaned.csv                    # Cleaned dataset
└── README.md                              # Project documentation
```

## 🚀 How to Run
1. **Clone this repository**  
```bash
git clone https://github.com/BHARTCHAUHAN/titanic-data-analysis.git
```
2. **Install required libraries**  
```bash
pip install pandas matplotlib seaborn
```
3. **Open the Jupyter Notebook**  
```bash
jupyter notebook Titanic_Data_Analysis_Improved.ipynb
```

## 📌 Author
**Bhart Chauhan**
