---
layout: default
---

[![headlines.png](https://i.postimg.cc/66f5R0Wc/headlines.png)](https://postimg.cc/3WWTQ2D0)

# Snowden's revelations 

In June 2013, Snowden reveals to the whole world shocking news about the U.S. government : the NSA is spying on the web traffic of the entire world ! This makes the headline of every newspaper in the world, everybody is talking about it. Everyone wonders how they should behave on the Internet, now that they know every one of their searches is being collected. 

Today, our task is to investigate how people behaved after the events. We will need to figure out whether people were chilled from using the Internet the way they used to, or not. For that, we have at our disposal data from Wikipedia view counts and Google searches counts.

Let's dive into these datasets and find out **how** people actually behaved.


# Let's start our investigation...

With more than 18 billions of monthly pageviews, there are a lot of Wikipedia articles at our disposal. We need to focus on the ones that are actually meaningful in our investigation. So we have to ask ourselves a question : what articles might people be chilled to look up after such revelations ? Imagine yourself, in June 2013, thinking about all your past activities on the Internet, trying to remember what you looked up that could potentially raise a flag for the government. Imagine yourself, in June 2013, wondering how you will look up, for tomorrow's speech in your history class, informations that the government might classify as suspucious.  

Well, it is interesting to think about what articles fall into that category. The category of topics that, when you look them up,  a small part of you thinks that this would make you look bad from the eyes of the government. This category contains every topic related to terrorism matters, because that's what the government is tracking, people with interest in terrorism's questions.

TODO insert World Cloud picture here, maybe interactive like when we hover over a word, there is the percentage of participation in the trend, or the total number of views, or the mean number of views per week/month, etc...

![Terrorism wordcloud]({{ site.url }}{{ site.baseurl }}/assets/pwc_t.png) 
> Subjects that people might have been chilled out to look for, together with their popularity in Wikipedia

We are going to look at the view counts for articles on Wikipedia, related to terrorism, to find some insight about how people behaved. Here are the trends observed for before and after the revelations.

TODO insert graph of the first time period to the left, and a short comment on it to the right.
Make an option to change the visualization to the second period 

{% include fig1.html %}

TODO write this next to the figure for before 2013
> Before June 2013, people were more and more engaging with the articles related to terrorism 

TODO write this next to the figure for after 2013
> After June 2013, people starting to go less and less on these Wikipdeia pages

Interesting ! The number of views seems to be impacted by the revelations !


#  Snowden's revelations, not the only big news

While we are happy with our first results, let's not stop here. There are so many world's events that happen everyday, we cannot be sure that the chilling effect observed was due to the revelations of Snowden of 2013. Maybe a lot of events related to terrorism happened before 2013, so that's why we observe such trends. Of course that the Wikipedia views will be affected by external world's event. But what exactly were the external events related to terrorism before and after June 2013 ? We gathered most of them below. How do we do that ? Well, when there is a breaking news and you want to know more about it, what do you do ? You type keywords in Google. And probably so does everyone else. This creates an extraordinary amount of requests in the Google search bar, and we can find these counts numbers with the Google Trends tool. 

We gathered those extraordinary events, feel free to explore them.


TODO insert here circular plot of the external events calendar, ideally when we hover over a case it explains in one line what the event is.

TODO When clicking on the event, also plotting a graph of the article view count and a marker of the day they clicked on

# North Korea's nuclear complex

Let's zoom into a particular example. On the calendar, we see that on the week of 31st of March 2013, the Wikipedia article 'Nuclear' has a high activity. It makes sense because on the 2nd April, North Korea says it will restarts its main nuclear complex, including a reactor mothballed. This is only about news in the world, and should not be an event that interests us. The only one that we care about is Snowden's revelations. People wouldn't be chilled about getting informed on nuclear technology when the nuclear topic is at the center of every news.

TODO insert graph of views for 'nuclear' and a marker on 31-03-2013


# Now are we still chilling ?

We want to remove all the external world events from our study, because they are single events in time. We want an illustration of an effect that is lasting in time, not disturbed by external breaking news. Recall the question we need to answer : from June 2013, is there a constant fear of the goverment spying among Internet users ? Let's see what the data in a world without big common events looks like. To do that we reproduce the same figure as the first one, but without all the external events that disrupt the general trend. Do we still have chilling effect ? The suspense is at its peak...

TODO insert figure of the new regression, maybe adding a functionality that allows the reader to discover the image by themselves, if you know what i mean. 

> Write here what we see !


# Title depending on the final plot 

TODO write conclusion here depending of our results



