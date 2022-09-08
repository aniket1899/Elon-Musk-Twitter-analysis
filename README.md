# Elon-Musk-Twitter-analysis
### Topic modeling and sentiment/emotion analysis of Elon Musk's all time Tweets with an academic paper. LDA, Top2Vec, BERT.

Data collection:
> Tweets were scraped using the library: [SNScrape](https://github.com/JustAnotherArchivist/snscrape)


Topic modeling:
> Gensim (for topic modeling using LDA/ CoherenceModel for calculating model coherence), pyLDAvis (for visualizing topics), Top2Vec, Spacy, NLTK, Seaborn. 


For sentiment and emotion analysis of all Tweets:
> A RoBERTa model (by [Hugging Face](https://huggingface.co) for sentiment/emotion analysis: [pysentimiento](https://github.com/pysentimiento/pysentimiento), which is trained on a huge corpora of millions Tweets, was perfect for this task. 
