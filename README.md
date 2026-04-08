# Financial Sentiment Analysis: Comparing TF-IDF and Sentence Embeddings

This repository contains the code for a sentiment classification study using the Financial PhraseBank dataset (Malo et al., 2014). Two models are compared: TF-IDF with Logistic Regression and Sentence Embeddings with Logistic Regression.

## Environment

Tested in Python 3 (Google Colab environment).

Key libraries used:
- scikit-learn
- sentence-transformers
- pandas
- numpy

No local installation is required. All libraries are pre-installed in Google Colab.

## Data

The dataset used is the Financial PhraseBank (Malo et al., 2014), available from:

https://www.researchgate.net/publication/251231364_FinancialPhraseBank-v10

Download the zip file, extract it, and locate `Sentences_75Agree.txt`.

## How to Reproduce

1. Open `financial_sentiment_analysis.ipynb` in Google Colab
2. Upload `Sentences_75Agree.txt` using the files panel on the left
3. Run all cells in order (Runtime → Run all)

**Note:** The dataset file must be uploaded manually in Co
