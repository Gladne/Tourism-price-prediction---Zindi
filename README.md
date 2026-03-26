# Tourism Price Prediction — Zindi Knowledge Challenge

## Project Overview
This project predicts tourism costs using machine learning based on traveler behavior, activities, and package details.

## Objective

Build a model to accurately predict total_cost.

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

## Key Steps
- Data cleaning and missing value handling
- Feature engineering (group_size, region, total_nights)
- Encoding (binary, one-hot, target encoding)
- Log transformation of target variable

---

## Models used and Results
| Model           | RMSE   | R²   |
|----------------|--------|------|
| **XGBoost**    | **4.05M**  | **0.41** |
| Random Forest  | 4.68M  | 0.26 |
| Decision Tree  | 5.91M  | -0.17 |

---

## Conclusion

XGBoost achieved the best performance, showing strong ability to capture complex patterns in tourism spending.

## How to Run
```bash
git clone https://github.com/Gladne/Tourism-price-prediction---Zindi.git
cd Tourism-price-prediction---Zindi
pip install -r requirements.txt
```
Run the notebook:

```Tourism_price_prediction.ipynb```
