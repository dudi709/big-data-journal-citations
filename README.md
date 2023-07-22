# The Impact of Citations on Publishing Articles in Journals

For this project, we utilized the [OpenAlex](https://openalex.org/) and [arXiv datasets](https://www.kaggle.com/datasets/Cornell-University/arxiv).
The purpose of the project is to investigate the impact of publishing an article in a journal on the number of citations
received by the article. The [data_proccessing-big_data.ipynb](./data_proccessing-big_data.ipynb) file contains the data
collection and processing procedures. The [Results_and_Visualizations.ipynb](./Results_and_Visualizations.ipynb) file 
contains the analysis and visualizations of the results.
------------ Add here a link and explanation to the PDF of the mini-article we will write ------------.


### Our Final Data File

[Here](https://drive.google.com/file/d/1UneExPO0cTGpaTv4QiKDrn7zKHxrCzND/view?usp=sharing) you can download the final CSV file that we created after collecting and processing the data. 
Explanation of each column:
<br/>
> **article_id_openalex** represents the identifier of an article as represented in OpenAlex.
> 
> **date_citation_counts** represents the number of citations for the article on specific dates.
> 
> **first_publication_date** represents the initial publication date of the article based on the arXiv dataset.
> 
> **article_type represents** the publication venue of the article, if applicable (journal, NaN, book, etc.).
> 
> **journal_publication_date** represents the publication date of the article in the journal, if applicable, based on the categories column.
> 
> **categories** represents the category or categories to which the article belongs.



### Installation:
```
pip install pandas
pip install matplotlib
pip install requests
pip install gdown
pip install glob2
pip install tqdm
```