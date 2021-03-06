# Exploratory-Data-Analysis By Data Minning ~200,000 Covid-19 PubMed Bibliographic and other MEDLINE metadata

## Objective
The goal of the project is to extract SARS CoV-2 bibliographic and other metadata from PubMed. This metadata includes Abstracts, Article Title, Authors, Secondary Sources, Biological Compounds, etc. The extracted metadata is then pre-processed to transform into pandas dataframe. Seaborn and Matplotlib are used for primary visualization. Networkx is used to build and analyse MeSH terms network-graph. 

## Personal Note
The inspiration for this project came from the thought - How archeologists extract and analyze ancient artifacts and piece together the data. (Well I don't know what exact words or methods they use).

Instead of analyzing already available data in resources like [Kaggle](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge), I wanted to extract the data myself. As of 26th Feb 2022, Now there are around  232,253 literature results in PubMed. Even if one-fourth of full-text articles are extracted, they still would be in large size. 

But one of the goals of this project was to make the data extraction process simple. Importantly, the custom code used here should be able to fetch any query topic from PubMed (and so does it can).

So instead of analyzing a plethora of full-text literature data, here I have fetched, processed, and analyzed nearly ~200,000 PubMed (or MEDLINE) bibliographic and other metadata.

## Libraries
- Pandas 
- Matplotlib 
- Seaborn 
- Requests 
- URLlib 
- NLTK 
- Sklearn 
- Biopython

