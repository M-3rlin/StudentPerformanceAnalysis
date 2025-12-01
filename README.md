# School Performance Predictor Analysis


##  Table of Contents:

1.)  Project Overview

2.)  Repository Structure

3.)  Data Cleaning & Preparation

4.)  Exploratory Data Analysis (EDA)

5.)  Visualisation

6.)  Key Insights

7.)  Technologies Used

8.)  How to Run the Project

9.)  Deliverables


## 1.)  Project Overview

This project is a data analysis initiative aimed at understanding whats predicts student educational performance.

Our goal is to move from observation to data-driven insight, which in turn will help relevant stakeholders focus their resources where they can have the maximum impact on student achievement.

### About This Dataset

Kaggle Dataset: https://www.kaggle.com/datasets/alizabrand/school-performance-analysis/data

This dataset contains information about students’ academic performance and related demographic factors. It includes scores in math, reading, and writing exams, along with background details such as gender, parental education, lunch type, and test preparation course.

## The Core Question

What is the best single predictor of a student's final educational performance across core subjects, including Maths, Reading, and English?

By answering this, we aim to establish a strong, measurable relationship between student attributes and academic outcomes.

## Project Scope & Deliverables

Our work is structured into the following phases to ensure a comprehensive analysis:

**1. Foundation** | Defining the business problem and reviewing the structure and quality of the raw data.


**2. Preparation** | Thorough cleaning, wrangling, and transforming the data to ensure it is suitable for analysis.


**3. Discovery** | Exploratory Data Analysis (EDA) to visualise relationships and patterns within the dataset.


**4. Modeling** | Developing analytical models (e.g., predictive models) to determine the strength of various factors in predicting performance.


**5. Reporting** | Interpreting the results to provide clear insights into the most influential predictors.


**6. Presentation** | Summarising our methodology, findings, and recommendations for stakeholders.

## 2.) Repository Structure

## 3.) Data Cleaning & Preparation

Key steps performed in the notebook 

School Performance Analysis Fin…

:

Loaded 1,000 student exam results from Kaggle (Math, Reading, Writing).

Reviewed categorical features:
gender, race/ethnicity, parental level of education, lunch type, test preparation course.

Verified no missing values.

Identified one extreme outlier (Math score = 0).
The team chose not to remove this outlier as it had minimal impact on median/quartile ranges.

Converted numerical exam results into banded categories:

0 = Low (≤60)

1 = Medium (61–75)

2 = High (≥76)

These bands were used for classification modelling and pattern comparison across subjects.

## 4.) Exploratory Data Analysis (EDA)

EDA included:

Score Distribution Analysis

All three subjects showed symmetrical, consistent distributions.

Very similar patterns made unified banding possible.

Correlation Analysis

Correlations between demographics and exam scores were weak (<0.5).

Correlations between exam subjects were strong:

Reading ↔ Writing: ≈0.95

Reading ↔ Maths: High

Writing ↔ Maths: High

Outlier Check

One maths score of 0 noted but retained.

Feature Exploration

Compared performance across demographic groups (gender, ethnicity, education level, lunch, test prep).

## 5.) Visualisation

## 6.) Key Insights

## 7.) Technologies Used

Python

Jupyter Notebook 

School Performance Analysis Fin…

Pandas, NumPy (data cleaning, transformations)

Matplotlib, Seaborn (visualisations)

Scikit-learn (modelling: Random Forest, classification, regression)

PowerPoint (presentation delivery)

Trello (project/task organisation)

Kaggle dataset (School Performance dataset)

## 8.) How to Run the Project

Requirements

Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn

Steps

Clone or download the repository.

Place the dataset in the /data folder (if not already included).

Open the Jupyter Notebook:

jupyter notebook StudentsPerformance.ipynb


Run each cell in order:

Data loading

Cleaning & preparation

EDA

Visualisations

Predictive modelling (classification + regression)

## 9.) Deliverables

✔️ 1. Jupyter Notebook — Full Analysis

Includes cleaning, EDA, modelling, plots, and conclusions.


School Performance Analysis Fin…

✔️ 2. Final Presentation Deck (PowerPoint)

Summarises methodology, visuals, findings, and recommendations.

✔️ 3. README (this file)

Full documentation describing the project structure and workflow.

✔️ 4. Optional (If added)

Exported plots

Model outputs

Enhanced dashboards

Additional analysis notebooks

## Team

| Name 
| :--- 
| [Abdul]   |
| [Ace]     |
| [Bhavita] | 
| [Igor]    |
| [Teresa]  |

---

## Getting Started

*This section will be updated with specific instructions for setting up the environment once we finalise what is needed for the deployment of the project.*
