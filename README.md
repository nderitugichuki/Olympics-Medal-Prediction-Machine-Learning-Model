# Olympics Athlete Team Performance Prediction

This project aims to predict the number of medals won by athlete teams based on various factors, including the team's history, athlete demographics, and previous performances.

## Project Overview

The main objective of this project is to use a machine learning model to predict the number of medals a team will win in future events. The dataset used contains detailed information about athlete teams across various years, including the team's country, event participation, and previous performance in medals won.

## Dataset

The dataset used for training and evaluating the model is `teams.csv`, which contains the following features:
- **team**: Name of the team.
- **country**: Country the team represents.
- **year**: Year of participation.
- **events**: Number of events the team participated in.
- **athletes**: Number of athletes in the team.
- **age**: Average age of the athletes.
- **height**: Average height of the athletes.
- **weight**: Average weight of the athletes.
- **medals**: Number of medals won by the team.
- **prev_medals**: Number of medals won in previous events.
- **prev_3_medals**: Number of medals won in the last three events.

## Files in the Repository

- **`teams.csv`**: The dataset used for training and evaluation.
- **`olympic_medal_prediction.ipynb`**: A Jupyter notebook containing data exploration, feature engineering, model training, and evaluation.
- **`README.md`**: This file, which explains the project structure, dataset, and model details.

## Model and Performance

The machine learning model was trained to predict the number of medals won by teams based on their attributes. The model was evaluated using various metrics, such as:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R² Score**

## Requirements

To run the code in this repository, you need to have the following libraries installed:

- Python 3.x
- numpy
- pandas
- scikit-learn
- matplotlib

You can install the required libraries using the following command:

```bash
pip install -r requirements.txt
```

## How to Run the Code

1. Clone this repository:
    ```bash
    git clone https://github.com/nderitugichuki/your-repository-name.git
    ```

2. Navigate to the project directory:
    ```bash
    cd your-repository-name
    ```

3. Open the Jupyter notebook `medal_prediction.ipynb` to explore the code and run the model.

4. Alternatively, you can run the model by executing the Python script:
    ```bash
    python model.py
    ```

## Next Steps

To further improve the model, the following can be explored:
- Feature engineering to include additional factors that might influence team performance.
- Testing with more advanced machine learning algorithms.
- Fine-tuning hyperparameters to improve prediction accuracy.

## License

This project is licensed under the MIT License.

