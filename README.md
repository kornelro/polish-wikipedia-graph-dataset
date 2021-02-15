# polish-wikipedia-graph-dataset

The repository contains dataset of polish Wikipedia pages assigned to specific science fields and links between these articles. Dataset can be use as simple classification task in NLP, especially as benchmark for graph based methods.

### wiki_pages.csv
Articles information file. Columns:
- _title_ - article title,
- _text_ - article text,
- _category_ - one of 7 main Wikipiedia categories related with science fields that was the closest to article categories in scrapped categories tree. 

Articles categories:
- _Astronomia_ - astronomy,
- _Biologia_ - biology,
- _Matematyka_ - math,
- _Psychologia_ - psychology,
- _Fizyka_ - physics,
- _Informatyka_ - computer science,
- _Chemia_ - chemistry.

### annotations.csv
File with links between pages. First column is source article title and second column is target article title. Take a note that file includes links to pages that are not present in _wiki_pages.csv_.