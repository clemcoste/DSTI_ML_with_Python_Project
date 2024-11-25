# DSTI ML Labs Project

## 📚 Project Overview

This project focuses on predicting book ratings using the Goodreads Books dataset from Kaggle. The goal is to apply machine learning techniques, including data exploration, feature engineering, model training, and evaluation, to achieve accurate predictions.

## 🚀 How to Run the Project

⚠️ Note: Due to Bertrandt’s IT policy, restrictions prevent the use of Anaconda and direct access to Google Drive from my laptop. The following steps outline a process to bypass these limitations:
1.	Clone the Repository  
	•	Clone the main_branch of this GitHub repository to your local computer, or download the zip file.
2.	Upload to Google Drive  
	•	Add the repository folder to your Google Drive account to make the file structure accessible in Google Colab.
3.	Open in Google Colab  
	•	Launch a Google Colab session.
	•	Navigate to the repository folder in Colab’s file browser.
4.	Run the Notebook  
	•	Execute the notebook main.ipynb to start the project.

## 🎯 Project Objectives

Using the dataset books.csv, the task is to:
	1.	Train a machine learning model to predict book ratings.
	2.	Conduct exploratory data analysis (EDA), feature engineering, and selection.
	3.	Build, train, and evaluate models using appropriate metrics.

## 📝 Project Evaluation Criteria

The project will be evaluated based on the following rubric (score: 5 points total):
1.	Data Analysis  
	•	Data cleaning, exploratory analysis, and visualizations of relevant attributes (1 point).
2.	Feature Selection  
	•	Feature engineering, pruning, and justification for the choices made (1 point).
3.	Model Training  
	•	Explanation for selected model(s), and comparison of performance across models (1 point).
4.	Model Evaluation  
	•	Evaluation metric, results interpretation, and discussion (1 point).
5.	Project Report  
	•	A concise report summarizing the approach, results, and key insights (1 point).

Bonus Points (up to 1 point):  
	•	Reproducibility: A complete requirements.txt and README (0.5 point).  
	•	Hosting: Hosting on platforms like GitHub, Docker, AWS, or Heroku (0.5 point).


## 📂 Directory Structure (inspired by CookieCutter)

The project structure follows the CookieCutter standard for reproducibility and organization:
```bash
├── LICENSE                   <- Project license.
├── README.md                 <- This README file.
├── data
│   ├── processed             <- Processed data ready for modeling.
│   └── raw                   <- Original, unmodified data files.
│
├── models                    <- Serialized models and predictions.
│
├── notebooks                 <- Jupyter notebooks for experimentation.
│
├── reports                   <- Generated analyses and reports.
│   └── figures               <- Graphics and figures for reporting.
│
└── requirements.txt          <- List of dependencies for reproducing the environment.
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
