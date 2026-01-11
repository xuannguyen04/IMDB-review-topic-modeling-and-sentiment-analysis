NLP Pipeline Analysis for Movie Reviews
==================================================

Author: Xuan Nguyen
File: Nguyen_Xuan_IMDBProject_BUAN6342.ipynb

--------------------------------------------------
SETUP INSTRUCTIONS
--------------------------------------------------
1. Ensure Python 3.11 or 3.12 is installed.
2. Install required libraries:
   pip install -r requirements.txt
3. Download NLTK data if not already installed:
   python -m nltk.downloader stopwords wordnet punkt

--------------------------------------------------
DATASET SOURCE
--------------------------------------------------
Kaggle IMDb Dataset of 50K Movie Reviews
Source: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews/data
Download the dataset CSV file and place it in the same directory as the notebook.

--------------------------------------------------
HOW TO RUN
--------------------------------------------------
1. Open the Jupyter notebook:
   jupyter notebook Nguyen_Xuan_IMDBProject_BUAN6342.ipynb
2. Run all cells in order (Kernel > Restart & Run All).

The notebook performs:
- Text preprocessing (tokenization, lemmatization, stopword removal)
- Sentiment analysis using Logistic Regression
- Topic modeling using LDA and NMF 
- Topic Visualization of LDA 
- Model evaluation and comparison

--------------------------------------------------
OUTPUTS
--------------------------------------------------
- Topic keywords displayed in the notebook in Part 3
- Interactive LDA topic visualization generated in the notebook (saved as screenshot in output folder if exported).
- Table summarizing LDA, NMF coherence score, and Logistic Regression results displayed in Part 5
- Comparison Table of PQI results displayed in Part 6

--------------------------------------------------
NOTES
--------------------------------------------------
- Some steps may require >2GB RAM.
- Run in a Python environment (e.g., Anaconda, venv) to avoid dependency conflicts.
- Ensure the dataset and notebook are in the same working directory.
