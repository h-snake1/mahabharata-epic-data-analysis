
Mahabharat Book Analysis
========================

This project performs a structured analysis of the Mahabharat using natural language processing (NLP) and data visualization techniques to uncover narrative insights, character dynamics, and linguistic features.

Project Overview
----------------

The analysis is divided into two main notebooks:

1. Mahabharat Book Analysis 1
   - Loads and cleans the raw text of the Mahabharat.
   - Segments the text into structured episodes/chapters.
   - Performs basic preprocessing (lowercasing, punctuation removal, tokenization).

2. Mahabharat Book Analysis 2
   - Analyzes character frequencies and co-occurrences.
   - Generates word clouds for visualizing key themes and characters.
   - Applies sentiment analysis using TextBlob.
   - Plots temporal trends in sentiment and character appearances.

Tools & Libraries Used
----------------------

- pandas, numpy: Data handling and manipulation
- matplotlib, seaborn, wordcloud: Visualization
- nltk, TextBlob: NLP preprocessing and sentiment analysis
- re: Regular expression-based text cleaning

Key Outcomes
------------

- Identified top-mentioned characters across chapters.
- Extracted patterns of character co-occurrence and dialogue presence.
- Visualized emotional shifts across the story.
- Built reusable preprocessing and visualization functions for textual epics.

Getting Started
---------------

To run this project:
1. Clone the repository and open both notebooks (.ipynb) in Jupyter Lab or Google Colab.
2. Install required libraries:
   pip install pandas numpy matplotlib seaborn nltk textblob wordcloud
3. Run all cells sequentially to reproduce the analysis.

Future Improvements
-------------------

- Incorporate Named Entity Recognition (NER) for improved character mapping.
- Add topic modeling to explore latent themes.
- Use transformers (e.g., BERT) for more advanced sentiment/context analysis.
