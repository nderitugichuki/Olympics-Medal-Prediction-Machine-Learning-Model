# Olympics-Medal-Prediction-Machine-Learning-Model
# Athlete Medals Prediction Model

This project builds a machine learning model to predict the number of medals athletes will win based on their past performance and other relevant features.

## Project Overview

The objective of this project is to use historical athlete data to build a predictive model that estimates the number of medals an athlete is expected to win. The dataset used for this project contains information about athletes, their performances, and their medals. By leveraging machine learning techniques, this model helps to forecast future medal achievements for athletes.

## Dataset

The dataset used in this project (`teams.csv`) contains the following features:
- **Team Name**: Name of the team or country.
- **Event**: The specific event the athlete/team participated in.
- **Year**: The year in which the event took place.
- **Athletes**: Names or count of athletes.
- **Medals**: The number of medals won by the athlete or team.

The dataset was pre-processed and used to train various machine learning models, with the goal of predicting future medal counts.

## Files in the Repository

- `teams.csv`: The dataset used for training the model.
- `model.py`: The Python script used for data preprocessing, model training, and evaluation.
- `prediction_results.ipynb`: A Jupyter notebook that contains the exploration of data, training, and testing of the predictive models.
- `README.md`: This file that explains the project.

## Model and Performance

The final model was evaluated using the following metrics:
- **Mean Absolute Error (MAE)**: A measure of the average error in the model's predictions.
- **Mean Squared Error (MSE)**: A measure of how large the squared differences are between actual and predicted values.
- **R² Score**: Indicates the proportion of the variance in the dependent variable that is predictable from the independent variables.

**Training Set**:
- MAE: [Value]
- MSE: [Value]
- R² Score: [Value]

**Test Set**:
- MAE: [Value]
- MSE: [Value]
- R² Score: [Value]

## Requirements

To run this project, you need the following libraries:
- Python 3.x
- numpy
- pandas
- scikit-learn
- matplotlib

Install the required libraries using:

```bash
pip install -r requirements.txt
```

## How to Run the Code

1. Clone the repository:
    ```bash
    git clone https://github.com/nderitugichuki/your-repository-name.git
    ```
   
2. Navigate to the project directory:
    ```bash
    cd your-repository-name
    ```

3. Run the model script:
    ```bash
    python model.py
    ```

Alternatively, you can run and explore the results using the Jupyter notebook provided.

## Next Steps

To improve the model further, future work can include:
- Adding more features to enhance the predictive power of the model.
- Trying out more advanced machine learning models or tuning the hyperparameters.
- Collecting more data to improve generalization.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
