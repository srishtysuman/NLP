# NLP


This task is for sentence classification, where it takes document as input, find word vectors using pretrained Word2vec of Google news corpus. For words in your documents, corresponding to which there is no pretrained vectors, it will put NULL to them. I have not done fine tuning, if you want, you can extend that. 

In Average_word2vec, it find the average vectors of words of the text. In Average_chargram, it first find the n grams of a texts and then find the vectors crresponding to those ngrams using pretrained vectors.

In both the tasks above, there is minimal preprocessign done. I had tried it using some preprocessing too, but result was not that exciting, and I reasoned that lots of useful information was getting lost in that, so I removed that.

Word vectos are 300 dimensional. 

In the code, I have used both simple Logistic Regression, cross validation in Logistic Regression, and feed forward fully connected neural network with single hidden layer. 

I have tested the code on MR, CR, TREC, SST-1, SST-2, Subj and MPQA datasets. Metric used in the evaluation is the accuracy. 
