# Deep Learning for Political Sentiment Analysis Of Hinglish Comments

## Dataset:
The dataset is made from the youtube Hinglih comments on the top two Indian political parties (Bhartiya Janta Party and Indian National Congress). The dataset is divided into two files. One file contains comments related to BJP and another file contains comments releted to Congress. The experiment is performed on the mergerd comments from two files. Thanks to the author of the datset provided here:https://zenodo.org/record/3055456#.XScftOhKhPZ

## What is Hinglish?
Hinglish is a code mixed language of Hindi and English. In India some comments contain  English words in Hindi langusge. For example "Mera brother 5 months se work pe he." Which means "My brothe is working for 5 months." Here 'months','work','brother' are English words. The challengeis that there are no standard stopword, stemmer and lemmatizer libraries for Hinglish language and working with such mateforically rich language increases complexity on processing user based comments.    

## AIM:
This experiment is performed on the youtube political Hinglish comments on two top political parties BJP and Congress. The aim of the experiment is to study the effectiveness of deep learning techniques  in extracting political sentiments from these comments. In other words it is a two class classification problem to classify each comments either in favbour of BJP or CONGRESS.

## Employed algoriyhms
1.Multilayer perceptron

2.LSTM- long Short Term Memory

3.Convolutional Neural Network with LSTM

## Vectorization techniques
1.TF-IDF

2.Keras Tokenizer Text To Sequence  for word embedding

## Evaluation Matrix
1.Binary_cross_entropy for accuracy

2.Reciver Operating Curves (ROC)

## Conclusion:
Deep learning techniques performed well on extracting political tendency of commenters as it achieved more than 80% accuracy.

