# Sentiment-Analysis-using-VADER-and-Roberta-transformers-model
This is a tutorial on Sentiment Analysis for Amazon Reviews using two approaches, VADER (Valence Aware Dictionary sEntiment Reasoner - A Bag of Words approach) and Roberta Transformers pretrained model from HuggingFace. This tutorial deals with the NLP basics from the NLTK python module. We compute the sentiment scores for both
the approaches and then compare the two. VADER is a Bag of Words approach where VADER takes in all the words of a sentence and each word has a value of Positive, Negative or Neutral and adds or combines up the value for all the words and tells how positive or negative or neutral the sentence is by using the SentenceIntensityAnalyzer, but it does not take into account the relationship between words which actually exists in normal human speech. Whereas the Roberta Transformers model is pretrained using 58M twitter-reviews/tweets and is
used to compute the Sentiment scores. Plots of both the computations are displayed to get a clear picture of the performance by using python modules such as Matplotlib
and Seaborn. At the end, also an easy and quicker way to compute the sentiment scores is shown using the Huggingface transformers pipeline. 


