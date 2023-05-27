# Climate Hackathon

This repository contains code for a machine learning project. The project involves predicting a target condition based on a given dataset. The dataset is divided into a training dataset `Training Dataset.csv` and an evaluation dataset `Evaluation Dataset.csv`.

## Project Overview

The project follows the following steps:

1. Data preprocessing: The training dataset is loaded into a pandas DataFrame, and data exploration and preprocessing are performed. This includes handling missing values, exploring the distribution of numerical columns, and analyzing correlation with the target condition.
2. Model selection: Several regression models from scikit-learn library are evaluated for their performance on the training dataset. The models are evaluated based on the R2 score, which is a measure of how well the model fits the data.
3. Feature selection: Less significant columns are dropped from the dataset based on their correlation with the target condition.
4. Model training: The ExtraTreesRegressor model is selected based on its performance, and it is trained on the training dataset.
5. Prediction on evaluation dataset: The trained model is used to make predictions on the evaluation dataset (`Evaluation Dataset.csv`), and the predicted values are stored in a DataFrame.
6. Saving predictions: The predicted values along with their corresponding index values are saved to a CSV file (`predictions.csv`) for further analysis and submission.

## Dependencies

The following dependencies are required to run the code:

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Usage

1. Clone the repository to your local machine.
    ```bash
    git clone https://github.com/jaywyawhare/Climate-Hackathon.git
    ```
2. Install the required dependencies using pip or any other package manager.
    ```bash
    pip install -r requirements.txt
    ```
3. Place the Training Dataset.csv and Evaluation Dataset.csv files in the data directory of the repository.
4. Run the Jupyter Notebook to preprocess the data, train the model, make predictions, and save the predictions to a CSV file.
5. The predicted values will be saved to predictions.csv in the root directory of the repository.

## License
This project is licensed under the MIT License. You are free to use, modify, and distribute the code for personal or commercial purposes. Please refer to the LICENSE file for more details.

## Hackathon Details

- Hackathon Name: Hack For Climate Hackathon
- Link: [Hack For Climate Hackathon](https://unstop.com/hackathons/hack-for-climate-hackathon-swanirvahan-2023-institute-of-chemical-technology-ict-mumbai-indianoil-odisha-camp-663542)
- Kaggle Competition: [Hack For Climate Hackathon](https://www.kaggle.com/competitions/hack-for-climate-hackathon-bhuabaneswar-ict89534/overview)