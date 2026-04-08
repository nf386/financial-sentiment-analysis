Financial Sentiment Analysis: Comparing TF-IDF and Sentence Embeddings
This repository contains the code for a sentiment classification study using the Financial PhraseBank dataset (Malo et al., 2014). Two models are compared: TF-IDF with Logistic Regression and Sentence Embeddings with Logistic Regression.
Environment
Tested in Python 3 (Google Colab environment).
Key libraries used:

scikit-learn
sentence-transformers
pandas
numpy

No local installation is required. All libraries are pre-installed in Google Colab.
Data
The dataset used is the Financial PhraseBank (Malo et al., 2014), available from:
https://www.researchgate.net/publication/251231364_FinancialPhraseBank-v10
Download the zip file, extract it, and locate Sentences_75Agree.txt.
How to Reproduce

Open financial_sentiment_analysis.ipynb in Google Colab
Upload Sentences_75Agree.txt using the files panel on the left
Run all cells in order (Runtime → Run all)

Note: The dataset file must be uploaded manually in Colab before running the notebook.
Model
Sentence embeddings are generated using the all-MiniLM-L6-v2 model from sentence-transformers.
Results
TF-IDF + Logistic Regression: Macro F1 = 0.77
Sentence Embeddings + Logistic Regression: Macro F1 = 0.80
Sentence embeddings outperform TF-IDF, particularly in the negative class, indicating that semantic representations better capture domain-specific financial language.
Reference
Malo, P., Sinha, A., Korhonen, P., Wallenius, J., & Takala, P. (2014). Good debt or bad debt: Detecting semantic orientations in economic texts. Journal of the Association for Information Science and Technology, 65(4), 782–796.
