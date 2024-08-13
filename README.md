# Exploratory-Data-Analysis By Data Minning ~200,000 Covid-19 PubMed Bibliographic and other MEDLINE metadata

## Objective
The objective of this project is to extract bibliographic metadata related to the SARS-CoV-2 virus from PubMed. This metadata includes abstracts, article titles, authors, secondary sources, biological compounds, and other relevant fields. After extraction, the data is pre-processed and transformed into a pandas DataFrame for further analysis. Seaborn and Matplotlib are used for primary visualizations, while NetworkX is employed to build and analyze a network graph of MeSH (Medical Subject Headings) terms.

## Personal Note
The inspiration for this project stemmed from a parallel with the work of archaeologists who extract and analyze ancient artifacts to reconstruct historical data. Instead of relying on readily available datasets from resources like Kaggle, I wanted to undertake the data extraction process myself. As of February 26, 2022, there are approximately 232,253 literature records related to SARS-CoV-2 in PubMed.

The primary goal of this project is to simplify the data extraction process. Additionally, the code developed here is designed to be versatile, allowing for the retrieval of bibliographic metadata on any query topic from PubMed.

In summary, this project involves the extraction, processing, and analysis of nearly 200,000 PubMed (or MEDLINE) records related to the SARS-CoV-2 virus, providing valuable insights into the literature surrounding this topic.

## Libraries
- Pandas 
- Matplotlib 
- Seaborn 
- Requests 
- URLlib 
- NLTK 
- Sklearn 
- Biopython

