---
title: Science as Algorithm Discovery
layout: post
---

Consider the trial of [Amanda Knox](http://en.wikipedia.org/wiki/Amanda_Knox). What's the purpose of the legal process here? 

Well, let's think about. Here's how a trial works (at least on television): the
prosecution and the defense get up in front of the jury. They present
evidence -- it could be DNA, surveillance videos, witness testimony, or [even a
tic-tac-toe playing chicken](http://www.thisamericanlife.org/radio-archives/episode/452/transcript). Closing
arguments follow. Then the jury deliberates and returns a verdict.

Now, the purpose of all this evidence is ostensibly to get at the truth. To figure out
what it is that really happened. Did Amanda Knox kill Meredith Kercher? Or not?

We can visualize the jury, then, as a sort of machine. It takes in evidence and
then applies that evidence to update two competing hypotheses: guilty or not
guilty. At the end of the trial, the jury spits out its verdict.

![Image of jury inference.](/img/jury-inference.png)

Science works in the same manner.

# What's a hypothesis?

Okay, I haven't been entirely honest. A jury doesn't have just two hypotheses
floating around in its collective head. There are a bunch of different
possible explanations. When they consider the most likely explanation
("someone else did it"), they decide *guilty* or *not guilty* based on that. So
in that box above with the G and NG for guilty or not guilty, it really ought to
contain all possible *explanations*.

What are these explanations, really? They're scenarios which could have produced
the evidence. Amanda Knox murdering Meredith Kercher is one possible
scenario. Rudy Guédé murdering her is another, or maybe Raffaele Sollecito did
it. Or maybe it was aliens or a government conspiracy.

But what's a scenario here, really? Consider the plight of physicists. They're trying to uncover the underlying laws of the universe. They
look at the world as it *is* -- the evidence -- and ask, "What underlying structure produced this?"
Much like a paleontologist who carefully brushes away dirt to reveal a fossil.

Now, what's a structure that produces data, evidence? An algorithm! Physicists are seeking not the laws of the universe, but the
*algorithm* of the universe -- what produced it all. 

**We can think, then, of science as the process of collecting evidence and then
updating the likelihood of possible algorithms that might have produced it.** Science is
the process of algorithm discovery.

![Image of updating hypotheses.](/img/updating-hypotheses.png)

Here the colored circles are algorithms (hypotheses) and their size is their
likelihood.

# Further Reading

* The meat of the idea here, captured by the graphics, is [Solomonoff induction](http://lesswrong.com/lw/dhg/an_intuitive_explanation_of_solomonoff_induction/). 
* The optimal way to update beliefs based on evidence is captured by [Bayes' Theorem](http://lesswrong.com/lw/2b0/bayes_theorem_illustrated_my_way/).
