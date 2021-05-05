# Parentents and children in russian drama
This is a repository for Bachelor thesis throughout the 2020/2021 academic year (Higher School of Economic, School of Linguistics). 

# About 
In this project, I conduct a contrastive analysis of parents and children' texts from Russian Drama Corpora ([its site](https://dracor.org/)). The first parent of work is the quantitative syntax, morphological, analysis and overal trends. The second part is machine learning tools for NLP: topic modeling and lexical complexity (as a plan). The third part is bulding few classificators based on features extracted on the previous steps and finding best of them. 

# Content
### Code
|**Content**|**Notebook**|**Comments**|
|:--:|:--:|:--:|
|Retrieving and downloading data|[get_data_from_RusDraCor.ipynb](https://github.com/Gratisfo/Parentents-and-children/blob/main/get_data_from_RusDraCor.ipynb)|save json for each play|
|Contrasitve analysis only Ostrovsky'plays and few classifiers|[сontrastive_analysis.ipynb](https://github.com/Gratisfo/Parentents-and-children/blob/main/сontrastive_analysis.ipynb)|there are all parents and childrens' replicas from plays, not only between them|
|Extraction replics only between parents and children|[between_parents_children.ipynb](https://github.com/Gratisfo/Parentents-and-children/blob/main/between_parents_children.ipynb)|also creating csv dataset|
|Topics of conversation| [topic_modeling.ipynb](https://github.com/Gratisfo/Parentents-and-children/blob/main/topic_modeling.ipynb)| for paretns and chidlren splitted by time period|
|Sentiment analysis pf perlics|[sentiment_analysis.ipynb](https://github.com/Gratisfo/Parentents-and-children/blob/main/sentiment_analysis.ipyn)| trying to provide unsupervised sentiment analysis |

### Dataset 
Parents and children characters' replicas (also date and title of plays) [data.csv](https://github.com/Gratisfo/Parentents-and-children/blob/main/data.csv)

### Slides
Final project of complingv course (March, 2021) [Contrastive analys drama text from RusDraCor](https://github.com/Gratisfo/Parentents-and-children/blob/main/%D0%9A%D0%BE%D0%BD%D1%82%D1%80%D0%B0%D1%81%D1%82%D0%B8%D0%B2%D0%BD%D1%8B%D0%B9%20%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D1%82%D0%B5%D0%BA%D1%81%D1%82%D0%BE%D0%B2%20RusDraCor.pdf)
