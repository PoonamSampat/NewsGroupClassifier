# NewsGroupClassifier
News Group Classificifier using Multinomial Naive Bayes

Used the open source News Group DataSet.

Tried with Naive Bayes to check accuracy, since I have around 30 classes used the Mutlinomial Naive Bayes.

Steps Involved:

    Processed the corpus, cleaning using spaces, quotes , numeric strings.
  
    Lemmatized the text.
  
    Removed Stop Words.
    
    Tokensized the sentences.
    
    Sorted the words based on their frequencies.
    
    Used the top 5000 words based on frequency.
    
    Used Scikit Learn's , Multiomial Naive Bayes to perform the classification.
    
    Got a decent accuracy of 84%.
    
    Published the recall, precision for each category
