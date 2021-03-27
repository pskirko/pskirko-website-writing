# Front Matter

© 2021 Peter Skirko. All rights reserved.

## Revision History

* Version 1.0 - 2021/03/27 - Initial commit (grabbed from website).

# My 2017 Twitter Year in Review: Small Data Edition

Note: This was migrated from my old Medium blog. I have decided to migrate from Medium to WordPress, and I’ll write about the reasons why soon, stay tuned.

Big Data has been a Thing™ for over a decade now. Google published the [GFS paper](https://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf) in 2003 and the [MapReduce paper](https://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf) in 2004. [Hadoop](http://hadoop.apache.org/) started a few years later. Interestingly, the Google Trends [trend for “Big Data”](https://trends.google.com/trends/explore?date=all&q=big%20data) didn’t start to take off until 2011, though:

![](https://i0.wp.com/35.224.241.201/wp-content/uploads/2018/06/smalldata1.png?resize=525%2C186)

Why is that? Well, one clue is that Big Data grows along with, and is even eclipsed by, the rise of AWS, as this [trend comparison](https://trends.google.com/trends/explore?date=all&q=big%20data,%2Fm%2F05nrgx) shows (AWS in red):

![](https://i1.wp.com/35.224.241.201/wp-content/uploads/2018/06/smalldata2.png?resize=525%2C182)

That makes sense: Big Data took off once cloud infrastructure became cheap and flexible enough for the masses.

That said, not all data is Big Data. Some data is, well, Small Data. The Web abounds with thought leadership jockeying over the “big vs small data” question. For my purposes, the difference will be considered self-evident.

For me, Twitter is a perfect source of small data to analyze. It lets me reflect on my behavior in a structured, quantitative way. Such an analysis is complementary to the off-the-cuff reasoning that happens inside my head.

In 2017, I tweeted a whopping 21 times. In hindsight, I’d say my main reason for not tweeting much is what Facebook calls “meaningful interaction”, or lack thereof, in my case. Facebook just [tweaked its News Feed algorithm again](https://www.nytimes.com/2018/01/11/technology/facebook-news-feed.html?_r=0) precisely to address this. I think they’re spot on.

With that hypothesis on the table, one straightforward solution suggests itself, before even looking at any data: spend more time engaging with my friends, and try to engage in tweet discussions around my interests, such as coding and design.

But let’s look at the data to be sure. First, I manually categorized my 2017 tweets by topic:

Date       Topic
-------------------------
01/07/2017 Design
01/08/2017 News
01/09/2017 Hamburger Eyes
01/13/2017 Design
01/20/2017 Startups
02/07/2017 Misc
02/14/2017 Hamburger Eyes
02/15/2017 Video Games
03/03/2017 Startups
04/10/2017 Apple Music
04/11/2017 Apple Music
04/13/2017 Misc
04/19/2017 Apple Music
04/27/2017 Apple Music
05/11/2017 Apple Music
05/17/2017 Apple Music
05/30/2017 Startups
06/22/2017 Music
06/28/2017 Music
07/25/2017 Apple Music
08/22/2017 Tech

Then, I used my blunderingly naive pandas and matplotlib skills to munge and plot the data:

import matplotlib.pyplot as plt
import pandas as pd

# Omitting a bunch of data and plot munging for brevity. Left as an
# exercise for the reader, or ping me on Twitter for advice.

data = pd.read\_csv("2017\_tweets.csv")
month\_groups = tweet\_dates.groupby("Month")
counts\_by\_month = month\_groups.agg("count")
counts\_by\_month.plot(kind='bar')
plt.show()

topic\_groups = data.groupby("Topic")
counts\_by\_topic = topic\_groups.agg("count")
counts\_by\_topic.plot(kind="pie", y="Count")
plt.show()

Here is the histogram by month:

![](https://i1.wp.com/35.224.241.201/wp-content/uploads/2018/06/smalldata3.png?resize=525%2C456)

Those results are somewhat funny. The January high of 5 is due to my renewed efforts at the start of every year to try and engage more on social media. Clearly, that effort loses steam as the year progresses. The matching high in April I’d guess was due to being done with taxes. Thus relieved and relaxed, I started listening to more music again. When I’m stressed, I tend to pick an album and listen to it on repeat.

Why no Twitter in the last 4 months of the year? Not sure. There’s a lot of circumstantial factors. I changed teams at work, for example. But nothing adds up convincingly. Let’s leave it as a small mystery for now. It’s more fun that way, anyways.

Here is the pie chart for the topic breakdown:

![](https://i1.wp.com/35.224.241.201/wp-content/uploads/2018/06/smalldata4.png?resize=525%2C394)

(Due to the height of my laptop screen, the pie ended up being an oblate spheroid #lol).

The biggest topic is Apple Music, when I share the song I am listening to straight from the Music app. None of these tweets drive interactions, but I like them as a form of self-expression, so doing that still makes me satisfied.

Another notable topic is Hamburger Eyes, a fantastic photography magazine I discovered over a decade ago. I should retweet their work more often. Also there is Design. I like having armchair design opinions, even though I do not practice.

What’s missing? Well, I had no tweets about coding. I like coding, more or less, but I haven’t really found discussing it on Twitter worthwhile. I prefer an in-depth book or article. As an experiment, I am now following more coding folks to see if this year will be any different. Also, no interactions with friends. Noted; will make a better effort this year.

Finally, my favorite tweet of last year is:

> I'm the obscene slang kicker with no parental sticker / Advisin' y'all that wise words is much slicker -GZA
> 
> — Peter Skirko (@pskirko) [June 22, 2017](https://twitter.com/pskirko/status/877996705383305216?ref_src=twsrc%5Etfw)

So there you have it.

### Share this!

*   [Twitter](https://www.pskirko.com/2018/01/12/2017-twitter-year-in-review/?share=twitter "Click to share on Twitter")
*   [Facebook](https://www.pskirko.com/2018/01/12/2017-twitter-year-in-review/?share=facebook "Click to share on Facebook")
*   [LinkedIn](https://www.pskirko.com/2018/01/12/2017-twitter-year-in-review/?share=linkedin "Click to share on LinkedIn")
*   [Reddit](https://www.pskirko.com/2018/01/12/2017-twitter-year-in-review/?share=reddit "Click to share on Reddit")
