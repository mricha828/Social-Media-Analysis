# Social-Media-Analysis
Credibility of Scientific Information on social media, BI Reporting and Dashboard Design 


OBJECTIVE

Problems to Address: During a pandemic, accurate and credible information is crucial for public health and safety. There is a lot of information out there on social media, especially a lot of facts and figures about COVID-19. But considering the average education level of users, they a lot of times are not able to make much sense of the data provided and end up mis-communicating, mis-reading the information. Our goal is to help people get some basic ideas about information given through our various visualizations. 

Importance of Addressing the Problem: As the general public consists of a varied crowd, from scientists to people who don't understand English like (immigrants), it is important to provide basic information regarding COVID to people who have high school knowledge. Addressing credibility issues is vital to ensure that individuals receive accurate and reliable information during a health crisis; this ensures considerable public safety. Credible information sources are essential for building and maintaining trust in official guidance and expert advice.

What to Accomplish: We aim to implement data visualization techniques to present the interplay among topics, credibility, keywords, and sentiment regarding the pandemic. We also look forward to disseminating the findings and insights to public officials and parents, ensuring they can distinguish between credible and non-credible information and make informed decisions.

Who Will Benefit, and How: A large sector of the public - for eg: Public Officials and Parents will benefit from such meaningful visualizations. Public officials will benefit from improved tools and insights for making informed decisions during the pandemic. Parents, on the other hand, can benefit from accurate information to make informed decisions about their children's safety and well-being.

DATASET DESCRIPTION

We have tweets recorded from March 2020 to September 2020
Total Number of Records (rows) : 10688
Total Number of Attributes (columns) : 11




Attribute Name
Data Item/ Attribute Type
Description
Whether of interest or not?
Text
Data Item
Raw text content of the tweets
Yes
month
Numeric
month in which the tweets were posted
No
cleaned_tweet
Data Item
preprocessed tweets
Yes
expert_label
Categorical
indicate whether the tweet is from an expert source or not
Yes
sentiment_score
Numeric
a numerical score indicating the sentiment of the tweet
No
sentiment_label
Categorical
label indicating the sentiment of the tweet
Yes
subjective_prob
Numeric
the probability of the tweet being subjective
No
objective_prob
Numeric
the probability of the tweet being objective
No
subjectivity_label
Categorical
a label indicating whether the tweet is subjective or objective, depending upon which of the above two probabilities are higher
Yes
topic_category
Categorical
the category or topic of the tweet
Yes
intent
Categorical
indicates the intent behind the tweet
Yes



Attribute’s Contribution : “text” can be used to deeply understand the content and then analyze the topics. “Expert_label” and “sentiment_label” distinguish expert communication from non expert communication and assess the emotional tone and credibility of the tweets respectively. Knowing a tweet’s subjectivity and intent helps in assessing its purpose. 

Examples of How Attributes Address the Objectives and Goals: 

Information Visualization:   "sentiment_label" can be used to create sentiment heatmaps, which can visually represent how credible information tends to have a more neutral sentiment compared to less credible information with extreme sentiments.
Educational Outreach:   The "topic_category" attribute can help identify tweets related to safety measures and health guidelines, which are critical for educational outreach. "intent" can help determine the intent behind information dissemination, which is valuable for educational efforts.
Cross-Verification:   By considering both the "subjectivity_label" and "expert_label," you can identify tweets from expert sources that provide objective information, which is crucial for cross-verifying facts.

VISUALIZATION NEEDS AND TASKS

Why Visualization is needed: It is needed to address the problem of evaluating the credibility of COVID-19-related tweets, understanding sentiment, and navigating information on Twitter for several reasons. Data table can be tedious to interpret and work on, especially when you have large and complex data. 

Complex Data: The data contains various attributes, such as text content, sentiment scores, and expert labels, which can be challenging to comprehend solely through data tables.
Interplay of Factors: Understanding how attributes like sentiment, subjectivity, and topic categories interplay with credibility is best achieved through visualization.
User Engagement: Visualizations can engage users more effectively, making it easier to grasp and interpret the data and its insights.
Quick Recognition: Visualizations allow for the quick recognition of patterns, trends, and anomalies in large datasets.
Interactive Exploration: Users can interact with visualizations to explore the data and adjust parameters to focus on specific aspects of interest.
Accessibility: Visualizations can make complex information more accessible to a broad audience, including those without data analysis expertise.

Visualization Tasks: There are various visualization tasks we could list out in order to effectively satisfy our objectives

Compare Sentiment:   Users may need to compare the sentiments of credible and non-credible tweets within specific topics or categories. Sentiment charts can help compare the overall tone of different tweets.
Topics and Keywords: Explore COVID-19-related topics through interactive topic networks or treemaps, gaining insights into the distribution of tweets, while concurrently visualizing keyword associations using tag clouds or network graphs to identify the most relevant terms and connections within the context of the pandemic.
Track Sentiment Trends:   Time series visualizations enable users to monitor sentiment trends across months or periods, providing insights into the evolution of sentiments over time (March to September). 
Subjective vs Objective Analysis:   Create visualizations that incorporate both Subjective analysis and Expert source, to display the subjectivity of tweets while distinguishing between expert and non-expert sources. This combined visualization approach effectively communicates both the subjectivity of tweets and the credibility of sources, offering users a comprehensive understanding in a single display.
Intent: Categorize data into five separate dashboards, each corresponding to a specific communication intent. Facilitates targeted analysis, allowing users to explore and understand distinct patterns and insights associated with different communication objectives.





