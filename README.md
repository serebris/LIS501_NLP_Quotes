# LIS501_NLP_Quotes
Measuring similarity in text, topic modeling using LDA, quote generation using LSTM 

Author: Sveta Bartholomew
Date: May, 2022

The dataset was retrieved from Kaggle.com and was originally sourced from PassItOn website. This qualitative dataset is a collection of inspirational quotes compilated from a variety of books, speeches, and quotes by famous individuals. The collection of inspirational quotes is described as a representation of quotes covering “a range of topics related to personal growth, motivation, and positivity”. Each quote is accompanied by an image URL to provide additional context and visual inspiration. 
The .csv file contains four columns, where the columns are: id number, category, quote, image-link, and quote-url. There are 1745 entries and multiple categories that include "courage", "justice”, “love”, “hope”, “mindfulness”, among others. The data in the file is nominal apart from id number that is represented as interval data type. 
I am interested to see how similar the category application in topic modeling is to the actual categories that exist withing the dataset.
I am interested in exploring:
-	Measuring similarity in text: most used stems using FreqDist from nltk.probability.
-	Visualization of categories and quotes. 
-	Method: topic modeling. Use Gensim to train LDA topic models; analyze topic change in a dataset of quotes.
-	Similarity
-	Visualization of similarity between the existing categories and categories created in topic modeling.
-	Quote generation using LSTM


Source: https://www.kaggle.com/datasets/mattimansha/inspirational-quotes?select=insparation.csv


