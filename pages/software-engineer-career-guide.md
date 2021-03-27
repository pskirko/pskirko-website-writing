# Front Matter

© 2021 Peter Skirko. All rights reserved.

## Revision History

* Version 1.0 - 2021/03/27 - Initial commit (grabbed from website).

# Software Engineer Career Guide

![](https://i0.wp.com/www.pskirko.com/wp-content/uploads/2019/02/parachute.jpg?resize=525%2C272&ssl=1)

Image courtesy of NASA Commons

### Articles

[5 principles for managing and optimizing your tech career](https://www.pskirko.com/2021/03/26/5-principles-managing-optimizing-tech-career/)

[For me, coding outside of work is not a “hobby”, it is a regimen akin to going to the gym](https://www.pskirko.com/2019/02/02/coding-as-a-hobby/)

Intro

Please note: This page is currently stuck in an editing-but-not-done state (I edit right on the live page, usually), so the narrative doesn’t flow as lock-step as I would prefer. With any luck, I’ll finish cleaning it up by the end of the year, but for now, thanks for your patience.

This page collects my best advice on a career in software engineering and related fields. I hope you find some of it useful.

I use the term “software developer” since that’s what I do and know (and will continue to do for the foreseeable future). The jobs, and corresponding titles, in our broader IT field vary wildly: software engineer, web developer, devops specialist, database admin, etc. That said, I’m sure some of what I say below will apply narrowly, and some things will apply more broadly. I’ll try to provide descriptive titles, but otherwise you can decide for yourself.

Links to specific articles are provided below, after the Preface.

### Preface

I have been a professional software engineer from 2002 to the present (2019), and in that time, the number and types of work roles that involve writing code to solve problems or otherwise “do stuff” has grown by a heck of a lot. Consider a few key examples:

*   The rise of Javascript (and the web as a platform, really) to become the world’s most used programming language (according to the Stack Overflow [Developer Survey](https://insights.stackoverflow.com/survey/2018#technology-programming-scripting-and-markup-languages)). This era started with the “web app [heard ’round the world](https://www.dictionary.com/browse/shot-heard-round-the-world)” [arrival of Google Maps in 2005](https://en.wikipedia.org/wiki/Google_Maps), which pretty much blew everyone’s mind with its use of AJAX to facilitate an actual _interactive, real-time, and visually rich_ app in a browser, rather than just the standard forms-based websites of the day (of which Google Search itself was one, useful and lucrative as it was then and now).
*   There have always been people doing Data Science (e.g. in finance companies, research labs, etc) since the birth of the modern computer, all the way back to [ENIAC](https://en.wikipedia.org/wiki/ENIAC) (I get the feeling many people think Data Science is largely prediction and inference, but I believe simulation to be a critical third pillar). In college, I was pretty comfortable in Matlab. But things really exploded when open source packages, mostly for R and Python, really matured and became easy to get, use and learn (especially in interactive notebook environments like Jupyter). That, coupled with the rise of Cloud Computing and Big Data, led us to where we are today, where being a Data Scientist is a useful and coveted role.
*   Similarly, the rise of “coding bootcamps” as alternatives to a “classical” university or college education in Computer Science or Electrical Engineering, especially for people transitioning from another background, often to get a better paying job or more promising career track.

And so on. Just like the rapper Drake called his playlist-album [More Life](https://en.wikipedia.org/wiki/More_Life), you could describe the above trend as “More Code”. And my personal frame of reference doesn’t even cover two full decades. In 2002, Google had not yet IPO’d, “Zuck” was just starting university ([FaceMash](https://en.wikipedia.org/wiki/History_of_Facebook) is dated to July 2003), and to most people (in the US at least), “using a computer” meant using a Windows desktop machine. Goldman Sachs [estimated](https://www.forbes.com/sites/timworstall/2012/12/13/microsofts-market-share-drops-from-97-to-20-in-just-over-a-decade/#5dc2713651cf) that Microsoft’s effective (personal computing) market share dropped from 97% in 2000 to 20% in 2012. These precipitous changes don’t happen all in one day, but the decade-centric rate of change is pretty incredible.

Furthermore, the world has not even remotely reached a saturation point, or “[Peak Code](https://en.wikipedia.org/wiki/Peak_oil)” if you will, in the demand for code and coders. Technologically, there is no such limit, as there are always more problems to tackle (and I’m skeptical of [General AI](https://en.wikipedia.org/wiki/Artificial_general_intelligence) any time soon), although economically most of us are at the mercy of the [economic machine](https://www.youtube.com/watch?v=PHe0bXAIuk0), with its All Too Human cycles of leveraging and deleveraging of capital), and so _how many_ people are paid to code will vary over time. If you don’t think “highly” skilled labor markets can saturate, consider what started happening to lawyers [a few years back](https://dealbook.nytimes.com/2014/12/17/law-school-enrollment-falls-to-lowest-level-since-1987/).

![](https://i0.wp.com/www.pskirko.com/wp-content/uploads/2019/02/pitfall_cover.png?resize=252%2C327&ssl=1)

Pitfall!, the classic Atari game

Thus, it seems safe to say that, for the next 20-30 years at least, being a software engineer of some kind is still a promising career choice. At the same time, there are many pitfalls along the way.

Consider career satisfaction. In the [Stack Overflow Developer Survey again](https://insights.stackoverflow.com/survey/2018#work-how-do-developers-feel-about-their-careers-and-jobs), 44.8% of respondents answered in the range from “extremely dissatisfied” to “slightly satisfied” (correspondingly, 55.2% reported being moderately or extremely satisfied). I naively expected closer to a 40/60 split; perhaps something’s up.

Furthermore, 33.9% responded that they wanted to be working in a different or more specialized role in 5 years; 59.8% are open to new job opportunities; and 15.9% are actively looking for a new job. Mobility is part of any encouraging labor market, but again, these numbers all trend higher than I expected.

The main inference I draw from those data points is that, if you want to have, or increase, happiness in _your_ programming-related career, you have to actively work at it. Maybe some people get lucky and everything works out for a long time. But the above data points tell me that there is a nontrivial group of people perpetually looking for a “better” thing (maybe even [The Real Thing](https://www.youtube.com/watch?v=I625zPMQ4r4)).

In my case, career satisfaction has really been a multi-dimensional concern, so boiling it down to a single scalar stat glosses over some important distinctions, and furthermore, over time some dimensions increase, some flatten out, and some hit bumps in the road. More on this later.

Consider also which technologies to learn. Actually, consider just languages for a moment. Some languages, like C and C++, have had an enduring lifetime and are still relevant, and even actively sought after, today (in the right role). Javascript is hot now, but will it have a 30 year run too? Others, like Perl, have not aged gracefully. Or look even further back and consider COBOL, which is effectively dead but runs enough critical stuff that “[COBOL Cowboys](https://www.reuters.com/article/us-usa-banks-cobol/banks-scramble-to-fix-old-systems-as-it-cowboys-ride-into-sunset-idUSKBN17C0D8)” have emerged to save the day for “$3 trillion in daily commerce flows through COBOL systems” since, let’s face it, most of us aren’t going to step in and learn it.

Finally, consider recessions. Depending on how young you are (and what country you live in), how many recessions have you lived through as an employed adult? For me (in the US), I caught the tail end of the Dot Com Bust in 2002, and felt the pain during the Great Recession of 2007-2009. Ever tried getting a job during a recession, when suddenly there’s 10x as many applicants for any given role, and when most companies basically stop hiring save for critical replacements? Yea, not fun.

And so on. Like I said, there are many pitfalls in crafting a career, _your_ career, in programming. And I am but one data point, but at least I’m a data point that writes and shares it on the Web. Whether you consider me “successful” or not, and to what degree, may very well depend on a lot of things: your background, goals, interests, expectations, peer group, etc. But I can share what I know, and it if helps someone, great! I actually find most “advice” from successful people to be functionally useless. Really, what helps is getting into nitty-gritty details, or deep into concepts, not broad click-bait-y generalizations peppered with a quote here or loose example there.

This is a long preface, which is intentional. I know so much of modern content and media on the Web is focused on the quick fix. But I rather cater to an audience of “deep divers”, e.g. the people who listen to the entirety of 2+ hour podcasts, and who read whole articles, not just skim the headlines. If you’re looking for lite fare like “top 20 programming languages to learn in 2019”, there’s plenty of that elsewhere. Maybe it’s useful as a “pulse” on current trends, but that’s a pretty shallow pond to dive in.

Coming soon! For now, the Preface should have sparked some important lines of thought for you.

### Share this!

*   [Twitter](https://www.pskirko.com/software-engineer-career-guide/?share=twitter "Click to share on Twitter")
*   [Facebook](https://www.pskirko.com/software-engineer-career-guide/?share=facebook "Click to share on Facebook")
*   [LinkedIn](https://www.pskirko.com/software-engineer-career-guide/?share=linkedin "Click to share on LinkedIn")
*   [Reddit](https://www.pskirko.com/software-engineer-career-guide/?share=reddit "Click to share on Reddit")
