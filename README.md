# Glassdoor-Review-Analysis

- raw zip file contains raw text reviews of employees from different companies scrapped from Glassdoor using python and Selenium.  

- Clean zip file : 

    Preprocessing raw text data: 
    1. Replace null values in reviews with empty strings
    2. Fix Contractions
    3. Remove Special Characters and numbers
    4. Convert all the letters into lower case
    5. Remove stop words using a list of customized stop words
    5. Tokenization using word ninja library
    6. Lemmatization using NLTK with POS tag

   After preprocessing the data saved in clean zip file. 

- Final_Text: Used text mining techniques - polarity, vectorization, and similarity to find characteristic of firms

- Tableau Dashboard : sentiment score of reviews and similarity score  
    - based in the sentiment and similarity score build dashboard : https://public.tableau.com/profile/sagar.surendra.kulkarni#!/vizhome/Text_Analytics_Updated/Dashboard1
