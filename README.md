#SCOPUS Citation Finder

A Python 3 script which gathers citation data for New Zealand research repositories from http://www.scopus.com.

The script uses two Elsevier SCOPUS APIs: the [SCOPUS Search API](http://api.elsevier.com/documentation/SCOPUSSearchAPI.wadl) and the [Abstract Retrieval API](http://api.elsevier.com/documentation/AbstractRetrievalAPI.wadl). Firstly, it identifies articles in SCOPUS that have referenced a research repository article. It then examines these articles and pulls out the relevant citation data.

To run:

1. Clone or download the repository
2. Create an apikey at http://dev.elsevier.com/myapikey.html and add this to the config.py file
3. Add repository codes to the reposistory list in config.py (repository codes can be found in the New Zealand Repository Codes text file)
4. Navigate to the directory on command line
5. Run the get referenced articles script

The script writes the ids, urls, titles, and authors of the referencing and referenced articles to a tab-delimitered text file

Example data can be found here: [Scopus Results 16-07-2016](https://figshare.com/account/projects/14855/articles/3493484)




