## Limitation of DB text search

- Lack of configurable, flexible text query tools and sophisticated ranking capabilities to find the best documents/records. DB lacks text normalization and processing, adding weights to term. DB lacks some of advanced search feature such as highlighting, faceting, spellchecking, stemming, stopword filtering etc... DB supports very simple wildcard based text search.

- Say we have text in database and we look for specific keyword in the text, then it will do a FULL table scan which will be slower as compared to Solr text search.

- There is no way to relevancy ranking with DB Full text search which Solr provides.