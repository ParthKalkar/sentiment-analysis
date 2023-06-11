# Sentiment Analysis with Vader and Model Comparison

This Jupyter Notebook contains code for sentiment analysis using Vader sentiment analysis and comparing models such as Random Forest, SVM, and Logistic Regression.

## Overview

Sentiment analysis is a powerful technique used in natural language processing to determine the sentiment or emotional tone of a given text. In this notebook, we perform sentiment analysis on textual data using Vader sentiment analysis and compare the performance of different machine learning models.

The following steps are involved in the sentiment analysis process:

1. **Text Normalization:** Text normalization is the process of transforming text into a canonical (standard) form. It involves tasks such as removing punctuation, converting text to lowercase, and handling near-identical words.

2. **Tokenization:** Tokenization is the process of dividing a large quantity of text into smaller parts called tokens. It helps in finding patterns in the text and serves as the base step for stemming and lemmatization. Sentence tokenization is also performed to split the text into individual sentences.

3. **Removing Contractions:** Contractions like "isn't" or "shouldn't" are expanded to their full forms, such as "is not" or "should not". This step helps in standardizing the text and improving the accuracy of sentiment analysis.

4. **Lemmatization:** Lemmatization aims to return the base or dictionary form of a word by removing inflectional endings. It helps in reducing the word variations and improving the consistency of sentiment analysis results.

5. **Vader Sentiment Analysis:** Vader sentiment analysis is performed to determine if a given word or text is positive, negative, or neutral in nature. It utilizes a lexicon of sentiment-related words, where each word is rated for its polarity and intensity. Vader sentiment analysis provides a quick and effective way to analyze sentiment without the need for extensive training data.

6. **Model Comparison:** In this notebook, we compare the performance of different machine learning models for sentiment analysis. Specifically, we evaluate the Random Forest, Support Vector Machine (SVM), and Logistic Regression models. By comparing their accuracy, precision, recall, and F1-score, we can assess the effectiveness of each model in sentiment classification tasks.

## Usage

To run the code in this notebook, you need to have Jupyter Notebook installed. You can install it using `pip`:

```bash
pip install jupyter
```

1. Clone the repository and navigate to the project directory.

2. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Open the `Sentiment_Analysis.ipynb` notebook.

4. Run the notebook cells step-by-step to perform text normalization, tokenization, removing contractions, and lemmatization. Then, perform sentiment analysis using Vader sentiment analysis and compare the performance of different machine learning models.

5. Feel free to modify the code and experiment with different parameters or models to further improve the sentiment analysis results.

## Dependencies

This notebook requires the following dependencies:

- Python 
- Pandas 
- NLTK 
- Scikit-learn 
- VaderSentiment 

You can install the dependencies using `pip` or any package manager of your choice.

```bash
pip install pandas nltk scikit-learn vaderSentiment
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [NLTK](https://www.nltk.org/)
- [Scikit-learn](https://scikit-learn.org/)
- [VaderSentiment](https://github.com/cjhutto/vaderSentiment)



If you have any questions or suggestions, please feel free to contact us.

Happy sentiment analysis!
