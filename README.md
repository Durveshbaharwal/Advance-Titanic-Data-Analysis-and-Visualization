# Titanic Data Analysis & Visualization

This project provides an advanced analysis of the Titanic dataset, with a focus on exploratory data analysis (EDA), feature engineering, visualization, and machine learning. The analysis includes interactive visualizations and survival analysis, making use of Python libraries such as Pandas, Seaborn, Plotly, and Scikit-learn.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis and Visualizations](#analysis-and-visualizations)
  - [Feature Engineering](#feature-engineering)
  - [Correlation Heatmap](#correlation-heatmap)
  - [Principal Component Analysis (PCA)](#principal-component-analysis-pca)
  - [Random Forest Model](#random-forest-model)
  - [Interactive Visualizations](#interactive-visualizations)
  - [Survival Analysis](#survival-analysis)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project aims to provide insights into the survival of passengers on the Titanic by exploring various features of the dataset. We perform feature engineering, create visualizations, and build predictive models to understand the factors that influenced survival rates.

## Dataset
The dataset used for this analysis is the Titanic dataset available from the Seaborn library, which is a cleaned version of the original Titanic dataset from Kaggle.

## Features
The following features were used in the analysis:
- `pclass`: Passenger class (1st, 2nd, 3rd)
- `age`: Age of the passenger
- `sibsp`: Number of siblings/spouses aboard
- `parch`: Number of parents/children aboard
- `fare`: Ticket fare
- `fare_per_person`: Fare per person, calculated as `fare / (sibsp + parch + 1)`
- `is_alone`: Binary feature indicating if a passenger is traveling alone

## Installation
To run this project locally, you'll need to have Python installed along with the following libraries:
- Pandas
- Seaborn
- Matplotlib
- Plotly
- Scikit-learn
- Lifelines (for survival analysis)

You can install the required libraries using pip:

```bash
pip install pandas seaborn matplotlib plotly scikit-learn lifelines
```
## Usage
1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Run the Jupyter notebook or Python scripts to perform the analysis.

## Analysis and Visualizations
### Feature Engineering
We created additional features such as fare_per_person and is_alone to enhance the dataset and provide more insights.

### Correlation Heatmap
A correlation heatmap was generated to visualize the relationships between different numerical features and their influence on survival.
![image](https://github.com/user-attachments/assets/5dee250a-7e17-44b3-ac0e-93b76c5f3634)

### Principal Component Analysis (PCA)
PCA was applied to reduce the dimensionality of the dataset, allowing us to visualize the data in two principal components.
![image](https://github.com/user-attachments/assets/db719908-9468-4aff-a9c8-ae5da3dd79f2)

### Random Forest Model
A Random Forest classifier was built to predict the survival of passengers. The model's performance was evaluated, and feature importance was analyzed.
![image](https://github.com/user-attachments/assets/3c82a7a3-3143-46bf-84ef-98334ce2fe0d)

### Interactive Visualizations
Plotly was used to create interactive visualizations, such as scatter plots for PCA and feature importance charts.
![newplot](https://github.com/user-attachments/assets/169cc47a-07e6-4cc9-9306-7e96f65a81c0)

### Survival Analysis
Kaplan-Meier survival curves were used to estimate survival probabilities over time, considering factors like age.
![newplot (1)](https://github.com/user-attachments/assets/4959f464-7c4c-4153-83c7-50defd983272)

### Contributing
Contributions are welcome! If you have any improvements or suggestions, feel free to submit a pull request or open an issue.
