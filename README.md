

# Sentiment Analysis with Naive Bayes Classifier

This project demonstrates sentiment analysis using the Naive Bayes classifier for classifying tweets into positive or negative sentiments.

## Import Necessary Libraries

- `nltk`: Natural Language Toolkit used for text manipulation (tokenization, stemming, POS tagging, etc.).
- `re`: Regular expression module used for text preprocessing and removing unwanted words.
- `string`: Used for removing punctuation.
- `random`: To shuffle the data.

## Dependencies

Make sure to install the required dependencies by running the following command:

```bash
pip install nltk
```

After installing the NLTK library, download additional data using the following commands:

```python
import nltk
nltk.download('twitter_samples')
nltk.download('punkt')
nltk.download('wordnet')
nltk.download('averaged_perceptron_tagger')
nltk.download('stopwords')
```

## 1. Exploring Our Data

The project uses the Twitter Samples dataset, containing both positive and negative tweets.

## 2. Tokenization Process

Tokenization involves breaking down tweets into individual words. POS (Part of Speech) tagging is also applied.

## 3. Lemmatization Process

Lemmatization is performed on the tokens to reduce words to their base form.

## 4. Removing Noise (Stop Words & Unwanted Punctuation)

The project removes noise from the tokens by eliminating stop words and unwanted punctuation.

## 5. Shuffling The Dataset

To ensure a balanced distribution, the dataset is shuffled.

## 6. Training the Naive Bayes Classifier

The Naive Bayes classifier is trained on the preprocessed dataset.

## 7. Testing the Model

The trained model is tested with custom tweets to predict their sentiment.

## Usage

To use the project, follow these steps:

1. Install the required dependencies.
2. Download additional data.
3. Execute the provided code sections.

Feel free to experiment with your own tweets and explore the accuracy of the Naive Bayes classifier.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

