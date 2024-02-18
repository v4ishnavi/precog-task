# Precog Recruitment Task 2024

This repository contains all necessary documents and code for the Precog recruitment task 2024, focusing on Task 1 - Representations for words, phrases, and sentences. 

## Repository Structure

- `research_paper.pdf` - Required reading.
- `RecruitementTask.pdf` - PDF containing tasks and their descriptions.
- `1.ipynb` - Contains Part A and the phrase similarity section of Part B.
- `2.ipynb` - Covers sentence similarity for Part B and Bonus Task 1.
- `3.ipynb` - Dedicated to similarity calculations using BERT embeddings (without fine-tuning).
- `datasets/` - Hosts SIMLEX999, AFINN111, and AFINN96 text files used in our analyses.
- `word_embedding_pics/` - Contains visual plots of word embeddings.
- `precog_report.pdf` - A comprehensive report detailing methodologies, results, and analyses, including a summary of the paper reading task.
- `paper_summary.pptx` - A PowerPoint presentation highlighting the strengths, weaknesses, and suggested improvements of the assigned reading.



## Overview

This project is divided into several Jupyter notebooks, each addressing different facets of word, phrase, and sentence representations. Markdown annotations within each notebook guide the reader through the methodologies and analytical processes.

## Data

The `datasets` directory includes essential resources:

- **SIMLEX999**: A dataset for semantic similarity evaluation.
- **AFINN111 and AFINN96**: Sentiment lexicons for sentiment analysis tasks.

## Visualizations

The `word_embedding_pics` directory provides graphical insights into the embedding space, illustrating the relationships between words.

## Requirements

To run the notebooks in this repository, you will need to have the following libraries and packages installed:

- `tensorflow`
- `torch`
- `sklearn.metrics`
- `numpy`
- `pandas`
- `spacy`
- `tensorflow.keras`
- `scipy`
- `gensim`
- `plotly`
- `nltk`
- `multiprocessing`

Please ensure that all these libraries are installed to avoid any runtime errors. All other libraries used are installed within the codebase.
You can install them using pip:

```bash
pip install tensorflow torch scikit-learn numpy pandas spacy tensorflow.keras scipy gensim plotly nltk multiprocessing
