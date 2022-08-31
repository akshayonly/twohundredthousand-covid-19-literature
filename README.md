# Exploratory-Data-Analysis By Data Minning ~200,000 Covid-19 PubMed Bibliographic and other MEDLINE metadata

## Objective
The goal of the project is to extract SARS-CoV-2 virus bibliographic and other metadata from PubMed. This metadata includes Abstracts, Article Title, Authors, Secondary Sources, Biological Compounds, etc. The extracted metadata is then pre-processed to transform into pandas dataframe. Seaborn and Matplotlib are used for primary visualization. Networkx is used to build and analyse MeSH terms network-graph. 

## Personal Note
The inspiration for this project came from the thought - How archeologists extract and analyze ancient artifacts and piece together the data. (Well I don't know what exact words or methods they use).

Instead of analyzing already available data in resources like [Kaggle](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge), I wanted to extract the data myself. As of 26th Feb 2022, there are around  232,253 SARS-CoV-2 virus literature results in PubMed. 

The goals of this project was to make the data extraction process simple. Importantly, the code used here should be able to fetch literature metadata of any query topic from PubMed.

So instead of analyzing a plethora of full-text literature data, here I have fetched, processed, and analyzed nearly ~200,000 PubMed (or MEDLINE) bibliographic and other metadata related to SARS-CoV-2 virus.

## Libraries
- Pandas 
- Matplotlib 
- Seaborn 
- Requests 
- URLlib 
- NLTK 
- Sklearn 
- Biopython

