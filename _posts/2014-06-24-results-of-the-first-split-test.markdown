---
title: Results From The First Split Test
layout: post
---

> Measuring gives you a leg up on experts who are too good to measure.
<span id="quote-attribute">—Walter Bright</span>

If you've been following along via email (and if not, you should be: [subscribe
here](http://eepurl.com/Ufpgr)), you understand that my current philosophy of site growth is to focus on
long-term readers. Social traffic is easy to obtain, but oh-so-fleeting. By concentrating on returning visitors, I can build a sort of relationship
with you, the gentle reader, and focus on consistent, steady growth,
instead of the occasional dizzying flurry of activity when something takes off
on Reddit. (Plus
[repeated interaction makes people nicer](http://rs.io/2014/02/26/why-online-communities-decay-over-time.html).)

Not that there's anything wrong with these flurries of social traffic. They're
sort of like steroid injections. They keep the site strong but, at anything
except the most unreasonable levels of abuse ([Mike Tyson anyone?](http://rs.io/2014/03/16/mike-tyson-and-steroids.html)), the bulk of
performance is the result of typical training activities.

Or something. Not my best metaphor ever.

As I see it, there are two ways that readers consistently engage with a site's
content: via an email subscription or an RSS feed. Well, okay, maybe two was a
lie. I bet there are at least six: Those two just mentioned, people who follow the site via
Twitter, those depraved individuals who have adopted the strategy of
visit-once-in-a-while-and-refresh, and so on.

But primarily, there are the two means: RSS and email. And people, thus far
anyways, engage a lot more with email than with RSS, plus some dozen-ish other
benefits: Much better analytics, I can make emails a bit more personal, I can
assume that email subscribers have a bit better idea of who I am and what I'm
about, and so on. RSS feeds are more limited.

So, in pursuit of this goal of converting strangers into friends, I'm running a
series of split ("AB") tests to see whether different site changes improve the
rate at which people subscribe via email. The basic idea: some
people see one version of the site, other people see another. After I've
gathered enough data, I should have a pretty rigorous idea about which is
better.

And, given that we're all good empiricists here (as I
[mentioned before](http://rs.io/2014/05/16/woah-dangerous-jobs.html)), with a
firm belief in the virtue of actually, you know, testing our beliefs, AB testing is like
the bare minimum we ought to be doing in order to persuade ourselves that we're
not fit to be crowned the king of hypocrites.

## The First Test

The popular wisdom, that I've had shunted into my brain via [Patrick McKenzie's
podcasts](http://www.kalzumeus.com/category/podcasts/) (recommended) is that you ought to trade an incentive for someone's
email. I figure there are two ways to frame it: one is sorta predatory, like
putting some cheese beneath a box propped up by a stick and catching an angry
badger, or the more noble way of thinking about it, which is as a free exchange
of value between parties. You receive updates and other valuables, I get an
email address.

Or maybe it's more like when your mom would promise a trip to the toy store if
you'd just swallow some damn cold medicine.

So, anyways, on the heels of the success of
the [100+ Interesting Data Sets For Statistics post](http://rs.io/2014/05/29/list-of-data-sets.html),
which is the most popular thing I've yet to write, I figured, hey,
maybe the bad drawings resonated with people. I will promise people some more of
those if they sign up.

And, off I went, spending way too much time figuring out how to set up a split
test with Jekyll, and debugging some not-quite-right analytics code. (The bug
boiled down to forgetting to copy and paste my user ID. Whoops. I look forward to the
day that we obsolete humans.)

And, finally, ladies and gentleman of the jury (but, judging by the site
analytics, mostly gentleman), I got to the point where users would see either
exhibit A or exhibit B.

![Picture two options from the first AB test.](/img/ab-test-1.png)

## Results

So, what happened?

First, I gained a more intuitive appreciation of the phenomenon where, when studying
small effects, you need a lot of data to figure anything out. Over the past two
weeks, about 15,000 unique visitors viewed each option, which still wasn't enough to reach
statistical significance.

I terminated the test anyways. With 43 subscribes to exhibit A and 35 to exhibit
B, promising people bonus drawings increased conversions by about 23%,
probably. [This calculator](http://getdatadriven.com/ab-significance-test) spits
out a confidence value of 82% and, given that our prior belief says that
promising people stuff = more conversions, we can be a little more confident
than that.

So I'm convinced. On to the next set of tests!

## Further Reading
* You, (yeah, *you*) should [subscribe via email right now](http://eepurl.com/Ufpgr).
* I once wrote
  [a post on the decay of online communities](http://rs.io/2014/02/26/why-online-communities-decay-over-time.html),
  which hints at why its important for a set to have a stable set of regulars that engage with each
  other. 
* To the extent that I'm not stumbling around in the dark here, it's from what
  I've learned via [Patrick McKenzie's writings on AB testing](http://www.kalzumeus.com/category/ab-testing/).
