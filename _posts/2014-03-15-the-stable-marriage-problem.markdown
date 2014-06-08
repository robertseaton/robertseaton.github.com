---
title: The Stable Marriage Problem
layout: post
summary: "An introduction and discussion of the Stable Marriage Problem -- the
problem of pairing couples so that no person has a better option."
description: "An introduction and discussion of the Stable Marriage Problem -- the
problem of pairing couples so that no person has a better option."
---

You are out in a thunderstorm. You look up, at the rolling
thunderheads painting the sky, and wonder, "Why am I here? What's the
point of all of *this*? What difference can I make in a world of 7 billion?"

Your weekly scheduled existential angst is interrupted by a flash. It's lightning,
six-ish bolts. The yellow branches cross and, for a moment, spell out your name. "What are the
odds?" you wonder. 

It's not a sign, though. You're not falling for that
one. Your worn copy of Dawkins has earned you that much. The mind, you know, has a
tendency of seeing patterns where there are none.

You soon tire of the diversion and go back to fretting about existence. At least until
a boom interrupts your reverie. You look up again. The clouds are
parting.

You wonder if this is some sort of freak weather system and why, exactly, you
thought it would be a good idea to be out in a thunderstorm.

Light filters through as the clouds continue to part. A shy blue sky reveals herself. Trumpets sound. There are winged creatures in the sky. A
man in white floats down from the heavens.

You figure it's a brain tumor -- hopefully benign.

The man approaches you and says, "There's been an administrative mix up."

