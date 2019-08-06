Testing the boundaries of unsupervised topic models. 

There are two notebooks in this repo. 

One notebook uses word count bag-of-word models and the other notebook uses word embeddings.

The data is the same in both notebooks. The idea is to see how traditional word count models behave versus traditional word embeddings. The other objective is to see how supervised algorithms perform versus unsupervised algorithms. The unsupervised topic models used are LDA and non-negative matrix factorization. I did not assess topics or terms during training but rather allowed the unsupervised models to proceed to a classification without any interruption. Supervised algorithms were trained with class labels as is normal and so they had more information to infer or predict the labels on the unseen test data. 

Results are in each notebook

 
