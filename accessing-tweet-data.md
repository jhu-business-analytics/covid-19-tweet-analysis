# Accessing and Sharing Twitter Data

Although all of the tweets that we analyze are from public twitter accounts that anyone can access from a website link, Twitter sets up its developer agreement and policies to try and protect Twitter user data and data distribution as much as possible. According to Twitter's [developer terms](https://developer.twitter.com/en/apply-for-access), anyone who accesses and redistributes Twitter data must: 

* Be careful about using Twitter data to derive or infer potentially sensitive characteristics about Twitter users
* Get express, opt-in consent from the user before making off-Twitter associations between user accounts and other identifiers \(e.g. names, households, other business accounts, etc.\) or only use publicly-accessible information to make the associations
* Share only Tweet, Message, or User IDs \(instead of the actual Tweet text, message text, or usernames\) to preserve the most current information on Twitter \(e.g. if someone deletes a Tweet or changes their username\)
* Only distribute up to 1,500,000 Twitter IDs within a 30-day period unless given explicit permission from Twitter
* Not use the data to spam or aggressively automatically message or tweet users

among other requirements. A Twitter "developer" is defined as someone who uses the Twitter API to download tweets, account information, or message information and who may potentially distribute this information for their personal \(own research or curiosity\) or professional \(advertisement company, etc.\) use. 

{% hint style="info" %}
An API is an **Application Programming Interface.** APIs are like connection points between websites, other software components, or computing systems and the API user that allow the user to directly access information in the form of _requests_ from those sources depending on the API terms. These API requests can help individuals and organizations access data \(e.g. from Tweets or weather\), authenticate users \(e.g. when you sign into a service "through" Google or another social media account\), or consolidate information \(e.g. when you see an aggregation of airline options on Expedia.com\), among other things, and may be a free or paid service.
{% endhint %}

Anyone with a Twitter account can apply for a [developer account](https://developer.twitter.com/en/apply-for-access) to receive free API keys \(special codes that allow you to use Twitter API--similar to the codes we used with Mapbox\), which are granted to your account if Twitter approves your developer application and reasons for wanting to use the API. 

The data that we'll use in this tutorial has already been collected and aggregated with a Twitter API \(so we won't need to create a developer account\), but it's important to understand why our data is formatted with only Twitter IDs and how we might access additional information in the future. 