Fast forward an hour. It's explained to you that Nietzsche was almost
right. God isn't dead, not *exactly*. He's disappeared. Maybe on vacation or maybe this is part
of one of his weird plans. ("Oh, *God*. I know the one. Luminous fellow. Always
coming up with those crazy schemes.") The angels, in their wisdom, figure that the best
way to choose a new God to serve while the real one is out is via a lottery. They assign a number to every
living soul and then choose one at random.

The angels, you see, are nihilists -- and you are the chosen one.

## First act as God

Now you're God and, boy, if you thought you had responsibilities before, you've
*really* got 'em now, and all the angels are waiting. Or, at least, you feel
like they *ought* to be waiting. That's how people on Earth
behave after electing a new president -- waiting for him to do something,
anything.

But the angels aren't really like that. They speak in Zen koans. Stuff like, "Do
something. Do nothing. Be one hand clapping," and "A cow is hanging from a tree
by its teeth. A river rushes below. Does the cow *mu*?"

Mostly they just sit around, shrugging at each other. You figure they are sort
of like what cats would be like if they were human-shaped and had wings.

Still, you suppose you ought to make some huge gesture to, you know, your people. Maybe not let
them outright know that God is back -- save a little mystery for further on in
the relationship -- but *something*. 

So you ponder for a while and think, "Hey, what about that whole divorce epidemic going on? As God, I
ought to be able to do something about that. Solve that *romance thing*."

Your first act of God, you announce to the angels, will be to solve the Stable
Marriage Problem.

## The Stable Marriage Problem

Mathematics is a game of the imagination. There is but one rule: you may not
contradict yourself -- and I'm not even sure about that rule. Maybe there's a neat
looking branch of math waiting to be discovered where sometimes contradictions
are allowed. 

For every 100 human girls born,
[106 boys are born](http://en.wikipedia.org/wiki/Human_sex_ratio), but the sex
ratio for the global population is 101 males for every female -- which means that,
even if "true love" were a real thing, fated by God, some people would end up
alone.

But with mathematics, I get to be the God, and I decide that I'm doing
mathematics in a platonic reality where there is a man for every woman and a
woman for every man. 

Now consider these men and women living in this platonic mathematical
universe. The women have some men they would prefer to be with -- the Johnny
Depps and George Clooneys -- and the men have their own preferences -- the
Scarlett Johanssons and, well, more Scarlett Johanssons.

However, if God matches me with Scarlett Johansson, there is a problem. It'll
end in divorce. A smarter, better looking, more successful, all-around-wonderful guy will come
along and, well, I'm out. And our twelve children will be devastated.

No, this will not do at all.

What I'm after is an equilibrium where no individual has a better option, a stable
pairing. Like let's say I'm with Casey Anthony -- who is pretty cute but also maybe a
murderess -- and some
other non-possible-murderess comes along who prefers me over her husband. If
I prefer this new woman over the constant threat of death-by-angry-wife, then a
*better option* exists.

An ideal couple is one with no options -- people who cannot do any better than
each other. If you marry someone, you both probably prefer someone else (at
least when not blinded by infatuation), like Brad Pitt or Angelina Jolie. But
none of those people want you more than their spouse, so you're stuck
together. And that's true love. 

### Is there a stable pairing?

But it's not obvious that there is always a stable pairing. Maybe there is some
way to set things up so that there's an infinite cycle -- one where people keep
getting divorced and then remarried and then divorced again. I can sort of
imagine such a scenario. Look at all the people getting divorced and then
remarried *today*.

Every introduction to this problem that I've read papers over this concern. It
says, "Well, there *is* a stable pairing for every set of preferences. Just
analyze this algorithm I'm about to give." This is totally unsatisfying -- I
don't want to just know something. I want to know how I could reinvent it.

But alas. I'm not that clever, so you will have to put up with the traditional
style of presentation.

## A first algorithm

Since you're God, you can just use the nicest algorithm that you can invent,
which would go like this:

1. Given all men and women, generate all possible matches.
2. Filter out all the non-stable matches.
3. Pick your favorite one. 

So let's say you whip this up and you recognize that it has some seriously nasty
algorithmic complexity. It grows exponentially and, on a conventional computer
will take longer than the age of the universe for inputs larger than ~50. 

But that's fine, right? Now that you're omnipotent, you'd think that you
wouldn't need to deal with any of this computational complexity nonsense. Except
one of those damned angels chimes in and lets you know that even God isn't
allowed to use exponential algorithms for large inputs.

So, if we want to have stable marriages *and* more than 50 happy souls in our
platonic mathematical reality, we're going to have to come up with something
better.

## Gale-Shapely algorithm

For inspiration, consider how dating actually works. Bob approaches Alice and says something like, "Let's hang out sometime." or "Want to get dinner
sometime?" or, for college students, the always popular, "We should watch Netflix
together."

Alice says "yes" if she finds Bob acceptable and "no" otherwise. Then they
date until someone better comes along, at which point one of them "falls of out
love," which is [really evolution nudging them to go pursue someone else](http://rs.io/2014/02/23/on-love.html). And the
relationship ends. Usually,
[the woman is the rejecter and the man the rejectee](http://rs.io/2014/03/14/female-is-the-heartbreaker.html).

So in the real world, the algorithm looks sorta like:

1. A man asks out a woman he likes.
2. The woman accepts or rejects the man.
3. If the woman accepts the man, the woman dates the man until a suitor she
prefers comes along. At this point, the relationship ends.
4. The woman dates the new man and the old man asks out a new woman.

Rinse and repeat.

This is basically what the solution to The Stable Marriage Problem -- the
Gale-Shapely algorithm -- looks like.

1. Each man proposes to his first choice.
2. Each woman (provisionally) accepts the best man who proposed to her. We could
say that they're engaged.
3. Each non-engaged man proposes to his next-best choice.
4. Each woman accepts the best man who proposed to her and rejects the
rest. This may entail breaking off her current engagement and "trading up."
5. Repeat until everyone pairs off.

Looks sorta like dating in real life, huh?

### Proving stability

How do we know that this algorithm produces a stable match?

Let's consider two couples: Fred + Wilma and Barney + Betty. Is it possible that
there is a *better option*? That Barney prefers Wilma over Betty and Wilma
prefers Barney over Fred?

No. If Barney preferred Wilma over Betty, he would have proposed to her before
Betty, as each man proposes in order of most preferred. In such a case, either Wilma accepted and
later kicked him out because she traded up for Fred, or she didn't accept him
because she was already engaged to someone better -- Fred or someone worse than
Fred. In either case, it's impossible that Wilma prefers Barney over Fred.

## Smashing the Patriarchy

But wait! We've discovered a sexist algorithm. All the men are matched with the
best possible woman *from their point of view*, while the women get their worst
stable match! It's stable only because all the men are too happy to agree to swap with
any woman.

If we reverse the algorithm so that the women ask the men out, then we get a
female optimal algorithm -- "proving" that there's more than one stable match. 

### How many possible stable matches are there?

Lots. It turns out that the upper bound is something like
\\(O\(n!^{\frac{2}{3}}\\)) and a lower bound of \\(\Omega(2.28^n)\\). Or, you
know, *lots*.

This means that we can probably find a more egalitarian one than the
male-optimal version. And indeed we can, except the algorithm is fairly
complicated, relying on more knowledge of graph theory than I currently possess.

But as long as you're omniscient, surely [you can figure it out](http://www.corelab.ntua.gr/courses/netalg/pres2013/xatzidimitriou.pdf).

## Further Reading

* If you're interested in this sort of thing, I've also written up [the Secretary
  Problem](http://rs.io/2014/03/03/the-secretary-problem.html) and
  [the Boy or Girl Paradox](http://rs.io/2014/03/05/the-boy-girl-paradox.html).
* For more on this problem, try
  ["A survey of the stable marriage problem and its variants,"](http://140.123.102.14:8080/reportSys/file/paper/scfu/scfu_21_paper.pdf). Don
  Knuth has a book, too, [*Stable Marriage and Its Relation to Other
  Combinatorial Problems: An Introduction to the Mathematical Analysis of
  Algorithms*](http://www.amazon.com/Stable-Marriage-Relation-Combinatorial-Problems/dp/0821806033),
  and there's always
  [Wikipedia](http://en.wikipedia.org/wiki/Stable_marriage_problem).
* While the Stable Marriage problem always has a solution, the [Stable Roommates
  problem](http://en.wikipedia.org/wiki/Stable_roommates_problem) -- one awful similar -- doesn't.
