# Top-N-Words-In-Any-Novel

### Project Objective 
* Most Frequnt Words in a novel

### Technology Used 

* Natural Language Processing(NLP)
* Web Scraping
  
### Project Details 
* Scrape any novel Moby from the website Project Gutenberg (which contains a large corpus of books) using the Python requests package.
* Extract words from this web data using BeautifulSoup before analyzing the distribution of words using the Natural Language ToolKit (nltk) and Counter
* Visualizing Top-Ten Words using Wordcloud

### Resource Used -

- E-Book Page HTML Page Link


### Steps to perform

- Request the Novel's HTML file using requests and encoding it to utf-8.

- Extract HTML and create a BeautifulSoup object using an HTML parser to get the text

- Initialize a regex tokenizer to keep only alphanumeric text, assigning the results to tokens.

- Transform the tokens into lowercase, removing English stop words, saving results to words_no_stop.

- Initialize a Counter object and find the ten most common words, savign the results to top_ten and printing to see what they are

- Display the most common words using a Wordcloud

### Python Packages Required 

- requests
- bs4
- nltk
- collections
-  re
- matplotlib
- wordcloud

### Overview of Process 
- Requests and Encode the text
- Extracting the Text
- Create a Beautifulsoup object and get the text
- Tokenize the Text
- Convert words to lowercase
- Loading the Stop-Words
- Remove Stop Words from text
- Count Frequency Of Words
- Creating a Word Cloud



### 


### Credits 
- The Project Gutenberg





