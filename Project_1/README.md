# COMS 5790 - Project 1: Terminologies and Topic Analysis

**Author:** Giuliano Pitari  

## Overview
This repository contains the code for Project 1 of the COMS 5790 course at Iowa State University. The project focuses on analyzing terminologies across two research corpora (Animal Science and LitCovid). 

The pipeline includes:
- **Task 1:** Text pre-processing and Word Cloud visualizations (Term Frequency & TF-IDF).
- **Task 2:** Word2Vec embedding training and 2D visualization using t-SNE.
- **Task 3:** Phrase mining implementation to extract and annotate bi-grams and tri-grams.

## How to Run the Code
This project was developed using **Google Colab** to streamline dependencies and avoid the need for the Nova cluster.

1. Clone this repository or download the `.ipynb` notebook.
2. Open [Google Colab](https://colab.research.google.com/) and upload the notebook.
3. **Data Setup:** The original datasets (`animal.tsv` and `litcovid_sample_1000.json`) must be accessible to the notebook[cite: 1]. By default, the code is set up to mount Google Drive. Please upload the datasets to a folder in your Google Drive and update the path in the notebook accordingly. Alternatively, you can upload them directly to the Colab session storage.
4. **Dependencies:** Run all cells in order. Standard data science libraries (`pandas`, `scikit-learn`, `gensim`, `matplotlib`) are either pre-installed in the Colab environment or will be installed in the first execution cell.
