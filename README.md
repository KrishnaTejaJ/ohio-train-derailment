# Ohio Train Derailment Analysis

This repository contains a Python script for analyzing tweets related to the Ohio train derailment incident. The script performs various tasks including data cleaning, filtering, and analysis to gain insights from the Twitter data.

## Table of Contents

- [Introduction](#introduction)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Analysis](#analysis)
- [Results](#results)
- [Future Scope](#future-scope)

## Introduction

This script aims to analyze tweets pertaining to the Ohio train derailment incident. It automatically processes the data to extract relevant information and perform various analyses. The key tasks performed include:

- Data Cleaning: The script cleans the tweets by removing links, user mentions, and unnecessary characters.
- Keyword Filtering: Tweets containing specific keywords related to the incident are identified.
- Phrase Matching: Tweets are analyzed to match specific phrases related to the incident.

## Dependencies

Before running the script, ensure you have the following dependencies installed:

- [Pandas](https://pandas.pydata.org/)
- [NLTK](https://www.nltk.org/)
- [Plotly](https://plotly.com/python/)
- [WordCloud](https://github.com/amueller/word_cloud)

You can install these dependencies using `pip`:

```bash
pip install pandas nltk plotly wordcloud
```

## Usage

1. Clone the repository to your local machine:

```bash
git clone https://github.com/your_username/ohio-train-derailment-analysis.git
```

2. Navigate to the project directory:

```bash
cd ohio-train-derailment-analysis
```

3. Place the `train_derailment_area_tweets_18_days.xlsx` file in the project directory.

4. Execute the script:

```bash
python ohio_train_derailment.py
```

## Analysis

The script performs the following analyses:

- Filtering: Tweets containing specific keywords such as 'norfolk', 'derail', 'palestine', etc., are identified.
- Date-wise Trend: It visualizes the frequency of tweets over the specified days.
- City-wise Counts: Provides the count of tweets per city.
- User Analysis: Analyzes active accounts, providing details like name, tweet count, location, followers, following, and follower-following ratio.
- Quoted Tweets: Identifies quoted tweets and their frequency.

## Results

The results of the analysis are saved in the following files:

- `clean_tweets.csv`: Cleaned tweets for further analysis.
- `train_derailment_tweets.csv`: Filtered tweets related to the Ohio train derailment.

## Future Scope

The script could be extended for further analysis:

- Extracting more data sources to increase the dataset.
- Distinguishing between national and local coverage.
- Analyzing user bios and information spreading patterns.
- Incorporating other social media platforms.
- Implementing topic detection or classifiers.
- Identifying influential figures and their impact on information dissemination.

---

*Note: This script is provided as-is without any warranty. Use it at your own risk.*
