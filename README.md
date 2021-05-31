# Topic-Modeling-Jeopardy-with-LDA

## Approach to Topic Modeling for this project:

Data: Questions from the game Jeopardy! for the past 30 years

Objective: Analyse how the topics of the Jeopardy questions changed over the years

For this project the approach taken for topic modelling was:

1. Partitioned the data into 90 parts using the Year and Question Type (Jeopardy!,Double Jeopardy!,Final Jeopardy!)
2. Applied 90 separate LDA models on each of these datasets to find the topic
3. Used **coherence score** to find the best k (number of topics) for LDA.
4. Using word_vectors similarity score, tried to find the similarity between different topics using the best topic which represented the document and the best words which represented the topic
5. Calculated the similarity trends across years, and noted the observations.
