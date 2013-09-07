---
title: Incompleteness and Halting
layout: post
---

Yesterday, while googling around for information on [hyperoperations](http://en.wikipedia.org/wiki/Hyperoperation), I came across Scott Aaronson's essay, ["Who can name the bigger number?"](http://www.scottaaronson.com/writings/bignumbers.html) You should go read it. I'll wait.

On the halting problem:
> The proof is a beautiful example of self-reference. It formalizes an old argument about why you can never have perfect introspection: because if you could, then you could determine what you were going to do ten seconds from now, and then do something else. Turing imagined that there was a special machine that could solve the Halting Problem. Then he showed how we could have this machine analyze itself, in such a way that it has to halt if it runs forever, and run forever if it halts. Like a hound that finally catches its tail and devours itself, the mythical machine vanishes in a fury of contradiction.

What if we could solve the halting problem? On hypercomputation:
> Suppose we could endow a Turing machine with a magical ability to solve the Halting Problem. What would we get? We’d get a ‘super Turing machine’: one with abilities beyond those of any ordinary machine. But now, how hard is it to decide whether a super machine halts? Hmm. It turns out that not even super machines can solve this ‘super Halting Problem’, for the same reason that ordinary machines can’t solve the ordinary Halting Problem. To solve the Halting Problem for super machines, we’d need an even more powerful machine: a ‘super duper machine.’ And to solve the Halting Problem for super duper machines, we’d need a ‘super duper pooper machine.’ And so on endlessly.

Wikipedia's [hypercomputation page](http://en.wikipedia.org/wiki/Hypercomputation) is silent on the super Halting Problem. Is this the work of the hypercomputation illuminati, trying to supress an inconvenient truth?

Then it ocurred to me: the structure of the super Halting Problem is virtually identical to the "Contracrostipunctus" dialogue in *Gödel, Escher, Bach*, in which the Tortoise tells Achilles about his collection of phonograph-destroying records. The super Halting Problem can be thought of as a record that cannot be played on a super Turing machine, which makes one wonder: what is the relationship between [the incompleteness theorems](http://en.wikipedia.org/wiki/G%C3%B6del%27s_incompleteness_theorems) and the halting problem? Some googling suggests that there [is some category theory underlying both of these](http://cstheory.stackexchange.com/questions/10635/halting-problem-uncomputable-sets-common-mathematical-proof/10636#10636). [This paper](http://xxx.lanl.gov/abs/math.LO/0305282) looks like a promising introduction. 
