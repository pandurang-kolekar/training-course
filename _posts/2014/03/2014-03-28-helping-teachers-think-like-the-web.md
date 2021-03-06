---
title: Helping Teachers Think Like the Web
author: Greg Wilson
permalink: /2014/03/helping-teachers-think-like-the-web/
categories:
  - Opinion
---
I've talked elsewhere about PowerPoint, version control, and the lack of open collaboration in education, but this exchange took place on Twitter a few days ago has got me thinking about it again:

> A: Somebody should make GitHub for PowerPoint. Why is that not a thing?
> 
> Me: We have a GitHub for PPT: it's called GitHub <img src="http://localhost:8080/wp-includes/images/smilies/icon_smile.gif" alt=":-)" class="wp-smiley" /> What we lack are the diff/merge tools to make it usable...
> 
> B: Use a text-based slide program, latex and beamer :-p
> 
> A: Or I could chisel slides from stone tablets. Not sure which would be more pointlessly difficult.
> 
> B: I am quite speechless in front of such lack of knowledge of the tools and shortsightedness #wtf

With all due respect to B, A and I are actually fairly knowledgeable: we just have different priorities. Text formats like LaTeX, HTML, Markdown are great for making slides full of bullet points—the kind Edward Tufte decries in [this widely-cited essay][1]—but we know that's a poor way to communicate. It's much easier to create a stop-motion series of vignettes of what you'd draw on a whiteboard using PowerPoint's WYSIWYG writing-and-drawing interface than it is to put markup in one file with an editor, draw images with some other tool, and then stitch the two together. Even a relatively impoverished slide, like this one from the Software Carpentry lesson on dictionaries:

![Example Slide][2]

is bloody difficult to make that way, and even harder to maintain.

So why do so many technophiles advocate text tools for slides, papers, and other artefacts? The answer, I think, is that they value ease of maintenance and sharing over comprehensibility. PowerPoint and its equivalents don't play nicely with version control systems because there's no way to diff and merge slide decks, which makes it really hard to collaborate on them with other people, including your future self. As programmers, we *know* that version control is the right solution for document management. What we choose to brush aside is that those text formats discourage people from authoring good slideshows.

All of this ties back to a question I've been asking for a couple of years now:

> Why is there so little open, collaborative development of teaching materials? What makes teaching different from open source software and Wikipedia?

Thousands of people have contributed code to Firefox, and some Wikipedia articles have had hundreds of contributors. In contrast, I've never seen a lesson that had more than half a dozen authors, and they almost always worked sequentially (i.e., one person wrote the original version, someone else inherited it and updated it, someone else tweaked it again, and so on). My question is, why not?

Justin Kitzes [speculates][3] that collaboration doesn't happen because educators aren't comfortable enough with the tools, but I don't buy it: I'm sure many teachers have contributed to Wikipedia. Other people have suggested that teachers simply don't want to share, or aren't rewarded for doing so, but I don't buy those arguments either: the first two are equally true of programmers and open source software,

And I don't believe the problem is one of narrative, either. A good lesson isn't just a bunch of facts and opinions presented one after another: it has a story that ties those together, and some people believe that committees can't create great stories. Again, though, the same argument ought to apply to Wikipedia articles, but its [essay on the causes of the American Civil War][4] is certainly readable "despite" having had 1093 distinct contributors.

One final argument is that collaboration doesn't work because every class is different. This doesn't feel right either: there are only so many ways to teach algebra and Shakespeare to high school students and freshmen, and to borrow an analogy from Ted Gioia's wonderful essay [The Aesthetics of Imperfection][5], playing from the same score doesn't mean we can't all improvise in our own unique ways.

The only answer I'm left with is, "I don't know." What I *do* know is that open collaboration is more likely to improve education than the combination of web TV, robo-grading, and ubiquitous surveillance currently known as "MOOCs". Software Carpentry's mission is to teach researchers lab skills for scientific computing, but it's also my way of figuring out what we can do to help teachers [think like the web][6].

 [1]: http://www.edwardtufte.com/tufte/powerpoint
 [2]: http://software-carpentry.org/v4/setdict/phylogen/032.png
 [3]: http://software-carpentry.org/blog/2014/03/collaborative-lesson-development.html
 [4]: http://en.wikipedia.org/wiki/Causes_of_the_American_Civil_War
 [5]: http://files.software-carpentry.org/training-course/2014/03/The-Aesthetics-of-Imperfection.pdf
 [6]: http://blog.jonudell.net/2011/01/24/seven-ways-to-think-like-the-web/
