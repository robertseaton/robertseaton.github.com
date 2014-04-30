---
title: Why Category Theory Matters
layout: post
summary: "Why are people excited about category theory? What is it? Why is it important?
What's the big deal? What are some applications of category theory? This article
answers these questions."
description: "Why are people excited about category theory? What is it? Why is it important?
What's the big deal? What are some applications of category theory? Answers to
these questions."
---

> I hope most mathematicians continue to fear and despise category theory, so I
> can continue to maintain a certain advantage over them.
<span id="quote-attribute">—John Baez</span>

!["Picture of the growth of category theory, from google n-grams."](/img/growth-of-category-theory.png)

The above is a graph of the number of times the phrase "category theory" has been
used in books, from about 1950 through the present. It speaks for itself.

But why? What's the big deal? Why does category theory matter? I'm about a
quarter of the way through *Conceptual Mathematics: A First Introduction to
Categories* and still not sure why I'm bothering with fleshing out all this theory. Is
this just set theory for hipsters?

# What category theory is about

Category theory is, essentially, the study of mathematical structure. It's the
study of things and the mappings between those things, the translations of these
objects. These are usually called objects and morphisms (or
arrows, if you prefer). Objects can be thought of as sets and arrows as
functions, though they are not limited to this interpretation.

!["A picture of objects and arrows in category theory."](/img/category-theory.png)

The subject's major insight is, in order to understand something, focus on the
structure persevering mappings of that something -- the legal translations.

# What the excitement is about

> The vast applicability and expressiveness of category theory leads to the
> observation that most structures in mathematics are best understood from a
> category theoretic or higher category theoretic viewpoint. 
<span id="quote-attribute">—<a href="http://ncatlab.org/nlab/show/category+theory">nLab</a></span>

Category theory is one of, if not the most, abstract fields of mathematics. It's
even been dubbed, as one might tease a younger sibling, "abstract nonsense."
After all, the field throws out all the specific properties of objects and
instead focuses solely on their translations.

This extreme generality of category theory means that it can say something about
anything, but nothing too specific. In other words, part of the growth of
category is probably because you can use it to talk about damn near
anything. (See the applications below for examples.)

In this respect, category theory is like set theory. The popularity of set
theory is a result of the fact that, hey, it's a pretty good language for talking
about a lot of different types of mathematics. Most things can be formalized as
a combination of sets and first order logic, and it's not *that* unnatural to
think in terms of sets so, bam, popularity.

In *Categories for Software Engineering*, the authors put it this way: "The way we like to present category theory is as a toolbox similar to set
theory: as a kind of mathematical lingua franca in the sense that it can be
used for formalizing concepts that arise in our day-to-day activity."

This generality mirrors the difference between strong and weak methods
in artificial intelligence. General methods, while widely applicable, don't
typically scale up to hard problems. Instead, specialized tools are necessary. In the same way, category theory is more of
a tool for elucidating connections between mathematical structures than for
solving problems -- in contrast with something like linear algebra, or really
any field of applied math.

## Benefits of category theory over set theory

> God made the integers, all the rest is the work of man.
<span id="quote-attribute">—Leopold Kronecker</span>

