# Text Analysis and Visualization of Twitter Posts
**Authors:** Jenny (So Youn) Kim & Atlanta Liu 

**Date:** Winter 2020

### Introduction
This is the final project for an advanced visualization course at the University of Calgary. For this project, we are comparing the overall context and trends of self-reported sleep disorders with physical activity tweets through an exploratory data analysis. We are aiming to gain a general understanding of how Canadian health is changing throughout time and major events and the reactions of Canadians as they share and post about perceptions regarding the state of their own physical and mental health.

### Dataset
The Twitter dataset for both sleep disorders and physical activity was provided in a CSV format, with approximately 6000 and 8800 rows, respectively. The dataset contains about 500 columns, but only the name of the 'city', 'coordinates', 'text', and 'date created' were used in our analysis. The time span of our initial dataset included about three months, ranging from October to December 2019. A separate dataset containing labelled self-reported conditions was also used for this project. 

### Project Breakdown

The first phase of this project involved exploring the distribution of self-reported tweets across Canadian provinces as a preliminary and exploratory analysis. Then we implemented a supervised and unsupervised learning component to deepen our analysis. Naive Bayes and Random Forest supervised learning models were trained in python to predict if the tweets were self-reported and determine if machine learning algorithms can classify tweets of interest for further research in this area. We applied natural language processing (NLP) for the unsupervised learning component and built multiple bigrams in R to visualize their text network. This visualization allowed us to get an overall understanding of the general context behind all the tweet posts.

To see if our findings could be further strengthened via data triangulation, we pulled data from other platforms (Google Trends & Reddit). We were interested in understanding the association between public's web search and tweets by comparing self-reported tweet counts and relevant search topics in Google. Furthermore, multiple subreddit posts were mined to compare Twitter posts with Reddit using bigrams. 

Finally, we created a barplot dendrogram to visualize the results of our Latent Dirichlet allocation (LDA). LDA is a natural language processing technique that falls into the topic modelling category. We conducted LDA analysis to discover relationships between a large set of words to observe any hidden semantic structure behind the words (i.e. do the words fall into discrete topics?).

### Tableau Visualizations

![Physical Activity and Sleep Disorder Tweet Comparison Across Canada]![Map](https://user-images.githubusercontent.com/80138718/110217252-455b9980-7e70-11eb-8ee2-ec774aefc545.png)

![Google Trends]![GoogleTrends](https://user-images.githubusercontent.com/80138718/110217310-86ec4480-7e70-11eb-83ad-62f25830a63c.png)

![Bigram Dashboard]![Bigrams](https://user-images.githubusercontent.com/80138718/110217325-9bc8d800-7e70-11eb-9a84-720fd208d640.png)

![Binary Classification]![BinaryClassify](https://user-images.githubusercontent.com/80138718/110217330-a3887c80-7e70-11eb-9a86-017aad82c138.png)

![Physical Activity LDA]![PhysActLDA](https://user-images.githubusercontent.com/80138718/110217334-a8e5c700-7e70-11eb-9bfd-05c4295f6d13.png)

![Sleep Disorder LDA]![SleepLDA](https://user-images.githubusercontent.com/80138718/110217338-ad11e480-7e70-11eb-9946-19328bb02b04.png)
