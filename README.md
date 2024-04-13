# March-Madness-2024
Using Machine Learning to predict games in the 2024 March Madness Tournament.

## Overview
This project applies a Random Forest machine learning model to predict game results for the 2024 March Madness tournament. The model is trained using histroical Mens NCAA March Madness tournament data from 2002 to 2024, all sourced directly from the KenPom website.

## Repository Structure
- **Data/**: Contains all scraped data sets stored in structured format.
- **Code/**: Includes all Jupyter notebooks and Python scripts used in the modeling process.
  - `ml_alog1.ipynb`: Jupyter notebook containing the Random Forest algorithm implementation.
  - `pred_data.csv`: CSV file with the data used for model predictions.

## Data Collection
Data was collected using a custom Python web scraper targeting historical statistics from [KenPom.com](https://kenpom.com/). The collected data spans from 2002 through 2024, focusing on metrics relevant to NCAA Men's basketball games.

### Data Columns:
- 

## Model Description
The Random Forest model was implemented in the Jupyter Notebook `ml_alog1.ipynb`. This model predicts the outcomes of the games using features derived from the historical data. Model performance and tuning details are documented within the notebook.

## Usage
To run the model:
1. Ensure you have Python installed along with the necessary libraries: pandas, numpy, sklearn, and matplotlib.
2. Navigate to the Code directory and open `ml_alog1.ipynb` in Jupyter Notebook or JupyterLab.
3. Run the cells in the notebook to train the model and make predictions using `pred_data.csv`.

## Contributing
Contributions to this project are welcome. Please fork the repository, make your changes, and submit a pull request for review.

### Last Updated: 04/13/2024
