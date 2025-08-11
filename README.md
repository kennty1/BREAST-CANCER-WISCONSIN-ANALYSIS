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
#### https://ibb.co/MyHmdqLW

##  SQL Queries
#### https://ibb.co/Z6DLyTsY
#### https://ibb.co/207yw1f1
#### https://ibb.co/WvGmfc28
#### https://ibb.co/BHV9sMBB
#### https://ibb.co/9Hdg17sQ
#### https://ibb.co/gLm38c85
#### https://ibb.co/cc6KsrQF


##  Power Bi Dashboard
### https://ibb.co/PsGZwQgy
### https://ibb.co/6RNYqB0w
### https://ibb.co/tTy5kfwn

---
# Findings
### 1.Benign cases make up roughly 62–64% of the data, while malignant cases account for 36–38%.
### 2.Tumor size–related features (e.g., radius_mean, perimeter_mean, area_mean) tend to have higher values for malignant tumors than benign ones.
### 3.Shape irregularity metrics (concavity_mean, concave points_mean, compactness_mean) are significantly greater in malignant cases.
### 4.Features such as worst radius, worst perimeter, worst area, and worst concave points show a clear distinction between benign and malignant tumors, making them highly predictive for classification.
### 5.Malignant tumors generally have larger dimensions and more irregular boundaries compared to benign tumors, suggesting that geometric and texture-based features are critical in diagnosis.

# Recommendation
### 1.Encourage regular breast cancer screening, especially targeting groups at higher risk, since malignant tumors show distinct measurable differences in size, texture, and shape that can be detected early.

### 2.Educate the public about early symptoms and available diagnostic methods, emphasizing that benign tumors are more common but malignant cases need urgent attention.
### 3.Provide continuous training for medical professionals on interpreting tumor measurements and identifying malignancy patterns.











.














