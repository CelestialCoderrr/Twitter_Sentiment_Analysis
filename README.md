
# Sentiment Analysis with NLTK

This project performs sentiment analysis on tweets using the NLTK library. It classifies tweets as either **Positive** or **Negative** using a Naive Bayes classifier trained on NLTK's built-in Twitter dataset.

## Features
- Uses **NLTK's twitter_samples** corpus for training.
- Preprocessing includes tokenization, lemmatization, and noise removal.
- Implements **Naive Bayes Classifier** for sentiment classification.
- Accepts custom tweets for sentiment prediction.

## Installation
### Prerequisites
Ensure you have Python installed (recommended: Python 3.7+). Install the necessary dependencies using:


pip install nltk

## How to Run the Project
### 1. Clone the Repository

git clone https://github.com/your-username/Sentiment-Analysis-NLTK.git
cd Sentiment-Analysis-NLTK


### 2. Run the Script

python src/sentiment_analysis.py


### 3. Test with a Custom Tweet
The script prompts for a tweet input and predicts whether it's positive or negative.

Enter a tweet: I love this!
Prediction: Positive




## Dependencies
- **NLTK** - Natural Language Toolkit for text processing
- **Python 3.x** - Required for running the script

## License
This project is licensed under the MIT License.

## Contributing
Feel free to fork the repository and submit pull requests with improvements!
