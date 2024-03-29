# Twitter Sentiment Analysis: Indonesian Presidential Debate

This project showcases a sentiment analysis of tweets related to the 2024 Indonesian presidential debate. The sentiment analysis aims to provide insights into public opinions and attitudes towards the presidential candidates during the debate.

## Description
This project focuses on performing sentiment analysis on tweets related to the Indonesian Presidential Debate. The tweets are gathered using the [Tweet Harvest](https://github.com/helmisatria/tweet-harvest/) tool, which allows for the collection of Twitter data. The sentiment analysis is conducted using a pre-trained model available on the Hugging Face Model Hub, specifically the `ayameRushia/bert-base-indonesian-1.5G-sentiment-analysis-smsa` model.

The main objective is to analyze the sentiment expressed in tweets regarding the presidential and vice-presidential candidates in Indonesia. Three presidential candidates and three vice-presidential candidates are selected for analysis. The collected Twitter data is used to assess public sentiment towards each candidate during the debate periods.

The project provides insights into public opinion and sentiment trends surrounding the Indonesian Presidential Debate, leveraging natural language processing techniques and machine learning models to analyze large volumes of Twitter data.

## Usage
To replicate this analysis or use the provided codebase, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies listed in the `requirements.txt` file using `pip install -r requirements.txt`.
3. Run the provided Python scripts or notebooks to perform sentiment analysis on Twitter data related to the Indonesian Presidential Debate.

## Dataset
The dataset used for sentiment analysis consists of tweets collected from Twitter during the Indonesian Presidential Debate. Each tweet is associated with metadata such as timestamp (`created_at`), tweet ID (`id_str`), tweet content (`full_text`), quote count (`quote_count`), reply count (`reply_count`), retweet count (`retweet_count`), favorite count (`favorite_count`), language (`lang`), user ID (`user_id_str`), conversation ID (`conversation_id_str`), username (`username`), and tweet URL (`tweet_url`).

## License
This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).
