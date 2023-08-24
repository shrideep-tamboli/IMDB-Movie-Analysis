# Text Analysis of Blackcoffer's articles

### AIM: 
  **1. WEB-SCRAPING:** Extract textual data from the articles posted in https://insights.blackcoffer.com/
  
  **2. TEXT ANALYSIS:** Utilizing Natural Language Processing to perform text analysis on the extracted data.
     
### RESOURCES:
  **1. Input.xlsx:** A sheet that stores links to all of the articles on the website.
  
  **2. Word Dictionary:** 

  **i. Stop Words:** Lists of common words belonging to different categories such as geography, names, months, etc.

  **ii. Master Dictionary:** Lists of Positive and Negative words.

### TEXT ANALYSIS OBJECTIVES:
  **1. Sentiment analysis:**  
  Identifying the text's tone by measuring positive/negative scores, polarity, and subjectivity scores.
  
  **2. Analysis of readability:**  
  Calculating Fog Index, average sentence length, count of complex words, count of sentences/words, etc. 

### PROCEDURE:
**1. Import Data:** Load all the resources.

**2. Web-Scraping:** Using HTML Parsers to parse through the texts in all of the articles and save each article as a .txt file.

**3. Data Cleaning:** Removing all the stop words from the saved .txt files that are present in the dictionary.

**4. Text Analysis:** Calculating all the required variables from the cleaned text files.

**5. Output:** Saving the findings in the form of data tables with variables in columns and articles in rows. 

### RESULTS: Output of the Text Analysis is saved in OUTPUT.xlsx file.
