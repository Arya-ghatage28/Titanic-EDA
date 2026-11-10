# Titanic Survival Analysis (EDA)

**InternCircle – Project 01**

## Project Overview
Exploratory Data Analysis (EDA) of the Titanic passenger dataset using Python and Pandas to understand the factors associated with passenger survival.

## Objective
To analyse passenger information and identify how gender, passenger class, and age were associated with survival rates.

## Research Questions
1. Did women survive more frequently than men?
2. Did passenger class affect survival?
3. Was age associated with survival?

## Dataset
- **Source:** Seaborn Titanic Dataset
- **Total Passengers:** 891
- **Features:** 15 columns
- **Target Variable:** Survived (0 = No, 1 = Yes)

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Cleaning and Analysis
- Loaded and inspected the dataset.
- Checked missing values and duplicate records.
- Filled missing age values using the median grouped by passenger class and sex.
- Filled missing embarked values using the mode.
- Dropped the deck column due to substantial missing data.
- Analysed survival rates using Pandas groupby.
- Created five visualizations to understand survival patterns.

## Key Findings

- **Overall Survival:** 38.4% of passengers survived.
- **Gender:** 74.2% of women survived compared to 18.9% of men.
- **Passenger Class:** Survival rates were 63.0% in Class 1, 47.3% in Class 2, and 24.2% in Class 3.
- **Age:** Children (0–12) had the highest survival rate at 58.0%, while seniors (61+) had the lowest at 22.7%.

## How to Run the Project

1. Clone or download this repository.
2. Create a virtual environment:

   `python -m venv venv`

3. Activate the environment (Windows):

   `venv\Scripts\activate`

4. Install dependencies:

   `pip install -r requirements.txt`

5. Open `Titanic_EDA.ipynb` in VS Code.
6. Select the Python kernel and click **Run All**.

## Project Structure

```text
Titanic_EDA/
│
├── Titanic_EDA.ipynb
├── requirements.txt
└── README.md
```

## Author
**Arya Ghatage**

## Project
InternCircle – Project 01