To be honest, I don't like set theory. It's artificial -- the axioms aren't
obviously true, but rather the product of a search for a paradox-free foundation for
mathematics. It's sort of complicated, maybe
not at the lowest levels, but definitely once you try to build up something like
the real numbers. (A [2008 issue](http://www.ams.org/notices/200811/tx081101370p.pdf) of the AMS reports, "...to expand the
definition of the number 1 fully in terms of Bourbaki primitives requires over
4 trillion symbols.")

The whole enterprise is bizarre. As humans, we didn't start out with sets and
then build out mathematics. No, the Egyptians did arithmetic and
some algebra. ([The oldest extant mathematical records deal with the
Pythagorean theorem.](https://en.wikipedia.org/wiki/History_of_mathematical_notation)) Animals have some notion of magnitude and many can even
count. Set theory, rather than a natural extension of mathematical enterprise,
seems more like something forced -- the difference between English and
Esperanto.

As far as I can tell, the mathematical community agrees with me. Paul Cohen is the only person
to ever win a Fields medal for work on foundations and today "foundations of mathematics" is
code not for mathematics, but philosophy.

So, immediately, category theory has an advantage over set theory in that it's a
less artificial construction, given that it stems directly from work in
algebraic topology. 

But, beyond that, is their anything else exciting about category theory? The main draw
is its ability to connect otherwise disparate fields, a sort of [skeleton to hang
other knowledge on](http://rs.io/2014/02/24/compressing-knowledge.html). John Baez writes about
this in his ["Physics, topology, logic and computation: a Rosetta Stone"](http://arxiv.org/pdf/0903.0340.pdf), where
he uses category theoretic constructs to speak about the similarities between --
you guessed it -- physics, topology, logic, and computation.

Jocelyn Ireson-Paine [puts it this way](http://www.j-paine.org/make_category_theory_intuitive.html), "category theory is a great source of unifying
concepts and organizing principles." This is the benefit of all the abstraction
-- by
[throwing away all the details](http://rs.io/2013/08/28/picasso-as-a-mathematician.html),
an object's structure reveals itself.

As a concrete example, consider one of the most profound mathematical
achievements, Descartes's discovery of analytic geometry -- the realization that
geometry can be translated into cartesian coordinates and, thus, the power of algebra
can be brought to bear on the subject.

With category theory, this discovery can be expressed in what has to be one of
the most satisfying formulas of all time:

\\(  P \xrightarrow{\quad f \quad} \mathbb{R}^{2} \\)

# Applications of category theory

The above is nice and all, but it's still just sort of
hey-take-my-word-for-it, which is not so satisfying. Here are some actual examples:

* Category theory has been used to
  [study grammar and human language](http://reyes-reyes.com/1999/06/01/count-nouns-mass-nouns-and-their-transformations-a-category-theoretic-unified-semantics/).
* [In building a spreadsheet application.](http://arxiv.org/ftp/arxiv/papers/0803/0803.2027.pdf)
* As a
  [descriptive tool in neuroscience](http://arxiv.org/PS_cache/math/pdf/0306/0306223v1.pdf).
* In the
  [analysis and design of cognitive neural network architectures](http://pdf.aminer.org/000/392/201/category_theory_applied_to_neural_modeling_and_graphical_representations.pdf).
* Many applications in [graduate level mathematics](http://ncatlab.org/nlab/show/applications+of+%28higher%29+category+theory#related_pages) (i.e. stuff I don't
  understand) and
  [physics](http://ncatlab.org/nlab/show/higher+category+theory+and+physics). 
* In programming languages,
  [especially Haskell and most famously monads](https://en.wikibooks.org/wiki/Haskell/Category_theory),
  but also, for instance, a
  [typed assembly language](http://www.cs.cornell.edu/~ross/publications/italx/)
  and work on the [typed lambda calculus](http://www.cs.nott.ac.uk/~txa/publ/lics01.pdf).
* [Generating program optimizations](http://www.cs.cornell.edu/~ross/publications/proofgen/proofgen_tate_popl10.pdf).
* [To model systems of interacting agents.](http://www.amazon.co.uk/Space-Motion-Communicating-Agents/dp/0521738334/ref=sr_1_1?ie=UTF8&s=books&qid=1283624498&sr=8-1)
* [To generalize sorting algorithms.](https://www.cs.ox.ac.uk/people/ralf.hinze/publications/WGP12.pdf)
* To understand
  [collaborative text editing.](http://bosker.wordpress.com/2012/05/10/on-editing-text/)
* To understand
[optimal play in sequential games like chess](http://www.cs.bham.ac.uk/~mhe/papers/selection-escardo-oliva.pdf). 
* To
  [formalize the notion of algorithm](http://arxiv.org/pdf/math/0602053v3.pdf).
* In
  [the study of analogy](http://link.springer.com/article/10.1023/A:1018963029743).
* As ["a language for experimental design patterns" and "a new vocabulary in
  which to think and communicate."](http://math.mit.edu/~dspivak/CT4S.pdf)
* In definitions of
[emergence](http://www.nbi.dk/~emmeche/coPubl/97d.NABCE/ExplEmer.html) and
discussions of
[biology](http://golem.ph.utexas.edu/category/2007/11/category_theory_and_biology.html).
* Generally speaking, there seems to be [a cabal of radical category theorists](http://golem.ph.utexas.edu/category/),
  led by John Baez, who are
  reinterpreting anything interesting in category theoretic terms. (The trend
  reminds me of reinventing the wheel for the nth time in the nth
  newest programming language.)

I will leave you with the following:

> \[Category theory\] does not itself solve hard problems in topology or algebra. It clears away tangled multitudes of
> individually trivial problems. It puts the hard problems in clear relief and
> makes their solution possible.
<span id="quote-attribute">—<a href="http://www.cwru.edu/artsci/phil/BJPSMacLane.pdf">"The Last Mathematician from Hilbert’s Gottingen"</a></span>

# Further Reading

* If you enjoyed this, you might enjoy some of [my other posts](http://rs.io/articles.html) on math, including
  one on
  [the secretary problem](http://rs.io/2014/03/03/the-secretary-problem.html),
  [the stable marriage problem](http://rs.io/2014/03/15/the-stable-marriage-problem.html),
  [mathematical proof](http://rs.io/2014/04/09/mathematical-proof-is-about-insight.html),
  and [worldbuilding and mathematics](http://rs.io/2014/02/28/worldbuilding-and-mathematics.html).
* There are several free online category theory texts, including
  [*Abstract and Concrete Categories - The Joy of Cats*](http://katmat.math.uni-bremen.de/acc/acc.pdf)
  and [*Category Theory for Scientists*](http://math.mit.edu/~dspivak/CT4S.pdf).
* There's often interesting category theoretic discussion at the [n-Category Cafe](http://golem.ph.utexas.edu/category/).
* The "Catsters" have a [series of online videos about category theory](https://www.youtube.com/user/TheCatsters#p/u/68/xqLgGB7Hv7g). 
