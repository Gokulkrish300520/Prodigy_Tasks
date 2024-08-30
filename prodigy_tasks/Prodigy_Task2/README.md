# PRODIGY_DS_02
Perform data cleaning and exploratory data analysis (EDA) on a dataset of your choice, such as the Titanic dataset from Kaggle. Explore the relationships between variables and identify patterns and trends in the data.
Sure! Here is a sample README content for your Titanic data analysis project:

---

# Titanic Data Analysis

This project involves analyzing the Titanic dataset to gain insights into the factors affecting passenger survival. The dataset is preprocessed to handle missing values, and various visualizations are created to explore the relationships between different features and survival.

## Dataset

The dataset used in this project is the famous Titanic dataset, which provides information on the passengers of the Titanic, including whether they survived or not, their age, gender, class, and other attributes.The dataset used here also attached in this repository.

## Project Steps

1. **Data Loading**: Load the Titanic dataset from a CSV file.
2. **Data Overview**: Display basic statistics and information about the dataset.
3. **Data Cleaning**: Handle missing values in the dataset.
   - Drop rows with missing 'Embarked' values.
   - Fill missing 'Cabin' values with "Unknown".
   - Fill missing 'Age' values with the mean age.
4. **Data Visualization**: Create visualizations to explore the data.
   - Plot the distribution of passenger ages.
   - Plot the survival count by gender.
   - Create a scatter plot of age vs fare, colored by survival status.

## Files

- `titanic.csv`: The dataset file.
- `prodigy_DS_task2.ipynb`: The Python script containing the data analysis code.
- `README.md`: This README file.

## Usage

To run the analysis, execute the `Prodigy_DS_task2.ipynb` script. The script performs the following steps:

1. Imports necessary libraries.
2. Loads the Titanic dataset.
3. Displays basic statistics and information about the dataset.
4. Handles missing values in the dataset.
5. Plots the distribution of passenger ages.
6. Plots the survival count by gender.
7. Creates a scatter plot of age vs fare, colored by survival status.

## Requirements

- Python 3.x
- Pandas
- Matplotlib
- Seaborn

## License

This project is licensed under the MIT License.

## Acknowledgements

- The Titanic dataset is provided by [Kaggle](https://www.kaggle.com/c/titanic/data).
- This analysis is inspired by various public tutorials and examples on data analysis and visualization.
