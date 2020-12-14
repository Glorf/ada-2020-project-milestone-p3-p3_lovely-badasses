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

While we are happy with our first results, let's not stop here. There are so many world's events that happen everyday, we cannot be sure that the chilling effect observed was due to the revelations of Snowden of 2013. Maybe a lot of events related to terrorism happened before 2013, so that's why we observe such trends. Of course that the Wikipedia views will be affected by external world's event. But what exactly were the external events related to terrorism before and after June 2013 ? We gathered most of them below. Feel free to explore them.


TODO insert here circular plot of the external events calendar, ideally when we hover over a case it explains in one line what the event is.

TODO When clicking on the event, also plotting a graph of the article view count and a marker of the day they clicked on


# Now are we still chilling ?

Now we reproduce the same figure as the first one, but without all the external events that disrupt the general trend. Do we still have chilling effect ? The suspense is at its peak...

TODO insert figure of the new regression, maybe adding a functionality that allows the reader to discover the image by themselves, if you know what i mean. 

TODO write conclusion here depending of our results

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.



# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```

