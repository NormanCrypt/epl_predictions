# Making Predictions on Soccer Matches in the English Premier League using Machine Learning
Use machine learning models on a dataset to predict future winners of English Premier League soccer matches

Dataset for all matches was the result of web scraping of fbref.com as detailed in [thealexvu/epl_scraping](https://github.com/thealexvu/epl_scraping) repository.

The dataset is composed of English Premier League soccer matches from the current season (2022-23) to the first season (1992-93). The goal of this project is to extract data points of previous seasons (results, time of day, effects of recent form) to better predict who will win in future matches between two teams.

The notebook can be found at [./epl_predictions.ipynb](https://github.com/thealexvu/epl_predictions/blob/main/epl_predictions.ipynb)

This project is written in Python using Jupyter Labs.

Libraries used:
- `pandas`
- `requests`
- `BeautifulSoup`
- `sklearn`
  - `RandomForestClassifier`
  - `accuracy_score`
  - `precision_score`
  
TODO:
- All matches data set may be missing data for a range of years
- Precision of predictions is lower than desired, so more predictors will need to be uncovered to enhance the model
