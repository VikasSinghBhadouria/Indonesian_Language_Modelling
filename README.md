# Indonesian_Language_Modelling
Indonesian_Language_Modelling Repo for  language model for  Indonesian language . Based on FastAI V1.40

Indonesian Language Modeling
A language Model with perplexity 44.94.Lower the perplexity , better the model.(perplexity=exp(valid_loss)).

The model has been trained in jupyter notebook using the fast.ai version of AWD LSTM Language Model --basically LSTM with droupouts--with data from Wikipedia. The dataset has been split to 90/10 train-validation with a vocabulary size of 60,000 and embeddings dimensions of 400.

The language model can also be used to extract text features for other downstream tasks such as text classification, speech recognition or machine translation.


The first such errfort was by Cahya wirwan using fastai 0.7. The code was quite complicated & outdated given the fact that Fastai 1.0 is based on pytorch. Also ,those weights ,encoder & weights are not getting load.

Above notebook give a walktrough in  trainig  a language model from scratch & using it for downstreak task like Text Classification.

For text classification : we achived accucracy of 95.08 % in multiclass text classification, which is better than other techniques as compared by Cahya earlier.

* Although perplexity is different from refered version , the loss & Accuracy is almost same.
#References:
https://github.com/cahya-wirawan/language-modeling/tree/master/indonesia

#TO Do :
1. Pre-Processing to decrease the perplexity further (around 30).
