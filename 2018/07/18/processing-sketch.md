# Front Matter

© 2018-2019 Peter Skirko. All rights reserved.

## Revision History

* Version 1.0 - 2019/05/07 - Initial commit (grabbed from website).

# My first Processing sketch

tl;dr – Here’s my first real Processing sketch:

![](https://i1.wp.com/www.pskirko.com/wp-content/uploads/2018/07/Sketch001.png)

I’ve been meaning to learn [Processing](https://processing.org/) for quite
awhile now. How long, you ask? It’s hard to remember when I first learned about
Processing, but let’s assume it’s been almost a decade. I used openFrameworks
as part of a short contracting assignment in 2009, and I vaguely recall
researching the complementary technologies at the time. However, I’m not sure I
ever downloaded a version to try until version 2 came along.

The reasons for taking so long to really dig into Processing are many, and not
all are relevant to this post. But there is one really good idea worth
addressing, the idea of _sketching:_

> It is necessary to sketch in a medium related to the final medium so the
> sketch can approximate the finished product… Processing is built to act as a
> software sketchbook, making it easy to explore and refine many different
> ideas within a short period.— from “Processing: A Programming Handbook for
> Visual Designers and Artists” (2014)

Sketching is most commonly associated with arts such as drawing and painting.
Most artists know how to sketch, and good artists know how to sketch quickly
and effectively.

Sketching in code outside of the arts is a mixed bag. I’d loosely hypothesize
that many professional software engineers don’t consider sketching (or
prototyping, experimenting, etc) a conscious, first-class part of their
toolkits. But this varies wildly by domain. For example, data scientists often
work in [Jupyter](http://jupyter.org/) notebooks, which allow for quickly and
interactively trying out small snippets of code and chaining these snippets
together to build something bigger, one idea at a time. To me, this is very
much akin to sketching. And the Rails community has long prided itself on its
[scaffolding](http://guides.rubyonrails.org/command_line.html#rails-generate)
functionality, which makes it easy to get chunks of a web app working and on
screen with minimal effort.

Once upon a time circa early 2000’s, I was quite adept at “sketching” in
Matlab. I could quickly ingest and plot data and write algorithms to try things
out. These days, the same thing can be achieved with Python, Jupyter, and
matplotlib, so the dominant tools change over time, whereas the underlying
practice keeps maturing.

Sketching, prototyping, experimentation—the more quickly and fluently you can
try an idea out before committing, the better you will be at your craft. I
didn’t learn how to sketch in Matlab because that’s what they taught me to do
in school. I learned out of necessity to get certain kinds of work done,
without busting out Java or C++ at the time. That said, huge kudos to the
Processing folks for making sketching a first-class principle in the learning
process. The more people that really internalize it, the better.

The reason I mention sketching here is that, while I have felt reasonably
comfortable sketching in code for non-artistic uses, the idea of sketching in a
creative sense eluded me for a long time. Every time I thought about starting
to learn Processing, I always started thinking about elaborate, grandiose
projects off the bat. I’d then fail to connect how to get from simple beginning
to grand ambitions, get deterred, and move on. I’m sure the same thing happens
to many people when they learn traditional coding, and so i can empathize.

However, for many reasons, now I can understand and use sketching in the
creative domain for what it is: exploring, trying thing out, letting happy
accidents run their course, working quickly, not getting caught up in any
predetermined final result, yet still working deliberately, with an eye towards
consistency, developing quality “in the small”, and building up fundamental
knowledge and skills that will serve me well later. That, to me, is the essence
and value of sketching; it took me a long time to really wrap my head around
it, but I “get it” now.

That said, accepting sketching into my life at a broad, conceptual level was
only part of the effort. There were other practical details to wrangle before
making meaningful progress. Sketching in code is only loosely analogous to
sketching on paper. For example, even if you are a beginning artist, you can
sketch out crude shapes from real life: apple, cat, etc. However, Processing
does not offer _direct manipulation _(unless you build the functionality
yourself using mouse and key events). You can’t really “sketch” an apple in
Processing in the most literal sense. You’d have to translate from a visual
sense of an apple to the coordinates of Bezier curves or a polygonal line in
your head. That very act of translation defeats the spontaneity of sketching.
To “draw” apples in Processing, if that’s what you want to do, you have to be a
bit more creative: either import apple assets and manipulate them, or try
different curve shapes until you find one that’s apple-like, and so on. Some of
these exercises might even be quite fun, but they are inherently _different_
than the kind of sketching that happens in a notebook.

Personally, I like to think of Processing as working at a higher level of
abstraction. You could call it a “creative manipulation” tool, but that’s an
awkward term. Now of course everyone will use the tool differently. But really,
unless you are doing generative art where the form “emerges” from rules of
varying complexity, you either need to import assets from outside the app, or
build your own direct manipulation tools inside the app.

Now all that might be true, but it’s a bit jarring and off-putting to think
about when you’re just wanting to learn. Most Processing tutorials start with
the most basic primitives: lines, circles and other simple shapes, and the
like.

Starting with such simple primitives is itself not always inspiring, especially
if you are not already grounded in other art practices. But there’s a few ways
to spice things up. One approach is to take inspiration from various branches
of art that apply such simple geometric objects. [Casey Reas did this early on
when he explored sketches inspired by Sol Lewitt’s Wall
Drawings](http://artport.whitney.org/commissions/softwarestructures/text.html).
This too is a great idea for many reasons: it gives you something immediately
achievable, it ties your initial efforts into a more established line of
thinking, it allows you dial in how much you follow the original idea vs
striking out on your own, etc.

In my case, I picked another fairly obvious inspirational choice in Mondrian.
My inspiration was [New York City
I](https://www.piet-mondrian.org/new-york-city.jsp). However, as a first
sketch, I decided to keep it simple: two horizontal lines and two vertical
lines, one red and one blue in each direction. The positions are randomly
chosen. A single image was a bit boring, so I made a 2 x 2 grid. This is more
interesting, because now your eye can jump around as it compares the
relationships between the sub-images. Also, every time I clicked, a new set of
positions were chosen. The red and blue are loosely taken from the original,
but I just picked some initial RGB values and then nudged them til they looked
good together.

So there you have it, a sketch, nothing more and nothing less.

![](https://i1.wp.com/www.pskirko.com/wp-content/uploads/2018/07/Sketch001.png)
