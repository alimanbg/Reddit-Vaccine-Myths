# Detecting and Visualizing Echo Chambers in Reddit Vaccine Myths Discussions

***

## Project Overview
This project investigates echo chamber formation and the spread of vaccine misinformation in Reddit’s r/VaccineMyths community. Using a Kaggle dataset of posts and comments, the analysis identifies communities, measures sentiment, uncovers discussion themes, and visualizes echo chambers using network science techniques.

## Goals & Research Questions
1. How do echo chambers form within r/VaccineMyths?
2. Which topics and sentiments are dominant in these communities?
3. How do group structures relate to beliefs and the spread of vaccine misinformation?
4. What are the broader implications for understanding and addressing online misinformation?

## Data & Methods
- **Dataset:** Reddit posts/comments from r/VaccineMyths (Kaggle)
- **Columns:** `title`, `score`, `id`, `url`, `comms_num`, `created`, `body`, `timestamp`
- **Analysis Methods:**
  - Data cleaning and preprocessing
  - Sentiment analysis (VADER)
  - Topic modeling (LDA)
  - Network construction by text similarity
  - Community detection (Louvain algorithm)
  - Visualization with matplotlib and networkx

## Project Contents
- `/code/` – Jupyter/Colab notebooks and Python scripts
- `/data/` – Reddit dataset (CSV)
- `/reports/` – Project proposal, progress, and final report (DOCX)
- `/outputs/` – Graphs, community plots, figures
- `/README.md` – This file

## How to Use This Repository
1. Review the README (you’re here!)
2. Read the analysis notebooks/scripts in `/code/`
3. Explore results, graphs, and figures in `/outputs/` and summary statistics in `/reports/`
4. If running yourself, ensure Python 3.x and required packages are installed

## Requirements
- Python 3.x
- Required packages: `pandas`, `numpy`, `nltk`, `vaderSentiment`, `gensim`, `networkx`, `matplotlib`, `seaborn`, `scikit-learn`, `pyLDAvis`

**Install dependencies:**
```bash
pip install pandas numpy nltk vaderSentiment gensim networkx matplotlib seaborn scikit-learn pyLDAvis
```

## Technologies Used
- Python (Colab notebooks and scripts)
- pandas, gensim, vaderSentiment, networkx, matplotlib, seaborn
- GitHub for version control

## Academic Reports Included
- `/reports/proposal.docx` 
- `/reports/progress.docx`
- `/reports/final_report.docx`



[9](https://github.com/mundimark/awesome-markdown)
[10](https://www.hatica.io/blog/best-practices-for-github-readme/)
