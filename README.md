# API Guardian Data Project
## Sentiment Dynamics in Discourse: Analyzing the Intersection of Narratives Between Palestine, Gaza, and Israel
## Description and mini report
In this report we used the Guardian API database to answer the question of whether Guardian sides more with Israel or Palestine in the media since the recent escalations. To do this we first split the articles into three groups: Israel only, Palestine only, and Israel and Palestine. Then we cleaned the articles to only include alphabetical characters and we tokenised the articles for each group. Following this, we employed part of speech tagging and lemmatisation followed by generating the polarity of each article through sentiment analysis. Lastly, the article numbers for each group along with their sentiment were visualised in a horizontal bar chart.

As shown in the visualisation, we have a total of 194 articles that covered Israel compared to 59 for Palestine. Israel had 156 positive published articles (80%) whereas Palestine had 49 (83%). Even though Palestine has a higher percentage of positive articles it is important to consider the total number of articles for both Palestine and Israel. While Guardian seems to side with Palestine percentage-wise, the sheer volume of articles about Israel is significantly greater. This numerical difference is crucial when interpreting the overall narrative bias. The disparity in article counts underscores the importance of considering both volume and sentiment in media analysis as well as media bias and conflict dynamics.
## Result
![image](https://github.com/farizmpr/Python-Week-6-Group-Project/assets/32903342/a63ccf29-be93-4570-8ab9-3814b83efd4b)
### Interpretation
- (Palestine OR Gaza) AND Israel
- (Palestine OR Gaza) AND NOT Israel
- Israel AND NOT (Palestine OR Gaza)

For each category, sentiments have been classified into three types - Negative, Neutral, and Positive. The length of each bar represents the count of sentiment occurrences in the texts. Here's an interpretation of the results:

- (Palestine OR Gaza) AND Israel: Mentions that include either Palestine or Gaza and Israel are overwhelmingly neutral, with a significant count (the longest bar in the graph, extending towards the right). There are more negative mentions than positive ones, as indicated by the shorter red bar compared to the shorter blue bar extending towards the left.

- (Palestine OR Gaza) AND NOT Israel: When mentions include Palestine or Gaza, but not Israel, the sentiment is mostly neutral with a smaller count compared to the first category. There are a few positive mentions and almost no negative mentions (the negative bar is minimal or at zero).

- Israel AND NOT (Palestine OR Gaza): For mentions of Israel alone, without Palestine or Gaza, the sentiments are again mostly neutral with the count being less than the first category but similar to the second. There are some negative mentions with a very small or negligible number of positive mentions (the positive bar is minimal or at zero).

The data suggests that discussions including both Israel and Palestine or Gaza have a higher engagement or count and are more likely to be classified as neutral, but with a tendency towards negative sentiment compared to positive. When each is mentioned without the other, the counts decrease, and the sentiment is predominantly neutral, with some negativity towards Israel alone and very little positivity mentioned for either when they are discussed separately.
