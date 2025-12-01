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

## 4.) Exploratory Data Analysis (EDA)

Exploratory Data Analysis (EDA) is a critical step in understanding the structure, patterns, and underlying behaviour of the dataset before applying any modelling techniques. For this project, the EDA we performed helped us explore how student exam performance varies across Maths, Reading, and Writing, and how these outcomes relate to demographic characteristics such as gender, ethnicity, parental education, lunch type, and test preparation status.

The goal of this stage is to:

- Examine data distributions across all numerical features

- Identify potential outliers, anomalies, or inconsistencies

- Understand relationships between demographic variables and exam scores

- Assess correlations between subjects to evaluate predictive potential

- Establish whether demographic characteristics have meaningful influence on performance outcomes

Through descriptive statistics, visualisations, and correlation analysis, EDA provides essential insights that guide the modelling phase and validates whether demographic factors can contribute to accurate prediction of student performance.
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

<img width="1654" height="884" alt="image" src="https://github.com/user-attachments/assets/8f50e456-aeaf-4f0b-ae76-9c53d34ec5bd" />

<img width="1634" height="866" alt="image" src="https://github.com/user-attachments/assets/51f9ba75-62e0-45dc-8d17-b46e4f74a228" />

## 6.) Key Insights

<img width="1622" height="858" alt="image" src="https://github.com/user-attachments/assets/14aa4d38-c6cf-43b4-a007-7f25d9b550c6" />

<img width="1596" height="858" alt="image" src="https://github.com/user-attachments/assets/e0cd58b3-7f30-4215-92e4-76ce310b9a34" />

<img width="1464" height="752" alt="image" src="https://github.com/user-attachments/assets/74320c7c-2aa9-4f65-a324-13e0ebf2b00b" />

<img width="1494" height="814" alt="image" src="https://github.com/user-attachments/assets/bb246558-ca05-4eef-88d9-8108192963fa" />

<img width="1640" height="878" alt="image" src="https://github.com/user-attachments/assets/b7c045ee-14c1-4e5a-bdc6-2bef3d23f2e1" />

## 7.) Technologies Used

Python

Jupyter Notebook 

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
