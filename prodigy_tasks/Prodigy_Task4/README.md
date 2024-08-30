# Prodigy_task_04

# Twitter Sentiment Analysis Project

## Project Structure

- `Prodigy_Task_04.ipynb`: The main Jupyter Notebook containing the code for the project.
- `twitter_training.csv`: The training dataset used for sentiment analysis.
- `twitter_validation.csv`: The validation dataset used for sentiment analysis.

## Requirements

To run the code, you need the following Python packages:
- pandas
- numpy
- matplotlib
- seaborn

You can install these packages using pip:
```bash
pip install pandas numpy matplotlib seaborn
```

## Data Description

### Training Data (`twitter_training.csv`)
This dataset contains tweets labeled with sentiment categories. Each row represents a tweet and includes the following columns:
- `id`: Unique identifier for the tweet.
- `tweet`: The text of the tweet.
- `sentiment`: The sentiment label for the tweet (e.g., Positive, Negative, Neutral).

### Validation Data (`twitter_validation.csv`)
This dataset is used to validate the model's performance. It has the same structure as the training data.

## Project Steps

1. **Load Data**: Load the training and validation datasets.
2. **Exploratory Data Analysis (EDA)**: Examine the data to understand its structure and identify any issues.
3. **Data Cleaning**: Check for missing values and duplicate rows, and handle them appropriately.
4. **Data Visualization**: Create visualizations to gain insights into the data distribution and sentiment categories.
5. **Modeling**: Apply machine learning models to classify tweets into different sentiment categories (not included in the current notebook but can be extended).

## Usage

To run the notebook, open it in Jupyter Notebook or Jupyter Lab and execute the cells step by step.

```bash
jupyter notebook Prodigy_Task_04.ipynb
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please contact [Gokul Krish] at [gokul.jayakumar2005@gmail.com].
