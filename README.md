# Heart-disease
A Supervised Learning Experiment

This project explores a simple experiment in predicting heart failure using supervised learning, specifically regression techniques. While heart failure is a serious condition requiring early detection, this analysis is more of a playful dive into the data rather than a groundbreaking medical tool. Using available data, we aim to build a basic predictive model and gain insights into which factors might indicate a higher risk of heart failure.

## Data

The dataset used in this project is 'heart.csv' and is sourced from Kaggle:

Source: [https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)

## Project Structure

The project is structured as follows:

- **Introduction:** Provides an overview of the project and its goals.
- **Setup:** Lists the necessary libraries and dependencies.
- **Data Loading and Preprocessing:** Describes the steps taken to load, clean, and prepare the data for analysis. This includes handling missing values and encoding categorical variables.
- **Exploratory Data Analysis:** If enabled, generates an exploratory analysis report using Pandas Profiling.
- **Model Selection and Training:** Details the different supervised learning models considered and the training process.
- **Model Evaluation:** Presents the evaluation metrics used to assess the performance of the models, including recall, ROC AUC score, and F1 score.
- **Conclusion:** Summarizes the findings and insights gained from the analysis.

## How to Run

1. Clone the repository to your local machine.
2. Open the Jupyter notebook file (`heart_failure_prediction.ipynb`).
3. Ensure that you have all the necessary libraries installed (see Setup section).
4. Execute the notebook cells sequentially to perform the analysis.

## Customization

You can customize the analysis by modifying the toggle switches in the notebook:

- `YData_report`: Enables or disables Pandas Profiling for exploratory data analysis.
- `Feature_selection`: Enables or disables feature selection based on correlation results.
- `selected_model`: Selects which model to use for further analysis.

## Disclaimer

This project is for educational and experimental purposes only. The predictions made by the models should not be interpreted as medical advice. 
