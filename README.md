# Resume_Classification_NLP

**Objective**:
The document classification solution should significantly reduce the manual human effort in the HRM. 
It should achieve a higher level of accuracy and automation with minimal human intervention.


![image](https://github.com/bhanudommeti/Resume_Classification_NLP/assets/140396048/e22ef8fa-e81f-466d-bfcf-f7e933ca7b7c)

We performed text extraction methods as follows to extract the clean text from all the resumes.

**Tokenization**: Splitting the text into individual text or tokens.

**Stopwords**: Removing the stopwords from the dataset (English).

**String** : After application of String, removing all the punctuations.

**Porter Stemmer** : Removing suffixes from the words in English.

**Lemmatization** : Breaking a word down to its root meaning to identify the similarities.

**Count Vectorizer** : Transforming a text into vector on the basis of the frequency of each word.

**Rows and Columns**: Dataset has 79 rows and 2 columns. Each row represent the unique resume entry.

***Model Building***
![image](https://github.com/bhanudommeti/Resume_Classification_NLP/assets/140396048/4db550bb-9553-4058-9ee0-8f75520b117e)


![image](https://github.com/bhanudommeti/Resume_Classification_NLP/assets/140396048/61889a67-5bd1-4e80-a0d8-086800474ec3)

Used **K-Fold and Stratified K-Fold** for model valuation
![image](https://github.com/bhanudommeti/Resume_Classification_NLP/assets/140396048/28279613-0994-4cfb-8938-9784c2792268)
