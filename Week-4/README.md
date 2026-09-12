# Week 4 — Big Mart Sales Prediction

## Overview

This project focuses on analyzing retail sales data and building machine learning models to predict **Big Mart sales** based on product and outlet characteristics.

The workflow includes exploratory data analysis, data preprocessing, feature preparation, model training, evaluation, comparison, and generation of sales predictions.

## Objectives

- Understand and analyze the Big Mart sales dataset.
- Perform exploratory data analysis on product and outlet attributes.
- Prepare data for machine learning.
- Train multiple regression models for sales prediction.
- Evaluate and compare model performance.
- Identify the best-performing model.
- Generate sales predictions for the test dataset.
- Extract useful business insights from the analysis.

## Dataset

The project uses the **Big Mart Sales** dataset containing product-level and outlet-level information.

### Dataset Files

- `train.csv` — training dataset containing historical sales information.
- `test.csv` — test dataset used for generating sales predictions.

### Dataset Summary

- **Training Records:** 8,523
- **Test Records:** 5,681
- **Input Features:** 11
- **Target Variable:** `Item_Outlet_Sales`
- **Problem Type:** Regression

## Analysis Performed

The project includes exploratory analysis of:

- Item type distribution
- Average sales by item type
- Outlet type distribution
- Average sales by outlet type
- Sales by location type
- Item MRP and sales relationship
- Item visibility and sales relationship
- Sales by outlet establishment year
- Fat content distribution and average sales
- Feature correlations

## Machine Learning Models

Three regression models were trained and evaluated:

1. **Linear Regression**
2. **Decision Tree Regressor**
3. **Random Forest Regressor**

## Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### Results

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 939.1751 | 1267.5513 | 0.4089 |
| Decision Tree | 739.3288 | 1065.9047 | 0.5820 |
| Random Forest | **723.5452** | **1035.8251** | **0.6052** |

## Best Model

The **Random Forest Regressor** achieved the best overall performance among the evaluated models.

- **MAE:** 723.5452
- **RMSE:** 1035.8251
- **R² Score:** 0.6052

## Business Insights

The analysis identified differences in sales performance across product and outlet characteristics.

Key observations from the project include:

- **Best Outlet Type:** Supermarket Type3
- **Best Item Type:** Starchy Foods
- **Best Location Type:** Tier 2
- **Best Fat Content:** Regular
- **Average Sales:** 2181.29

These findings describe patterns observed in the dataset and should be interpreted as associations rather than causal relationships.

## Prediction Output

The trained model was used to generate sales predictions for the test dataset.

- `bigmart_sales_predictions.csv` — generated sales predictions for the test records.
- **Prediction Records:** 5,681

## Project Report

`Thiranex_Task_4_BigMart_Sales_Prediction_Report.docx` contains the detailed analysis, visualizations, model comparison, results, and project findings.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

## Project Files

| File | Description |
|---|---|
| `train.csv` | Big Mart training dataset |
| `test.csv` | Big Mart test dataset |
| `bigmart_sales_predictions.csv` | Generated sales predictions |
| `Thiranex_Task_4_BigMart_Sales_Prediction.ipynb` | Complete analysis and machine learning notebook |
| `Thiranex_Task_4_BigMart_Sales_Prediction_Report.docx` | Detailed project report with analysis and visualizations |
| `README.md` | Project documentation |

## Project Structure

```text
Week-4/
├── README.md
├── Thiranex_Task_4_BigMart_Sales_Prediction.ipynb
├── Thiranex_Task_4_BigMart_Sales_Prediction_Report.docx
├── bigmart_sales_predictions.csv
├── train.csv
└── test.csv
```

## Key Learning

This project provided practical experience in **exploratory data analysis, data preprocessing, regression modeling, model evaluation, model comparison, prediction generation, and interpreting retail sales patterns**.

## Conclusion

The project successfully demonstrates a complete machine learning workflow for Big Mart sales prediction. Among the three evaluated models, **Random Forest Regressor** achieved the highest R² score and the lowest MAE and RMSE, making it the best-performing model in this project.

## Internship Task

**Thiranex Internship — Week 4**  
**Task:** Big Mart Sales Prediction

## Author

**Mohammed Aayan**  
B.Tech — Computer Science & Information Technology
