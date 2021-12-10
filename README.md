# Moodify
A Spotify based mood-based recommender system

Based on the songs the user listens to and their personal information, identify their mood (i.e., sad, depressed, anxious, happy, excited, etc.) and recommend songs having a similar theme to improve it.

2 recommendation algorithms developed:
1. Based on the 2-D Valence-Arousal plane to represent entire spectrum of human emotions
2. Based on sentiment analysis on song lyrics to identify sentiment and polarity and recommend songs of higher cosine similarity with better sentiment - using LightFM.

File Descriptions:
1. getUserPlayList.py -  script that builds feature vectors for songs using several characteristic and audio features.
2. RuleBasedRecommendation.ipynb - computes initial clusters for training data based on 2-level K-Means clustering.
3. data - folder that contains the data used for the project (both zip and csv)
4. Data_preparation.ipynb - gets songs dataset asinput and handles initial spotify API calls to extract song audio and general features and performs data cleaning.
5. Lyrics_extraction_geniusapi.ipynb - extracts lyrics for Spotify song dataset using Genius API
6. NLP_embeddings_approach.ipynb - generates recommendations using LightFM approach using word embeddings


