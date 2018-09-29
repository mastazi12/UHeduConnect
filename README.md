# UHeduConnect
This is a full text search engine based off Sphinx engine. The initial idea was to create an integrated search engine where STEM students at University of Houston can collaborate and pick up on 'projects' to work together. Later on it was integrated into UHportal. It also provides real time comparision with IEEE database(though it never really IEEE data into a local machine but performs a API call related to the query) to recommend helpful publications related to the search query(The indexing is real time from a Local SQL database which is updated by a form UH portal). It uses the following technogoly/framework. 

Django Framework
Nginx web server
MySQL
Redis(for in-memory key-value storage)
