# Text Analysis Report : Blackcoffer articles

### TASKS: 
  **1. Web-Scraping:** Extract textual data from the articles posted in _https://insights.blackcoffer.com/_
  
  **2. Text Analysis:** Utilizing Natural Language Processing to perform text analysis on the extracted data.
     
### RESOURCES:
  **1. Input.csv:** A sheet that stores links to all of the articles on the website.
  
  **2. Word Dictionary:** 

  **i. Stop Words:** Lists of common words belonging to different categories such as geography, names, months, etc.

  **ii. Master Dictionary:** Lists of Positive and Negative words.

### TEXT ANALYSIS OBJECTIVES:
  **1. Sentiment analysis:**  
  Identifying the text's tone by measuring positive/negative scores, polarity, and subjectivity scores.
  
  **2. Analysis of readability:**  
  Calculating Fog Index, average sentence length, count of complex words, count of sentences/words, etc. 

  _Check the [Objectives.txt](https://github.com/shrideep-tamboli/Text-Analysis/blob/main/Objectives.txt) file for more information about the variables and formulas_
  
### PROCEDURE:
**1. Setup:** Importing all the available resources such as URL for articles and Dictionary.

**2. Web-Scraping:** Using HTML Parsers to parse the texts in the articles and save each article as a .txt file.

**3. Data Cleaning:** Removing all the stop words from the saved .txt files present in the dictionary.

**4. Text Analysis:** Calculating all the required variables from the cleaned text files.

**5. Output:** Saving the calculations in a data frame with rows as articles and columns as scores. 

_(The attached [.ipynb](https://github.com/shrideep-tamboli/Text-Analysis/blob/main/Blackcoffer_Text_Analysis.ipynb) acts as a detailed notebook to walk through each step in details)_

### RESULTS: 
![image](https://github.com/shrideep-tamboli/Text-Analysis/assets/110283522/337c8b12-89b7-41f4-bcbb-8bc83bd4a89a)

_(Check the [Output.csv](https://github.com/shrideep-tamboli/Text-Analysis/blob/main/Output.csv) file to view the full output)_

