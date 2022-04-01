# Localnorm
This is an implementation of paper Journey to the center of the words: Word weighting scheme based on the geometry of word embeddings.


Setup:
1. Install the python packages in requirements.txt.
2. Keep the STS datasets in datasets folder. We already provided these dataset files (pre-processed) in this repo as they are fairly smaller in size.
3. Keep the Word embedding files (GloVe, Word2Vec) in data folder. We couldn't provide these word embeddings files in this repo as they are too big. However, instructions are given in data folder on how to download them very easily.

Run:
1. Simply, run the localnorm.py file. Current code works with Glove embeddigs.
2. For Word2vec, uncomment lines #201 - #209 and comment out lines #198 - #199.