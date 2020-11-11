# NLP


This task is for sentence classification, where it takes document as input, find word vectors using pretrained Word2vec of Google news corpus. For words in your documents, corresponding to which there is no pretrained vectors, it will put NULL to them. I have not done fine tuning, if you want, you can extend that. 

Word vectos are 300 dimensional. 

In the code, I have used both simple Logistic Regression, cross validation in Logistic Regression, and feed forward fully connected neural network with single hidden layer. 

Datasets on which the code has been tested is there in the dataset folder.
