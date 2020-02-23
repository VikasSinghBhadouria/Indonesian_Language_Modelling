# Indonesian_Language_Modelling
Indonesian_Language_Modelling Repo for language model for the Indonesian language. Based on FastAI V1.40

Indonesian Language Modeling
A language Model with perplexity 44.94.Lower the perplexity , better the model.(perplexity=exp(valid_loss)).

The model has been trained in jupyter notebook using the fast.ai version of AWD LSTM Language Model --basically LSTM with dropouts--with data from Wikipedia. The dataset has been split to 90/10 train-validation with a vocabulary size of 60,000 and embeddings dimensions of 400.

The language model can also be used to extract text features for other downstream tasks such as text classification, speech recognition or machine translation.


The first such effort was by Cahya wirwan using fastai 0.7. The code was quite complicated & outdated given the fact that Fastai 1.0 is based on PyTorch. Also ,those weights ,encoder & weights are not getting load.

Above notebook gives a walkthrough in training a language model from scratch & using it for a downstream task like Text Classification.

For text classification: we achieved an accuracy of 95.08 % in multiclass text classification, which is better than other techniques as compared by Cahya earlier.

* Although perplexity is different from the referred version, the loss & Accuracy is almost the same.
*Training & Text data is taken from below mentioned repo.(Credits to Cahya)

#TO Do :
1. Pre-Processing to decrease the perplexity further (around 30).


#References:
https://github.com/cahya-wirawan/language-modeling/tree/master/indonesia
