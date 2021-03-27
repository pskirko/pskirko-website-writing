# Front Matter

© 2018-2019 Peter Skirko. All rights reserved.

## Revision History

* Version 1.0 - 2019/10/25 - Initial commit (grabbed from website).

This post is also available on my website ([link to
post](https://www.pskirko.com/2018/12/18/why-how-develop-wordpress-theme/)).
Read it there or here; up to you.

# Why and how I started developing my own WordPress theme

![](https://i2.wp.com/www.pskirko.com/wp-content/uploads/2019/10/website_top.jpg?fit=525%2C315&ssl=1)

_The opinions stated here are my own, not those of my company._

tl;dr – I recently (Dec 2018) started a new WordPress theme, Moderately Austere ([GitHub link](https://github.com/pskirko/moderatelyaustere)), as a fork of the Twenty Seventeen [(WordPress link)](https://wordpress.org/themes/twentyseventeen/) theme. Forking an existing theme, instead of starting from scratch, was the best way for me to get started in theme development and customization.

Why did I start developing my own WordPress theme?
--------------------------------------------------

I started developing my own WordPress theme for three main reasons.

The first reason was to fix a problem. Twenty Seventeen uses vh units for some heights (namely, [here](https://github.com/WordPress/twentyseventeen/blob/master/style.css#L1621) and [here](https://github.com/WordPress/twentyseventeen/blob/master/style.css#L3575)). The problem with vh units is that they can cause stutter-y image updates on iOS — [this article](https://medium.com/@heyraimana/how-and-why-i-built-vh-fix-2bc0288eb5af) has a good explanation. There are various workaround hacks and libraries, but I just wanted to simplify things and use fixed heights for now.

The second reason was to explore web design. I’ve been a design spectator for many years, whether it’s web design, classic print design, industrial design, etc. However, if I like something, I generally want to participate and not just be a passive observer. Working on web design for my own site seemed like a great way to do a design project that was immediately beneficial to me.

The third reason was self-expression. Part of the reason of hosting my own site, rather than using Medium or something else, was to make it uniquely my own. That includes how it looks and functions. Existing themes are like pre-furnished apartments: sure, they have furniture, but it’s not your furniture.

How did I start developing my own WordPress theme?
--------------------------------------------------

I started developing my theme by forking, or cloning, the existing WordPress theme [Twenty Seventeen](https://wordpress.org/themes/twentyseventeen/). Many WordPress themes, such as Twenty Seventeen, are fully [licensed under the GPLv2](https://wordpress.org/news/2009/07/themes-are-gpl-too/). That license grants me, you, and everyone else the freedom to modify the original theme and distribute the modified version.

Why didn’t I start a new theme from scratch?
--------------------------------------------

If I were a seasoned web developer, I might create a new theme — templates, CSS styling, etc. from scratch. However, I’m not a seasoned web developer; I’m more of a dabbler who just wants to get particular things done and learn a bit of CSS along the way. Thus, forking an existing theme was the pragmatic path to take. If I had started from scratch, it would have taken me a long time to get a usable theme up and running at all.

The importance of forking
-------------------------

Forking, or replication, is one of the great results of the [Information Age](https://en.wikipedia.org/wiki/Information_Age). Before this era, the primary example of replication was DNA, which is responsible for nothing less than the propagation of life itself. Discovering how DNA works was a [fundamental achievement](https://www.nobelprize.org/prizes/medicine/1962/perspectives/) in science.

Here is Wikipedia on the origins of fork() in operating systems:

> fork() is the name of the system call that the parent process uses to “divide” itself (“fork”) into two identical processes. After calling fork(), the created child process is an exact copy of the parent except for the return value of the fork() call. This includes open files, register state, and all memory allocations, which includes the program’s executable code. In some cases the two continue to run the same binary, but often one (usually the child) switches to running another binary executable using the exec() system call.
> 
> [https://en.wikipedia.org/wiki/Fork–exec](https://en.wikipedia.org/wiki/Fork–exec)

See [this StackOverflow post](https://unix.stackexchange.com/questions/136637/why-do-we-need-to-fork-to-create-new-processes) for commentary on the origins of Fork–Exec: “…it seems reasonable to suppose that it exists in Unix mainly because of the ease with which fork could be implemented without changing much else.”

_Don’t underestimate the power of simple, elegant solutions._

Nowadays, people fork projects on GitHub all the time. And not just code: data, fonts, icons, you name it. Fork, modify, reuse, adapt, evolve. This is a cornerstone of modern productivity in computing and digital tradecraft.

Why the name “moderately austere”?
----------------------------------

Well, that’s how the theme looks to me, and that’s the visual motif I intend to follow.

Conclusion
----------

Forking a theme is a great way to get started in WordPress theme development. Sure, all the hard work of making the theme truly my own is still to come. But that is something I can chip away at one small change at a time.

### Share this!

*   [Twitter](https://www.pskirko.com/2018/12/18/why-how-develop-wordpress-theme/?share=twitter "Click to share on Twitter")
*   [Facebook](https://www.pskirko.com/2018/12/18/why-how-develop-wordpress-theme/?share=facebook "Click to share on Facebook")
*   [LinkedIn](https://www.pskirko.com/2018/12/18/why-how-develop-wordpress-theme/?share=linkedin "Click to share on LinkedIn")
*   [Reddit](https://www.pskirko.com/2018/12/18/why-how-develop-wordpress-theme/?share=reddit "Click to share on Reddit")
