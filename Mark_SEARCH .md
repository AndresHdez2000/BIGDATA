
## SEARCH DATABASE

### Description

The primary aim of the search is to retrieve the most relevant matches to the user’s queries, excluding other general content from the website.
The system should be able to narrow down the search by using ranges (price, dates, sizes, etc.), sorting (by popularity, date, price) and filtering (including only desirable parameters). When we talk about web apps where information changes dynamically (prices, description details, availability of goods), it is extremely important to have near real-time updates; for example, in eCommerce or booking engines to show goods and services available in stock, engines can provide recommendations when looking up for the most interesting products or information, to improve the user experience.

|| SEARCH DATABASE|
|--|--|
| Benefits      | full-text search (by simple words and phrases or multiple forms of a word or phrase)<br>Multifield search<br>Highlighting (visual indicator of the searched words)<br>search by synonyms<br>Autocomplete suggestions<br>faceted search (opperations of counting)<br>fuzzy search(algorithms such as levestain algorithm, to detect typos or misspellings)<br>geospacial search(an object such as location according to its latitude an longitude)|
| ADVANTAGES    | 1. Near real-time<br>2. High scalability<br>3. Not only indexer but used as a database<br>4. Visualization of the Data<br>5. Machine Learning for anomaly detection and outlier detection <br>6. Fast search |
| DISADVANTAGES | * The configuration of the system is not very intuitive<br>*Many updates in the database might affect the retrival of results<br> It is needed to review the date converge, many problem matching for recen databases <br> |
| DB            | * [ELASTIC SEARCH](https://www.elastic.co/)  <br>* [SOLR](https://lucene.apache.org/solr/)  <br>* [SPLUNK](https://www.splunk.com/)   <br>* [SPHINX](http://sphinxsearch.com/) |

### References
 
 
[greenice](https://greenice.net/elasticsearch-vs-solr-vs-sphinx-best-open-source-search-platform-comparison/)
[mcmaster](https://fhs.mcmaster.ca/neru/documents/limitationsofsearchdatabases.pdf)


```python

```
