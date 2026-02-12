# Tourism Price Prediction — Zindi Knowledge Challenge

## Project Overview
This project is based on a dataset containing 6,476 records of recent tourist expenditure information collected by the National Bureau of Statistics (NBS) 
in Tanzania. The primary purpose of the dataset is to provide insights into the current state of the tourism sector and support data-driven strategies for 
sustainable sector growth. The main objective of this study is to develop a predictive model capable of accurately estimating tourist expenditure during 
visits to Tanzania.
The dataset highlights distinct travel patterns across different age groups. Visitors aged 25–44, considered the most economically active group, predominantly
traveled for leisure and holidays (53.2%) and business purposes (18.5%). Individuals aged 45–64 were mainly engaged in holiday travel and visiting friends and
relatives. Younger visitors aged 18–24 mostly traveled for leisure and holidays (55.3%), with a notable portion participating in volunteering activities (13.7%). 
Senior visitors aged 65 and above were largely motivated by leisure and holidays (80.9%) and visiting friends and relatives (9.5%).
Data collection was conducted across seven major departure points, including Julius Nyerere International Airport, Kilimanjaro International Airport, 
Abeid Amani Karume International Airport, and the Namanga, Tunduma, Mtukula, and Manyovu border points, ensuring comprehensive coverage of international 
tourist movements.

---

## Dataset
The dataset was obtained from the **Zindi Tourism Knowledge Challenge** and contains:

- Demographic information
- Travel group composition
- Tourist experience factors
- Target variable: `total_cost`

Files included:

- `train.csv` — Training dataset
- `test.csv` — Test dataset
- `SampleSubmission.csv` — Submission format
- `VariableDefinitions` - Variable Descriptions

---

## Data Preprocessing
- Handling missing values using pipelines
- Encoding categorical variables
- Feature selection using correlation
- Removing duplicates (none found)

---

## Exploratory Data Analysis (EDA)
- Distribution analysis
- Feature importance exploration

---

## Model
Model tested:
- Random Forest

Evaluation metric:
- Mean Absolute Error (MAE)

---

## Results
Best model achieved:

MAE: *5138636.041684616*

---

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook
