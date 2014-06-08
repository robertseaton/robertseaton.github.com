---
title: What are Quantum Computers Good For?
layout: post
---

There is a lot of magical thinking around quantum computers. That they're the
next big thing in computing, that they'll replace classical computers, that they'll
be impossibly fast and small. There's [at least one](http://www.reddit.com/r/explainlikeimfive/comments/1cs062/eli5how_a_quantum_computer_works_and_why_it_is/c9jh0zx) quantum physicist who doesn't
know any better. **Most problems receive no sort of "quantum speedup."**

Here's what Scott Aaronson, a theoretical computer science guy who works on quantum computing at MIT, has to say:

> To be clear, I think it’s entirely possible that I’ll see practical quantum
> computers in my lifetime (and also possible, of course, that I won’t see
> them). And if we do get scalable, universal quantum computers, then they’ll
> almost certainly find real applications (not even counting codebreaking):
> mostly, I think, for specialized tasks like quantum simulation, but to a lesser
> extent for solving combinatorial optimization problems.
<span id="quote-attribute">—<em>Quantum Computers Since Democritus</em></span>

Sure, quantum computing will be useful, but no, they won't enable us to replace
classical architecture machines with fingernails that -- I don't know -- pass
the Turing test.

Here's
[Aaronson himself in Scientific American](http://www.cs.virginia.edu/~robins/The_Limits_of_Quantum_Computers.pdf)
with a bit more on quantum computers for simulation:

> If quantum computers ever become a reality, the “killer app” for them will most
> likely not be code breaking but rather something so obvious it is rarely even
> mentioned: simulating quantum physics. This is a fundamental problem for
> chemistry, nanotechnology and other fields, important enough that Nobel Prizes
> have been awarded even for partial progress.

## Problems fit for a quantum computer

<center><img src="/img/complexity-classes.png"></center>

On what sort of specific problems quantum computers will be used for, well,
that's a complexity class: [BQP](http://en.wikipedia.org/wiki/BQP). A quantum
computer -- should they prove physically realizable -- can outperform a
classical computer at problems outside of P (another complexity class) but in
BQP.

The main suspected problems in that class are:
* Integer factorization (important for crypto)
* Quantum-level simulations of physical stuff.

So, you know, what Aaronson already told us.

So, classical machines are here to stay. Quantum computers are not a silver bullet. Hard problems remain hard, or as Aaronson puts it (again from his Scientific American piece):

> I predict that the hardness of NP-complete problems will someday be seen the
> same way: as a fundamental principle that describes part of the essential
> nature of our universe. There is no way of telling what theoretical
> enlightenment or what practical consequences might come from future
> application of this kind of fundamental principle.
  
## Further Reading

* Scott has a [blog](http://www.scottaaronson.com/blog/) with way more quantum
  computer stuff.
