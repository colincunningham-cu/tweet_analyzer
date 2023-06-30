# Tweet Analyzer

## Overview
This repository contains a Dash web application that analyzes Elon Musk's tweets from Jan 1 2022 to Dec 31 2022. The Tweet Analyzer was built using Jupyter Notebooks where the data was ingested, preprocessed, and visualized to extract key insights.

## Data Pipeline
Elon Musk's twitter activity was taken from Kaggle (https://www.kaggle.com/datasets/marta99/elon-musks-tweets-dataset-2022) and loaded into a Pandas DataFrame. From there, I performed basic cleaning / preprocessing steps so that the data could be analyzed. Lastly, I displayed the data visually uisng various Dash/Plotly components so that it can be digested easily by the end user. See source code for more information.

## Sample Output
Below is a screenshot that displays the sample output after the parameters in the sidebar are specified:

![alt text](https://github.com/colincunningham-cu/tweet_analyzer/blob/main/dash_result.png)

## Other Considerations
The purpose of this project was to build a POC to demonstrate potential avenues for analyzing raw text data. The following changes can be made to improve upon the work that has already been completed:
- Connect to Twitter API to allow users to enter any username to expand scope (must apply for developer access)
- Incorporate additional metadata to allow for more advanced queries
- Enhance visuals / layout to make application more aesthetic
