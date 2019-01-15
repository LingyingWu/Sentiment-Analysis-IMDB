# Bag of Words Meets Bags of Popcorn

DeepLearningMovies 

[**Kaggle's competition**](https://www.kaggle.com/c/word2vec-nlp-tutorial) for using Google's word2vec package for sentiment analysis.  
Original Repository: https://github.com/wendykan/DeepLearningMovies  
  

Final project of **Perceptual Computing** from Waseda Univ.  
Deadline: 2019/01/15


## Results

- **Bag of Words** + **Logistic Regression**

max_features | 2500 | 3000 | 3500
:--- | :---: | :---: | :---:
unigram | 0.8678 | 0.8665 | 0.8654
bigram | 0.8694 | 0.8575 | 0.8689
trigram | 0.8693 | - | 0.8684
  

- **Word2Vec** + **CNN**

droupout | num_filters | kernel_size | epoch | score
:---: | :---: | :---: | :---: | :---:
0.2 | 64 | 2 | 6 | 0.8852
0.5 | 64 | 2 | 6 | 0.8888
0.8 | 64 | 2 | 6 | 0.8938
