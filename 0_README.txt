This dataset is prepared for ENGL/DIHU407/ENGL521 and is for use in student projects only. 

//data pre-treatment 
In Walsh and Antoniak's article, the authors follow complex pre-treatment procedures recommended by David Mimno (Mimno article included in this file). For this data, however, cleaning and pre-treatment is very light. All datasets scrape the same number of book titles and reviews. 
1. I have restricted the data to three fields: review_id, book_id_title, text. 
2. I have removed carriage returns from the text field. 

Walsh and Antoniak install an instance of a Topic Modelling program called Mallet. For this class, however, we're using an in-browser Topic Modeller, jsLDA. You can find the in-browser program here: https://mimno.infosci.cornell.edu/jsLDA/. Both programs are developed by David Mimno and use an identical algorithm. However, there are some further restrictions in using the jsLDA in-browser version, and the light pre-treatment is intended to support use of jsLDA.

//stoplist.txt

This file is a list of stop words provided by David Mimno for jsLDA. You can edit it if you wish to add or delete stop words. 

//classic_book_reviews.tab.newLineStrip.csv

This data is scraped from Goodreads using the Python script created by Walsh and Antoniak and described in their article that we read for class. 


//historicalFiction_book_reviews.tab.newLineStrip.csv

This data is scraped from Goodreads using a script altered from the Python script created by Walsh and Antoniak. The data is scraped to include reviews for books with the folksonomic tag "historical-fiction" in Goodreads. The list of title ids is included in the "goodreads-scraper-master" directory but the edit to the script is not included. 


//memoir_book_reviews.tab.newLineStrip.csv

This data is scraped from Goodreads using a script altered from the Python script created by Walsh and Antoniak. The data is scraped to include reviews for books with the folksonomic tag "biography-memoir" in Goodreads. The list of title ids is included in the "goodreads-scraper-master" directory but the edit to the script is not included. 

//goodreads-scraper-master

This directory includes the Python web scraper developed by Walsh and Antoniak, purely for student interest. I have added additional title lists for the "historical-fiction" and "biography-memoir" datasets, but the script itself will scrape the original folksonomic tag set by Walsh and Antoniak. 