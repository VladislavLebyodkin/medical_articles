# medical_articles

This project developed for medical scientists. The idea of the project - find similar articles using tf-idf as similarity metric. 

Case:
1. You have the greatest idea about something
2. You want to describe the idea, so first of all you need to check researches with the same topic

You need to write abstract of your idea and highlight keywords. Then just use this .ipynb file. 
As output you will see csv file with 20 similar abstracts.

Necessary:
1. Entrez account (to find similar articles I used Entrez database)
  https://www.ncbi.nlm.nih.gov/
  
2. Install biopython for API access, requests, request handle etc. Example for Anaconda:
  conda install -c anaconda biopython

Will be finalized:
1. Links to similar articles as output
2. More information about articles (authors, source etc)
