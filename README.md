# Text-mining-Ham-Spam-text-Classification
Classifying text messages as either spam or ham

This project is about building a binary classification algorithm that can accurately classify text messages as either spam or ham. 
the dataset used in this project is hosted on kaggle which includes 5572 text messages out of which 747 are spam and rest 4825 are ham. This also state that the dataset is imbalanced and the dependent variable is binary. theer are two columns in the data set one is the text messages and the other is the label(ham/spam). 
I have used nltk package for text mining in python. I have implemented nltk.corpus and nltk.tokenize to tokenize and remove punctuation from the text messages. Before performing any text mining tasks, first we need to divide the text messages into tokens and then remove the stop words and punctuations. I have used lemmitizer to understand the related words and group the words of same lemma. 
Model Building:
I have implemented logistic regression, Random forest classifier, Gradient boosting classifier, SGD classifier to accurately classify teh spam messages.
After analyzing the dataset with all the 4 algorithms, i found that the classification is more accurate with Gradient Boosting classifier, with accuracy of 97%. This algorithm classified all the spam messages as spam. 
I have implemented confusion matrix, classification report, accuracy measure to interpret the most accurate model. Apart from classifying the text messages as spam, i have also found the top 10 words used in messaging. 


