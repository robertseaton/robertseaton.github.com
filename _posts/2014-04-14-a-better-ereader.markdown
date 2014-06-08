---
title: Response to BasicBookReader
layout: post
summary: "Features for a better book reader."
description: "Features for a better book reader. Response to Austin G. Walters BasicBookReader project."
---

How can e-readers be improved? This is a response to Austin G. Walters [BasicBookReader project](http://austingwalters.com/basicbookreader/).

## Features For Authors

Better feedback for authors. When seeking feedback on a draft of something,
authors want analytics. Where does someone stop reading?
If someone puts down your book at a certain page, that's a page that ought to be
rewritten. You've bored them enough that they've decided to stop reading.

After all, an author -- at least of fiction -- is aiming at creating an
addicting product. You want to write something that people can't put down, the
sort of book that people stay awake late into the night reading. Notice that
this is what popular websites (Facebook, Reddit) have in common: they're
addicting.

I expect, though, for an author to get really useful feedback, they're going to
need quite a few "test" readers. Otherwise, the signal will get drowned in noise
-- maybe someone places a book down because the phone rings, etc. (Heh, noisy data
caused by literal noise.) But with lots
and lots of test readers, the law of large numbers should kick in, and you'll be
able to objectively identify boring passages.

### Extending online analytics

The current generation of cutting edge analytics are being applied to the
web. These could, in principle, be extended to books read on a screen. Take AB
testing for instance. Maybe some readers get a version of the original
book. Others get a version with the "stopping points" rewritten. Which version
are people more likely to finish?

With enough such trials, a mediocre book can be pounded and shaped, like a
blacksmith would iron, into something *great*. 

I suspect there are other techniques that could similarly be lifted from website
analytics.

## Features for Readers

### Export highlights as text

One of the more powerful features of Skim is the ability to export highlights
from PDFs as text. I then save these annotations and can search through them via
`grep` whenever I'm looking for a piece of evidence that I vaguely recall.

![Picture of grepping through notes.](/img/grep-through-notes.png)

### Autoscroll

I've spoken with people who say that they're able to read more if the page
automatically scrolls -- this forces them to maintain attention of the book in
front of them. I've been unable to duplicate this success, but it seems
plausible. 

### Bookmarks

A useful feature in academic texts is the ability to save one's current position
in order to look up a citation or footnote. You might need to skip ahead 100 or
so pages or whatever, so you want to be able to quickly jump back and forth.

Allowing a "split screen" where you can view two pages at once is similarly
useful. 

### Analytics for readers

Are there any useful analytics for readers? It's hard to think of any. You might
correlate time of day with pages per minute, or something. These analytics could
help identify when one's at an intellectual peak. Words per minute might be
similarly useful. 

It's hard to think of any other information someone might find useful. The
Kindle has a feature that automatically highlights popular segments of a text
purchased through them. It's entertaining, but I'm not sure how useful.

Graphs of pages per day, total pages, and books read are, at the very least,
inspiring. 

### Beauty

Intersecting that readability.com could build a business around taking ugly
websites and making them beautiful, eh? This seems like a place where a newcomer
could win over established players. When given text or ePub, the reader could
lay it out is some pleasing form. 

The styling could be tweaked in some form of AB testing, figuring out what's
most conducive to long reading sessions.

### Saving book locations

If the app crashes or my computer does, I'd like to be able to restore exactly
where I left off reading. It's also useful to have a "farthest page read"
marker in case something goes wrong. I find I'll often press the wrong key on
the Kindle and lose my place. 

### Fast dictionary look up

A means to quickly figure out what a word means would be useful.

### Table of contents sidebar

The largest advantage print books still have over electronic ones is that it's
easy to figure out the structure of a print book at any time. You keep one
finger stuck in the page you're on and flip to the table of contents, or to the
next chapter.

As far as a I know, no software has successfully replicated this yet. Skim
contains a sidebar, like so:

![Picture of Skim sidebar.](/img/skim-sidebar.png)

Unfortunately, this feature breaks down when a PDF doesn't ship with table of
contents metadata.

