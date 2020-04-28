# Analyzing COVID-19 Related Tweets

So far we've focused on Python numerical analyses to gain insights into how the COVID-19 virus might negatively impact certain US counties and how the pandemic has spread  across the US. This is largely because the analyses that we conduct and statistical models that we build depend on numbers, however, much of the world around us operates in non-numerical language. It's useful for organizations to analyze textual data so that they can better understand consumers' opinions and feedback, trending topics, or common reactions to an event. Social media websites, such as Twitter, also provide large amounts of individualized, textual data that can help us derive valuable insights from different communities or on different topics and check the pulse of different events, topics, or points in time. While we need to comply with the terms and user agreements in each social media \(or any website\) platform, we can use most of this data for our own analysis once we format this in a usable structure. 

### Natural Language Processing in Python

While sentences, paragraphs, and documents have some structural element, it's difficult to perform analyses on textual data since there's not necessarily a standard "data frame" of information for all letters and words. We'll use the [Natural Language Toolkit](https://www.nltk.org/) \(NLTK\) Python package to help us structure and analyze sentences, phrases, and words in a dataset of tweets that reference COVID-19 \(or a related term\) as a hashtag to see how people are talking about COVID-19 and what else they might be talking about at the same time. Looking at this information over several days might give us insight into how people's reactions change over time or how different events impact the kind of language people use in their tweets. 

Although the first COVID-19 in the US was reported in late January 2020, we saw in our animated geospatial county map that the number of COVID-19 cases in the US spread slowly throughout February 2020, and then quickly between March 4, 2020:

![](.gitbook/assets/march04-covid-us-spread.png)

and April 1, 2020 \(4 weeks later\):

![](.gitbook/assets/april-1-covid-us-spread.png)

**We'll analyze** [**COVID-19-related tweets**](https://github.com/echen102/COVID-19-TweetIDs) **scraped and formatted by a group at the** [**University of Southern California's Information Sciences Institute**](https://arxiv.org/pdf/2003.07372.pdf) **to see how people's tweet language differed on these dates.**



