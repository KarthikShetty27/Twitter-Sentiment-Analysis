# Twitter Sentiment Analysis: Unveiling Public Discourse

## Introduction
In today's digital age, social media platforms have become central hubs for communication, information sharing, and opinion expression. Among these platforms, Twitter stands out as a prominent source of real-time data, offering a wealth of insights into public sentiment and discourse. In this case study, we embark on an exploration of sentiment analysis and word-level analysis using Twitter data.

Twitter's unique format, characterized by short messages or "tweets" limited to 280 characters, presents both challenges and opportunities for natural language processing (NLP) practitioners. Despite the brevity, Twitter users convey a wide range of emotions, opinions, and reactions, making it an intriguing dataset for linguistic analysis.

**Primary Objectives:**
- **Word-Level Analysis:** Delve into the linguistic patterns of Twitter data, examining how users construct messages, the prevalence of slang, abbreviations, and hashtags, and uncovering key terms and topics that emerge from the discourse.
- **Sentiment Analysis:** Conduct sentiment analysis to understand the underlying sentiment expressed in tweets. By classifying tweets as positive, negative, or neutral, gain insights into the prevailing attitudes and emotions within the Twitter community.

## Dataset Description
The sentiment140 dataset is a widely used dataset in natural language processing (NLP) and sentiment analysis tasks. It consists of 1,600,000 tweets collected using the Twitter API. These tweets are annotated with sentiment polarity, indicating whether the sentiment expressed in the tweet is negative, neutral, or positive.

**Fields:**
1. **Target (Polarity):** Represents the sentiment polarity of the tweet. Encoded with numeric values: 0 for negative sentiment, 2 for neutral sentiment, and 4 for positive sentiment.
2. **IDs:** Unique identifier assigned to each tweet.
3. **Date:** Timestamp indicating when the tweet was posted. Presented in a standardized format.
4. **User:** Twitter handle (username) of the user who posted the tweet.
5. **Text:** Actual text content of the tweet within the 280-character limit.

| Dataset Link | QR Code [Dataset Link] |
|--------------|---------------|
| [Dataset Link](https://www.kaggle.com/datasets/kazanova/sentiment140) | <img src="https://github.com/KarthikShetty27/Twitter-Sentiment-Analysis-NLP-Project/assets/91489581/53d18446-b196-4ee2-9b17-ca9c5392d5fb" width="200"> |

## Setting up a Virtual Environment (venv) with PowerShell Scripts
To manage project dependencies and ensure reproducibility, we'll use PowerShell scripts to start and end the virtual environment. Here's how to do it:

1. **Create a Project Directory:** Create a directory for your project. You can name it anything you like.

2. **Download PowerShell Scripts:** Download the provided PowerShell scripts for starting and ending the virtual environment and place them in the Scripts folder of your project directory.

3. **Open PowerShell:** Navigate to your project directory using PowerShell.

4. **Start Virtual Environment:** Run the start_venv.ps1 script to activate the virtual environment:
    ```
    .\Scripts\start_venv.ps1
    ```

5. **Install Required Packages:** Once the virtual environment is activated, you can install the required packages using pip:
    ```
    pip install numpy pandas matplotlib nltk wordcloud scikit-learn seaborn
    ```

6. **End Virtual Environment:** When you're done working on your project, run the end_venv.ps1 script to deactivate the virtual environment:
    ```
    .\Scripts\end_venv.ps1
    ```

> Note: The data file for the project is provided in a zipped format. You'll need to unzip it before using it in your analysis.

This project aims to explore and analyze Twitter data to gain insights into public sentiment and linguistic patterns. Through word-level analysis and sentiment analysis, we seek to uncover trends, attitudes, and prevailing opinions within the Twitter community.
