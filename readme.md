# Topic_Modeling


## Overview  
This repository explores topic modeling techniques to uncover latent themes from text corpora. Using the following unsupervised learning algorithms: Latent Dirichlet Allocation (LDA), Non-Negative Matrix Factorization (NMF) I extract meaningful topics from a news articles corpus and a WhatsApp group-chat containing more than three years of text in Hebrew.


## Contents  
- `Topic_Modeling_Articles.ipynb` – A Jupyter notebook for topic modeling on the articles dataset using both.  
- `Topic_Modeling_Whatsapp_Updated.ipynb` – A notebook for topic modeling on WhatsApp chat data using NMF.  
- `valurank_News_Articles_Categorization.csv` – CSV of news articles used for the Articles notebook.  
- `Terr_Chat_2.txt ` - Over Three years of (censored) group chat in hebrew.
    - All full names and personal details have been removed.
    - The remaining content is intended for educational and analytical purposes, and all messages should be considered in a humorous or lighthearted context.
- Please do not use or share this chat for any other purposes.
- `hebrew_stopwords.json` – A JSON file with Hebrew stopwords to clean and preprocess Hebrew-language texts for the Whatsapp project. This file was created by me and additionally contains common words that I wanted to disregard in preprocessing.  
- `LDA_Model.pkl` – A serialized LDA model (pickle) created during the workflow for the Articles topic modeling.  




## Prerequisites  
- Python 3.7 or higher  
- Jupyter Notebook or JupyterLab  
- Required Python libraries installed (e.g., `numpy`, `pandas`, `scikit-learn`, `gensim`, `nltk`, `matplotlib`, etc.)


### Installation
1. Clone this repository:
```bash
   git clone https://github.com/Roi-Belson/Topic_Modeling.git
   cd Topic_Modeling
  ```


2. Install dependencies (you can create a virtual environment first if desired):  
   ```bash
   pip install -r requirements.txt
   ```








