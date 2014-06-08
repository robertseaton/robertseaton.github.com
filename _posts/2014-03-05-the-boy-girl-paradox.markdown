---
title: Intuition for the Boy or Girl Paradox
layout: post
---

Probability theory is notorious for violating human intuition. Consider the **Boy or Girl Paradox:**

> Mr. Smith has two children. At least one of them is a boy. What is the
> probability that both children are boys?

Answer: <font style="background-color: #222;">Of course, the brain thinks, it
must be one half. Except it isn't. It's one in three.</font>

## Trust, but Verify

If the whole
[Monty Hall debacle](http://en.wikipedia.org/wiki/Monty_Hall_problem#Vos_Savant_and_the_media_furor)
and my sister's reaction ("That's bullshit!") are any indication, though, you will not believe
me. We must force the intuition to see the error of its ways. 

Let's consider a set of 100 pairs of children and assume that it's a perfect,
representative sample. This means that \\(\frac{1}{4}\\) is \\(\(Boy, Boy\)\\),
\\(\frac{1}{4}\\) is \\(\(Boy, Girl)\\), \\(\frac{1}{4}\\) is \\(\(Girl,
Boy)\\), and \\(\frac{1}{4}\\) is \\(\(Girl, Girl\)\\). 

Visually:

!["Picture of pairs in the Boy Girl Paradox."](/img/boy-girl-paradox-1.png)

We don't need to consider double girl sets, since the problem specifies at least
one child is a boy. 

!["Picture of pairs in the Boy Girl Paradox, without girl pairs."](/img/boy-girl-paradox-2.png)

From the image, we can see that there are twice as many boy-girl pairs
than double boy pairs -- giving us \\(\frac{1}{3}\\).

!["Picture of solution to the Boy Girl Paradox."](/img/boy-girl-paradox-3.png)

Examining this problem suggests a more general heuristic: 

**Heuristic:** *When considering a probability problem, consider all possible
  permutations. Draw a picture.*

## The Other Problem

Usually, the problem is presented as a pair of problems, the second of which is:

> Mr. Jones has two children. The older child is a girl. What is the probability
> that both children are girls?

Answer: <font style="background-color: #222;">This time it is one half. Can you see why?</font>

Consider the original image again:

!["Picture of pairs in the Boy Girl Paradox."](/img/boy-girl-paradox-1.png)

Then eliminate all pairs where the eldest child is not a girl:

!["Picture of eldest girl child pairs in the Boy Girl Paradox."](/img/boy-girl-paradox-4.png)

\\(\frac{1}{2}\\) of the pairs are \\(\(Girl,Girl\)\\).

## Debugging the Intuition

[When MBA students were presented with the first problem](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.99.1889&rep=rep1&type=pdf), 83% of them gave an
answer of \\(\frac{1}{2}\\). Why is this so tempting? Why does intuition
lead us astray?

I've heard that teachers consider wrong answers on tests to be valuable
feedback. They can see the sort of errors that children make and iron out the
conceptual bugs, so to speak. Consider the process of coming up with wrong
answer to the first problem. When I worked through
it the first time, I thought, "Well, I know that one child is a boy, so there's
a 50% chance that the other child is a boy." The trouble with this is that it
implicitly fixes the first child as a boy -- like the second problem does -- but
this is not a valid move.

[Fox and Levav](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.99.1889&rep=rep1&type=pdf) argue that people have a faulty heuristic in their head, that
works like this:

**Faulty Heuristic**: *People split up the sample space in the simplest way
  necessary to accommodate the problem's parameters.*
  
In the boy or girl paradox, the simplest way of splitting up the problem space
-- whether or not there are two boys -- is by halving it. 

Finding the correct answer to the problem feels different. It's more of a,
"Wait, what are all the possibilities?" followed by listing them out, \\(\(Boy,
Boy\)\\), \\(\(Boy, Girl\)\\), \\(\(Girl, Boy\)\\), \\(\(Girl, Girl\)\\). Once
that's done, the final step is taking care not to eliminate \\(\(Girl,
Boy\)\\) by falsely assuming that only those in which \\(Boy\\) comes first are
valid, at which point the solution is a matter of counting. This is much easier to avoid when everything is out on paper than it is
when considering it mentally.

The trouble with the intuition may just be that it is too quick to compress the
space of possibilities -- "It can either be \\(Boy\\) or \\(Girl\\)!" thinks the
fast, [system one](http://en.wikipedia.org/wiki/Dual_process_theory) processor. By slowing it down, listing out all the possibilities,
and only throwing out those that don't apply -- \\(\(Girl, Girl\)\\) -- we avoid
that failure mode and arrive at the right answer. 

## Further Reading

* If you enjoyed this, you may enjoy my articles on
  [the secretary problem](http://rs.io/2014/03/03/the-secretary-problem.html),
  on
  [the science of problem solving](http://rs.io/2014/02/21/problem-solving.html),
  and maybe
  [Jürgen Schmidhuber's theory of creativity](http://rs.io/2014/02/22/ju%CC%88rgen-schmidhuber-creativity.html).
* If you're still unconvinced, Wikipedia has more information on [the Boy or Girl paradox](http://en.wikipedia.org/wiki/Boy_or_Girl_paradox).
* The canonical example of a counterintuitive probability problem is [The
  Monty Hall Problem](http://en.wikipedia.org/wiki/Monty_Hall_problem#Vos_Savant_and_the_media_furor),
  which tripped up even Paul Erdős. Wikipedia has a
  [list](http://en.wikipedia.org/wiki/Category:Probability_theory_paradoxes) of others.
