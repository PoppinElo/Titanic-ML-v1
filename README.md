# Titanic - Machine Learning from Disaster

## Overview
This repository contains a comprehensive notebook for the Kaggle competition Titanic: Machine Learning from Disaster. The notebook includes steps to download the datasets, perform exploratory data analysis (EDA), build a machine learning model using RandomForestClassifier, and create a submission file for the competition.

- Name: Kevin Juan Román Rafaele
- LinkedIn: https://www.linkedin.com/in/kevin-juan-r-997530117/
- Email: mrredsky.2095@gmail.com


## Table of Contents
1. Overview
2. Dataset
3. Requirements
4. Installation
5. Usage
6. Project Structure
7. Visualization
8. Results
9. License

## Dataset
The Titanic dataset is a classic dataset used in data science and machine learning. It provides information about the passengers aboard the Titanic and whether they survived or not. The datasets used in this project can be found at the following URL:
- https://www.kaggle.com/competitions/titanic/data

## Requirements
The following Python libraries are required to run the notebook:
- requests
- pandas
- sqlite3
- matplotlib
- seaborn
- scikit-learn

## Installation
1. Clone the repository:
```
git clone https://github.com/yourusername/titanic-ml-from-disaster.git
```

2. Change the directory:

```

cd titanic-ml-from-disaster
```

3. You can install the necessary libraries using pip:
```
pip install requests pandas matplotlib seaborn scikit-learn
```


## Usage
1. Open the Jupyter Notebook:

```

jupyter notebook Titanic_ML_from_Disaster.ipynb
```

2. Run the notebook cells to:
   - Download and load the Titanic datasets
   - Perform exploratory data analysis (EDA)
   - Visualize some key data relations
   - Build a RandomForestClassifier model
   - Evaluate the model
   - Generate a submission file

3. Submit the generated submission.csv file to the Kaggle competition to get your score.

## Project Structure
```
titanic-ml-from-disaster/
│
├── Titanic_ML_from_Disaster.ipynb  # Main Jupyter Notebook
├── submission.csv                  # Generated submission file
├── README.md                       # Project README file
└── requirements.txt                # Python libraries required
```

## Visualization
- Age distribution & Survival rate by gender:
  ![Age distribution & Survival rate by gender](https://github.com/PoppinElo/Titanic-ML-v1/blob/main/images/age_and%20sex_dist.png)

- Feature importances:
  ![Feature importances](https://github.com/PoppinElo/Titanic-ML-v1/blob/main/images/feature_importance.png)

## Results
1. From the data visualization, it can be hypothesized the great importance of sex and age in determining life priority (the code of conduct "women and children first")
2. After running the notebook, a submission.csv file will be generated. This file contains the predictions for the test dataset, formatted for submission to the Kaggle competition. The file includes the following columns:
   - PassengerId: ID of the passenger
   - Survived: Prediction (1 for survived, 0 for deceased)
   - The score reached in the competition is around 0,64.

## License
This project is licensed under the MIT License.
