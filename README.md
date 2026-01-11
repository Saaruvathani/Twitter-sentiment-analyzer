# Twitter-sentiment-analyzer

## Project Overview 
This project performs sentiment analysis on Twitter data using a pre-trained Hugging Face Transformer model. It processes a dataset of 10,000 tweets stored in a CSV file, classifies each tweet as positive or negative, and visualizes the overall sentiment distribution using graphs.

The goal is to understand public opinion and emotional trends expressed on social media.

## Features 
- Reads and processes a large Twitter dataset (twitter_dataset.csv)
- Uses a Hugging Face sentiment analysis model
- Classifies tweets as Positive or Negative
- Stores predictions
- Displays a graphical visualization of sentiment distribution

## Technologies Used 
- Python
- Hugging Face Transformers
- Pandas
- Matplotlib
- NLTK

## Dataset
The dataset ``twitter_dataset.csv`` contains:
- 10,000 rows of tweets
- Each row contains a tweet text that is analyzed by the model

## Installation
- pip install transformers
- pip install pandas nltk seaborn matplotlib

## How to Run
- Open the notebook in Google Colab
- Upload twitter_dataset.csv
- Run all the cells from top to bottom
- The notebook will:
    Analyze 10,000 tweets
    Predict sentiment
    Display the sentiment graph
  
## Output
The output includes:
 - Sentiment label for each tweet
 - A visual graph showing how many tweets are positive vs negative
 -This makes it easy to understand overall public sentiment.

## Learning Outcomes

- Understanding NLP and sentiment analysis
- Hands-on experience with Hugging Face Transformers
- Working with large datasets
- Data visualization using Python

## Future Improvements

- Add Neutral sentiment category
- Support live Twitter API
- Analyze trends over time
- Improve visualization (pie charts, dashboards, etc.)

## License
This project is intended for educational and learning purposes.
