# Sentiment-Analysis-Hotel-Reviews-Japan
This project involves performing a sentiment analysis of hotel review data in Shirakawa, Japan crawled from Tripadvisor to identify positive and negative words and noun phrases.

Four analysis methods are used in this data science project to analyze the hotel reviews:
1. Natural Language Toolkit (NLTK)'s Vader is used to calculate the sentiment of each hotel review

Ex: Average Vader sentiment vs. ground truth ratings

![image](https://github.com/user-attachments/assets/b377165a-9496-4266-8d02-fd0b52c39b0e)

2. Term frequency analysis is used to find the most commonly appearing words and noun phrases in positive and negative reviews

Ex: Top k noun phrases with propositions appearing in positive reviews

![image](https://github.com/user-attachments/assets/fa4b8e1b-1897-4353-994c-374789a10a6f)


3. Mutual information and pointwise mutual information are used to rank the top 50 most sentiment-affecting words and noun phrases

Ex: Top k words ranked by MI that inform you that the review is likely negative

![image](https://github.com/user-attachments/assets/2232fa1a-d3ea-441f-9282-9ae49ca0374d)

4. Plots such as histograms, boxplots, scatterplots, and heatmaps are used to visually understand how closely Vader's sentiment analysis is reflected in the ground truth ratings of the reviews.

Ex: Box plot of Vader's sentiment analysis ratings vs. the ground truth ratings

![image](https://github.com/user-attachments/assets/0cf13eef-a841-4545-8ca4-c38e5d1a926a)

Ex: Scatterplot and heat map of ground truth star ratings versus Vader's sentiment analysis score

![image](https://github.com/user-attachments/assets/aeb82b69-72a0-4287-9c1c-f2afebcef064)
