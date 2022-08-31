# DSTI ML Labs Project

Goodreads Books Kaggle's dataset evaluation, book's rating prediction.

## How to evaluate
Due to Bertrandt IT policy applied to my laptop, I was not allowed to use Anaconda and I have to access to Google Drive.
That's why I propose a specific process in order to run the current project:
1.   Clone the GitHub "main_branch" repository in your computer, or download the zip
2.   Add The repository to your Google Drive account in order to have the full folder arborescence in your Google Colab workspace
3.   Open a Google Colab session and browse to the repository
4.   Start to execute the notebook called "main.ipynb" in the repository

## Project Objectives:
Using the provided dataset, you are asked to train a model that predicts a book’s rating. The
project can be submitted as a Jupyter Notebook and should include exploratory analysis of
the data, feature engineering and selection, model training and evaluation.  
You may use additional resources from those that are suggested in the “Project Resources”
section or others as you see fit (provided you can justify how they can serve your solution).
You can even consult similar solutions from the Internet.   
However, this comes with a big
responsibility: any submission that is over-plagiarised or does not reflect personal work
will not be accepted.

## Project Evaluation:
The project will be evaluated using the following rubric. It contains the required items for a
complete submission as well as bonus elements. The grading system is over 5 and the final
grade will be transformed to a grade over 100.

● Data analysis (data processing, data cleaning, exploratory analysis, plots of relevant
attributes) [1 point]  
● Feature selection (feature engineering, feature pruning, choice justification) [1 point]  
● Model training (motivation for selected model, comparison of different models) [1
point]  
● Model evaluation (evaluation metric, results interpretation) [1 point]  
● Project report (short report explaining the approach and results) [1 point]  
● BONUS: Project reproducibility (requirements file with necessary packages, README
file for running the project) [1/2 point]  
● BONUS: Project hosting (Github, Docker, AWS, Heroku or any other method) [1/2
point]


## Directory Structure (inspired by CookieCutter)

├── LICENSE  
├── README.md          <- The top-level README for developers using this project.  
├── data  
│   ├── processed      <- The final, canonical data sets for modeling.  
│   └── raw            <- The original, immutable data dump.  
│  
├── models             <- Trained and serialized models, model predictions, or model summaries  
│  
├── notebooks          <- Jupyter notebooks  
│  
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.  
│   └── figures        <- Generated graphics and figures to be used in reporting  
│  
└── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.  
                          generated with `pip freeze > requirements.txt`  

## License
[MIT](https://choosealicense.com/licenses/mit/)