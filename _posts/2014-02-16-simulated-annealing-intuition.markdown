---
title: Intuition for Simulated Annealing 
layout: post
summary: "This post develops the intuition behind simulated annealing via lots of pictures. It's self-contained and ought to be accessible to
those without a math-centric background. It also serves as a gentle introduction to
more technical discussions."
description: "Develops the intuition behind the simulated annealing search
algorithm via lots of pictures."
keywords: "simulated annealing overview"
---

!["Picture of a three dimensional function as an example of an optimization space."](/img/optimization-space.png)

Imagine that you're approached by the Greek goddess of discord, Eris and, given
that Eris is a cruel goddess, she places you into the mathematical space
above. She promises, "If you climb to the highest point, I will release you."

This would not be too difficult except, like most encounters with Greek gods, there's a catch. The goddess, in her
wickedness, has blinded you. You can only tell whether or not a step will take
you upwards or downwards. How might you find the highest peak? You think for a while and decide to
climb upwards. From any position, you choose the direction that will increase
your elevation.

!["Hill-climbing in a 3d space."](/img/hill-climb.png)

So you climb and you get to the top of this hill. Nothing happens. What gives?
You've climbed the top of *a* peak, but you haven't made it to the top of the
*highest* peak.

!["Hill-climbing hits a plateau."](/img/hill-climb-fail.png)

You're going to have to modify your
strategy. There are a couple options. You might
stumble around at random. You'd make it to the top
eventually, but it would take an eternity, most of which would be wasted exploring areas that
you'd seen before.

Instead, you could adopt a systematic approach to exploring
the landscape, which is much more efficient. With a memory better than mine, you could keep track of where you've visited
before and focus on exploring those areas you haven't. You'd start
by checking out one mountain, and then the three surrounding, and then the nine
surrounding those three, and so on until you'd found the highest point.

This would work, unless Eris has placed you in an infinite space where the
elevation increases forever. If you imagine the edges extending forever, such a
space would look like this:

!["Hill-climbing in an infinite space."](/img/infinite-climb.png)

In such a space, Eris is twisted indeed, as there is no way to reach the
peak of an infinite climb. Let's imagine that you toil away at this Sisyphean task for a few
billion years until one of the gods, Clementia, takes pity on you. She offers you a new
deal, telling you, "I will transport you to a new, finite space. If you can reach
one of the highest peaks with sufficient haste, I will free you." You accept the
deal and are teleported here:

!["A space for which simulated annealing is the answer."](/img/clementia-space.png)

This space features a number of valleys filled with sub-optimal plateaus. If
you use your original "upwards climb" strategy, you may find yourself stuck
for eternity. Alternatively, you could try searching the entire space, but then
you run the risk of violating Clementia's "sufficient haste" clause.

The trick is to modify the initial strategy to sometimes accept a downwards
move, which will help prevent you from getting stuck at a sub-optimal
plateau. Such a path might look like this:

!["Simulated annealing without temperature decrease over time."](/img/broken-annealing.png)

Still, this is not quite right, as you can see from the path above. The problem
is that your strategy never terminates. You quickly reach a high point, but then
are forced to accept sub-optimal moves as those are the only possible moves. 

To get around this, you need to modify your strategy such that you're willing to
accept a lot of bad moves early on, but fewer and fewer with time, until you
eventually will accept no sub-optimal moves. This strategy will eventually reach
a plateau. 

!["What a simulated annealing path might look like."](/img/simulated-annealing-path.png)

That's more like it. With this strategy, you begin to climb. Clementia frees you and you
live happily ever after (or at least until Eris decides to visit you again.)

Except for formalizing the details, this is the basic intuition behind simulated
annealing, which [Wikipedia calls](http://en.wikipedia.org/wiki/Simulated_annealing) a "generic probabilistic metaheuristic for the
global optimization problem of locating a good approximation to the global
optimum of a given function in a large search space." I'm not convinced such a
sentence was written with the realization that humans will have to read
it.  In English, **simulated annealing is a method for finding an approximation of the
highest (or lowest) point in a space,** like the one above. 

# Shaking Intuition

Simulated annealing can be understood in terms of body language. It can be [felt
as motion]((http://rs.io/2013/10/08/heuristics-for-reading-mathematics.html). You
can think of simulated annealing as shaking.

Imagine that you're holding onto one of the spaces above. (Masterfully illustrated below.) You place a
ping pong ball into the space, with the goal of moving the ball to the lowest
place possible. The ball will naturally roll downwards thanks to gravity, but
sometimes it will get stuck. When it gets stuck, the natural response is to
shake the space, dislodging the ping pong ball, allowing it to continue rolling
downwards.

!["Metaphor: simulated annealing as shaking a ping-pong ball."](/img/simulated-annealing-ping-pong.png)

There you have it. That's the core of simulated annealing. You could have
invented it and, now, if you ever do come across Eris, you'll be
prepared. (On second thought, if you ever come across Eris and are teleported to a
mathematical space, see a psychiatrist.)

# Further Reading

* The early strategies mentioned are real search algorithms. The "just climb
  upwards" algorithm is aptly named [hill-climbing](http://en.wikipedia.org/wiki/Hill_climbing). The random exploration method is
  known as a [random walk](http://en.wikipedia.org/wiki/Random_walk) and the "systematic exploration approach" described is
  [breadth-first search](http://en.wikipedia.org/wiki/Breadth-first_search). Its cousin, [depth-first search](http://en.wikipedia.org/wiki/Depth-first_search), would have worked
  equally well.
* For more on simulated annealing, try
  [this paper](http://homes.ieu.edu.tr/~agokce/Courses/Chapter%208%20Theory%20and%20Practice%20of%20simulated%20Annealing.pdf). For
  different interesting search algorithms, check out
  [STAGE](http://machinelearning.wustl.edu/mlpapers/paper_files/BoyanM00.pdf)
  and [beam search](http://en.wikipedia.org/wiki/Beam_search).
* Simulated annealing is a heuristic search algorithm, meaning that it attempts
  to find a "close enough" solution. This makes it well suited for otherwise
  intractable problems, such as those in NP. There's some discussion of
  applications [here](http://stackoverflow.com/questions/2988857/simulated-annealing-applications). 
* Simulated annealing was inspired by the natural process of [annealing in
  metallurgy](http://en.wikipedia.org/wiki/Annealing_%28metallurgy%29). It's one of a class of [algorithms inspired by nature](http://arxiv.org/abs/1307.4186). Scott
  Aaronson writes about the relationship between nature and complexity in [this paper](http://www.scottaaronson.com/papers/npcomplete.pdf). 
* In *The Algorithm Design Manual*, the author writes (of heuristic search algorithms) , "I find
  \[simulated annealing\] to be the most reliable method to apply in practice."

