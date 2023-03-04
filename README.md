# Abstract-Classification
Every year, tens of thousands of papers on machine learning are published. This makes the academic literature about machine learning itself a source of big data - with all of the problems that this brings. Given the plethora of papers, it is useful to have tools to help a researcher identify which papers might be useful to read and which are not. 

Two features of papers which are commonly used to classify papers are abstracts and keywords, but both have their limitations. While academic papers usually have abstracts that summarize the paper, reading hundreds or thousands of abstracts is also often not an efficient use of time. Keywords can more efficiently classify papers, but relying on them suffers from at least two problems: first many papers and journals do not include keywords, and second, the author's or editor's choice of keywords may be inaccurate or overly general (e.g. "machine learning"). 

Using unsupervised learning to help classify papers, then, may help researchers and scientists to better sift through the big data of academic articles to more efficiently target their efforts and time.

In this notebook I use two different unsupervised techniques (BERTopic and Non-Negative Matrix Factorization) to classifying the abstracts of academic papers on machine learning (ML) and artificial intelligence (AI). The data consists of nearly 36,000 academic papers scraped from the arXiv dataset (https://www.kaggle.com/datasets/Cornell-University/arxiv?select=arxiv-metadata-oai-snapshot.json).
