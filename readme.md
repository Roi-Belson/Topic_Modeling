# Topic_Modeling

## Overview  
This repository explores topic modeling techniques to uncover latent themes from text corpora. Using methods like Latent Dirichlet Allocation (LDA), the aim is to extract meaningful topics from news articles and WhatsApp chat data.

## Contents  
- `Topic_Modeling_Articles.ipynb` – A Jupyter notebook for topic modeling on the articles dataset.  
- `Topic_Modeling_Whatsapp_Updated.ipynb` – A notebook for topic modeling on WhatsApp chat data.  
- `valurank_News_Articles_Categorization.csv` – CSV of news articles used for the “Articles” notebook.  
- `hebrew_stopwords.json` – A JSON file with Hebrew stopwords to clean and preprocess Hebrew-language texts.  
- `LDA_Model.pkl` – A serialized LDA model (pickle) created during the workflow.  
- `.gitattributes` – File for tracking large/binary files if needed.  
- `requirements.txt` – List of Python packages required for this project.

## Prerequisites  
- Python 3.7 or higher  
- Jupyter Notebook or JupyterLab  
- Required Python libraries installed (e.g., `numpy`, `pandas`, `scikit-learn`, `gensim`, `nltk`, `matplotlib`, etc.)

Install dependencies via:  
```bash
pip install -r requirements.txt
```