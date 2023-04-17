# garanti-bbva-datathon
This project aims to predict whether people changed jobs in 2019 using the Tech-Talent dataset. The dataset contains information on job seekers and their employment status in 2019, along with other variables such as education, experience, and skills.
Predicting Job Change using Tech-Talent Dataset

# Introduction
This project aims to predict whether people changed jobs in 2019 using the Tech-Talent dataset. The dataset contains information on job seekers and their employment status in 2019, along with other variables such as education, experience, and skills.

The problem is framed as a churn prediction task, where i try to identify job seekers who are likely to leave their current job and switch to a new one. The goal is to build a machine learning model that can accurately predict job change based on the available features.

# Dataset
The Tech-Talent dataset is provided by Garanti BBVA Company and contains 3 diffrent dataset (skills.csv, language.csv, work_exp.csv) (user_id 	industry	location	moved_after_2019	school_name	degree	fields_of_study	start_year_month	end_year_month	skill	company_id	language ) rows Skills.csv is not included. The data is split into a training set and a test set, with 80:20 ratio of the data in the test set. SMOTE Method is used for balancing datasets.

# Methodology
Follow the following steps to build the machine learning model:

# Data preparation: 
Clean the dataset and perform feature engineering to create new variables that might be useful for predicting job change.

# Exploratory data analysis
 Perform exploratory data analysis to gain insights into the dataset and identify any patterns or trends that might be useful for prediction.

# Model selection I try out different machine learning models and select the best one based on their performance on the validation set.
RandomForestClassifier, DecisionTreeClassifier, CatBoostClassifier, Logistic reggresion, LGBMClassifier. 
Model evaluation: I evaluate the selected model on the test set and report its performance metrics, such as accuracy, precision, recall, and F1 score.
Results
Our best performing model is a CatBoostClassifier with a Scores mean: 0.7134, Scores std: 0.0196 performance metric of  0    9953, 1    3302 value. I also identify some areas for improvement, such as [insert potential areas for improvement].

# Conclusion
In conclusion, successfully built a machine learning model to predict job change using the Tech-Talent dataset. Our results show that %80 accuracy. This project has potential limitations for diffrent datasets.

# Repository Structure
The repository has the following structure:

data/: folder containing the dataset
notebooks/: folder containing the Jupyter notebooks used for data preparation, exploratory data analysis, and model selection
src/: folder containing the Python scripts used for data preparation and model training
README.md: this file

# Installation
To run the code in this repository, you need to install the following dependencies:

Python 3.x
[insert dependencies]

# Usage
To run the code in this repository, follow these steps:

Clone the repository: git clone [insert repository URL]
Install the dependencies: pip install -r requirements.txt
Run the Jupyter notebooks in the notebooks/ folder or run the Python scripts in the src/ folder.
License
This project is licensed under the [insert license].

# Acknowledgements
I would like to thank Garanti BBVA Company for providing the Tech-Talent dataset used in this project.





