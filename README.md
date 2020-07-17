# Review-Analysis
Analysis on Yelp Reviews

This project applied NLP techqniues including stemming and lemmatization, N-gram model, word embedding and tf-idf score to conduct sentiment analysis on Yelp review for a buffet restaurant in Las Vegas. The data is from open source Yelp data. \\

The Jupyter notebook outlines the step taken to identify key words in good reviews and poor reviews, and generize word cloud for better visualization. It also expore the sentiment classification using logisitic regression and decistion tree model.

In addition, a hypothesis test is performed to see if customer service is mentioned about the same time in good and poor reviews respectively. Based on the Exploratory Data Analysis, customer service is a keyword shown in poor reviews but there are relatively less poor reviews. By comparing the percentage of time 'customer service' mentieond in both class of review population, we tested that it is statistically significant that 'customer service' is mentioned in different manner in both reviews. There are many limitations with just using word count to analyze reviews. Even though we have the reviews separated into poor and good, we do not understand the context of the reviews that mention our key words. Still, it implies that customer service is a major factor that customers care about and the restaurant should pay more attention to.
