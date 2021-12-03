# Gender based Fairness Analysis in Stories


Run in the follwing order to identify useful fairness based trends
1. NLP_Fairness_in_stories.ipynb
    1. Fetches the data + Preprocessing to output clean sentences from stories corpus
    2. Extracts Events using Spacy
    3. Categorizes events on gender and filters out non-gender based events
2. Visualizations.ipynb
    1. Visualizes odds ratio scores of our extracted events
4. weat.ipynb
    1. Computes the weat scores using the word2vec model for the 5 different genre-based categories of our stories dataset:
    2. Genre-based Categories: General, Children, Fiction, Male_Author, Female_Author


Active internet connection is required for downloading stories from Gutenberg (we are using html links to fetch stories)

