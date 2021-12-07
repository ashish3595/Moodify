# Moodify
A Spotify based mood-based recommender system

Based on the songs the user listens to and their personal information, identify their mood (i.e., sad, depressed, anxious, happy, excited, etc.) and recommend songs having a similar theme to improve it.

2 recommendation algorithms developed:
1. Based on the 2-D Valence-Arousal plane to represent entire spectrum of human emotions
2. Based on sentiment analysis on song lyrics to identify sentiment and polarity and recommend songs of higher cosine similarity with better sentiment - using LightFM.

File Descriptions:
1. getUserPlayList.py -  script that builds feature vectors for songs using several characteristic and audio features.
2. RuleBasedApproach - computes initial clusters for training data based on 2-level K-Means clustering.
3. data - folder that contains the data used for the project



