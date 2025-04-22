# Semantic Book Recommender with LLMs

This project is a semantic book recommender system that leverages large language models (LLMs) to provide book recommendations based on user queries. The system is built using various components that handle data processing, semantic search, text classification, sentiment analysis, and a user interface.
## Overview
![image](https://github.com/user-attachments/assets/7343b2db-33f7-459f-8bdb-23d0d76321dc)

## Components

1. **Data Exploration**: Cleaning and preparing text data. (See `data-exploration.ipynb`)
2. **Semantic Search**: Building a vector database for finding similar books. (See `vector-search.ipynb`)
3. **Text Classification**: Classifying books as "fiction" or "non-fiction" using zero-shot classification. (See `text-classification.ipynb`)
4. **Sentiment Analysis**: Extracting emotions from text to sort books by tone. (See `sentiment-analysis.ipynb`)
5. **Web Application**: A Gradio-based interface for users to get book recommendations. (See `gradio-dashboard.py`)

## Setup Instructions

1. **Python Version**: This project requires Python 3.12 or higher.
2. **Dependencies**: Install the required packages using the provided `requirements.txt` file:
   ```bash
   pip install -r requirements.txt
   ```

4. **Data**: Download the necessary data from Kaggle as instructed in the project files.

## Usage

Run the Gradio dashboard to start the web application:
```bash
python gradio-dashboard.py
```
