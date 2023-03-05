AIDS-NLP-Project -> ' Natural Language Processing ' at Jio Institute

Team Members:

1. Ahmed  : 23PGAI0120
2. Akash Deshwani: 23PGAI0035
3. Harshada Suresh Jadhav: 23PGAI0101
4. Rohan Mehta: 23PGAI0001

Dataset

Dataset file name used -> "gg2015.json"

Note -> To run the code, you have to download the json file from the following link and keep it in the same folder.
Link: https://drive.google.com/file/d/1FvFlK9gy4U5wyCEsgsTucGltoSph3sSw/view?usp=sharing

Requirements:

A project must do a reasonable job identifying each of these components.
1. Host(s) (for the entire ceremony)
2. Award Names
3. Award categories; Presenters
4. Nominees, Favorites, Winners mapped to awards*
5. Winners, mapped to awards*

Additional Goals:
1. Excerpts from Winners’ statements; reactions
2. Other honors, speeches
3. Unexpected events
4. Visuals (i.e., build a slide show)?

Approach

We have a dataset of 17,54,153 tweets relating to the Golden Globe Awards. 

We have used natural language processing techniques to parse tweets.
We have performed preprocessing on the dataset - removing opiniated tweets. 
We used BeautifulSoup to scrape the top 1000 actors and actresses fromt the imdb website. This is to cross check if the names that we extract truly exists.
We have used regex and built various functions to extract host names, award names, presenter names, nominee names, winner names, and display the output.

