# arabic search engine
Arabic search engine using tfidf and cosine similarity

# dataset
the notebook is working on SANAD dataset
URL: https://www.kaggle.com/datasets/haithemhermessi/sanad-dataset
# preprocessing
Any numerical values are removed.
leading or trailling spaces are removed in case of multiple spaces between words.
stop words are removed
text is normalized using tashaphyne.normalize.normalize_searchtext

text vectorization is done using tfidf.
similarity is calculated by cosine similarity

a final code is written to retreive the document matching the search query or sub of the search query with similarity score sorted from highest match to lowest

if you are interested in english search engine visit https://github.com/Ahmed-Ismail-Mohamed/en-search-engine
