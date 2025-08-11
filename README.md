# BREAST-CANCER-WISCONSIN-ANALYSIS
## Table of Contents
+ [Project Overview](#Project-Overview)
+ [Dataset Description](#Dataset-Description)
+ [Objectives](#Objectives)
+ [Tools Used](#Tools-Used)
+ [Analysis and Insight](#Analysis-and-Insight)
+ [Dataset Preview](#Dataset-Preview)
+ [SQL Queries](#sql-queries)
+ [Power Bi Dashboard](#Power-Bi-Dashboard)
+ [Findings](#Findings)
+ [Recommendation](#Recommendation)
---
## Project Overview
#### This Project analyses the Breast Cancer Wisconsin dataset which contains 569 patient records with 32 attributes, including an ID, a diagnosis label indicating whether a tumor is malignant (M) or benign (B), and 30 numerical features describing tumor characteristics such as radius, texture, perimeter, area, smoothness, compactness, concavity, symmetry, and fractal dimension—each measured as mean, standard error.
---

## Data Description
| Column Name               | Description                                                                |
| ----------------------------- | ------------------------------------------------------------------------------ |
| id                        | Unique identifier for each patient record                                      |
| diagnosis                 | Tumor diagnosis: **M** = Malignant (cancerous), **B** = Benign (non-cancerous) |
| radius\_mean              | Mean distance from center to points on the tumor perimeter                     |
| texture\_mean             | Standard deviation of gray-scale values (texture variation)                    |
| perimeter\_mean           | Mean size of the tumor perimeter                                               |
| area\_mean                | Mean area of the tumor                                                         |
| smoothness\_mean          | Mean smoothness of the tumor surface                                           |
| compactness\_mean         | Mean compactness (perimeter² / area − 1.0)                                     |
| concavity\_mean           | Mean severity of concave portions of the tumor contour                         |
| concave points\_mean      | Mean number of concave points on the tumor contour                             |
| symmetry\_mean            | Mean symmetry of the tumor shape                                               |
| fractal\_dimension\_mean  | Mean complexity of tumor boundary (fractal dimension)                          |
| radius\_se                | Standard error of radius measurements                                          |
| texture\_se               | Standard error of texture measurements                                         |
| perimeter\_se             | Standard error of perimeter measurements                                       |
| area\_se                  | Standard error of area measurements                                            |
| smoothness\_se           | Standard error of smoothness measurements                                      |
| compactness\_se           | Standard error of compactness measurements                                     |
| concavity\_se             | Standard error of concavity measurements                                       |
| concave points\_se        | Standard error of concave points measurements                                  |
| symmetry\_se              | Standard error of symmetry measurements                                        |
| fractal\_dimension\_se    | Standard error of fractal dimension measurements                               |
| radius\_worst             | Largest (worst) radius value for the tumor                                     |
| texture\_worst            | Largest (worst) texture value for the tumor                                    |
| perimeter\_worst          | Largest (worst) perimeter value for the tumor                                  |
| area\_worst               | Largest (worst) area value for the tumor                                       |
| smoothness\_worst         | Largest (worst) smoothness value for the tumor                                 |
| compactness\_worst        | Largest (worst) compactness value for the tumor                                |
| concavity\_worst          | Largest (worst) concavity value for the tumor                                  |
| concave points\_worst     | Largest (worst) number of concave points                                       |
| symmetry\_worst           | Largest (worst) symmetry value for the tumor                                   |
| fractal\_dimension\_worst | Largest (worst) fractal dimension value for the tumor                          |


---
## Objectives
+ To classify whether a tumor is benign or malignant based on cell nucleus features extracted from medical imaging.
---
## Tools Used
+ POWER BI
+ SQL
---
# Analysis and Insight 
## Dataset Preview
#### https://ibb.co/dwFcgH3m

##  SQL Queries
#### https://ibb.co/20wfwMGL
#### https://ibb.co/BHd1qn1B

##  Power Bi Dashboard
#### https://ibb.co/B528V675
#### https://ibb.co/1YZPD3FL
#### https://ibb.co/hx0kvmcj
---
# Findings
### 1.Benign cases make up roughly 62–64% of the data, while malignant cases account for 36–38%.
### 2.Tumor size–related features (e.g., radius_mean, perimeter_mean, area_mean) tend to have higher values for malignant tumors than benign ones.
### 3.Shape irregularity metrics (concavity_mean, concave points_mean, compactness_mean) are significantly greater in malignant cases.
### 4.Features such as worst radius, worst perimeter, worst area, and worst concave points show a clear distinction between benign and malignant tumors, making them highly predictive for classification.
### 5.Malignant tumors generally have larger dimensions and more irregular boundaries compared to benign tumors, suggesting that geometric and texture-based features are critical in diagnosis.

# Recommendation
### 1.Introduce additional bike accessory types to diversify product lines and increase customer value per order.
### 2.Focus marketing and retention strategies on Adults (35+), especially in Australia and Canada, as they generate the most revenue.
### 3.Consider discounts or entry-level products targeted at the <25 age group to grow their customer base and build early brand loyalty.
### 4.Explore new provinces or countries with similar profiles to Australia and Canada to scale up sales geographically.
### 5.Introduce tiered pricing or bundle deals for bulk orders to incentivize larger purchases while protecting margins.










.














