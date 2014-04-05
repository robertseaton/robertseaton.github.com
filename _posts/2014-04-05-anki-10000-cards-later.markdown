---
title: Anki, Ten Thousand Cards Later
layout: post
summary: "How my Anki usage has evolved after 10,000 cards."
---

If you don't know what Anki or spaced repetition is, start by reading
[gwern's excellent introduction](http://www.gwern.net/Spaced%20repetition).

!["Picture of Anki review statistics."](/img/anki.png)

This month, I created my ten thousandth virtual flashcard. When I started using Anki, I worried that I'd do the wrong thing, but
decided that the only way to acquire Anki expertise was to make a lot of
mistakes.

Here's how my Anki usage has evolved.

## Why questions

Cards that answer the question "Why?" are more valuable than factual
cards. (See also [this post](http://rs.io/2014/02/25/why-questions-reveal-structure.html).) It's
easy to memorize that QuickSort has a lower bound of O(n lg n), but better to
know *why* it has such a lower bound, and even better still to understand why
comparison-based sorts can't be faster than O(n lg n).

Of course, it's best to know all of these.

My emerging perspective here is that it's important to understand all the
context of an idea to *really* know it. How it emerged, how to invent it, what
it's for, and so on. 

## Images

My original Anki decks were *all* words. Now, I lean on images as
  heavily as possible. I find, at least for my sort of
  mind, that most of understanding something is learning to visualize
  and manipulate it mentally. Google image search is one of my first stops.
  
In a pinch, I also make crude drawings of my own. As long as it captures the
main idea, it'll do:

!["Crude math drawing."](/img/crude-anki.png)
  
As an unintended consequence, my thought itself has shifted towards more imagery. The repetition makes an image
representation of a concept more available mentally than its equivalent in words.

## Connections

The biggest problem with Anki is the tendency for cards to become
disconnected, so that a lot of knowledge is only available with the right cue
and, even then, it's a sort of impoverished thing.

I'm not aware of any silver bullet for this problem, but I now construct more
cards that enforce links between knowledge. I might ask, "How is this concept
different from that concept?" Or how a concept explains something from my
personal life, or what an idea is reminiscent of.

The main limitation here is the general unavailability of a piece of information. With the right cue, I can recall it,
but it's not as if I can just sit down and brain dump every single one of my
memories.

Mnemonics, at least the [method of loci](http://en.wikipedia.org/wiki/Method_of_loci), are a bit better in this regard, as I
can think myself to a place if I need to retrieve something.

## Single deck

Currently, I have decks organized by topic and subtopic. However, I now think this
is backwards. Given [Hebbian learning](http://en.wikipedia.org/wiki/Hebbian_theory) -- neurons that fire together wire
together -- I'm convinced that mixing everything is superior.

Take the production of insight, for instance. I find that insight often arises when
two ideas that have been recently activated in memory collide and I think, "Oh,
wait, that's related to that."

If everything is carefully partitioned, you limit opportunities for this
serendipity. Topic organization says "ideas about computer science don't belong with those about economics,"
except applying ideas across disciplines is precisely where the insights are
likely to be most fertile.

## Two-way connections

Here's a mistake I've made a couple of times. You'll be reading a text and it'll
define something, like the Martin-Löf-Chaitin thesis, and you'll create a card
saying, "What's the Martin-Löf-Chaitin thesis?"

Then, sometime in your life, you'll be sitting and thinking, "Hey, what's that
mathematical theory of randomness called?" and you won't know, because you
didn't make a card like that, and your mind only learned the connection one
way.

This has also happened with cuckoo hashing and I'm sure other things too, so now
I make more of an effort to learn something forwards and backwards, like "What's
cuckoo hashing?" and "What's the name of that probabilistic version of hashing?"

In general, poor models of how memory and mind
work hinder Anki effectiveness. You might think, hey, knowing something is all there is to knowing. Wrong.
A lot of knowing is creating different cues and representations of that
knowledge so that you can recall it when needed.

A great deal of an effective knowledge base is engineering it so that it'll be
useful in the sort of situations where you expect to apply it.

## Adding whatever

My philosophy when I started using Anki was to add whatever, to just adopt a
trifling barrier to entry. I didn't worry about whether a fact is useful or not
or anything like that. If something appealed to me, I'd add it.

This core is remains. The main change this philosophy has undergone is to shift away from setting a
specific study time and making cards during that study time. Instead, I add
anything interesting, regardless of when it happens, and random
connections and insight that occur to me throughout the day.

For example, each morning I go through my RSS reader and check the news for the
day. Whenever I come across something interesting or insightful, I add it.

Or here's a common hangup people have, and that I had, when starting with spaced
repetition. It's the question, "What ought I memorize?" and people think, well,
maybe the presidents or something, because that's what they've associated
memorization with.

It's the wrong question. Ask "What's interesting?" and start ankifying that.

People also really like it when you can recall minutia about them, too,
which is sort of fun. If someone mentions their favorite type of cheese, or a pet's
name, make it into an Anki card. It's like free social points. Memorizing
birthdays works.

# Thoughts on the value of Anki

I remain, more than a year later, enthusiastic about Anki. The honeymoon period
is over and I still think it's awesome.

Anki-powered studying has become my new normal. Whenever I regress to trying to
memorize something spontaneously,
without software assistance, like command line flags or some bit of HTML, it's
frustrating. It feels like something is wrong, like it ought to be so much
easier, because with Anki it is.

Which is not to say that Anki is a panacea. Just as it's a good idea to
diversify your stock portfolio, it's a good idea to diversify learning
methods.

# Further Reading

* I've written before about
  [the importance of "Why?" questions](http://rs.io/2014/02/25/why-questions-reveal-structure.html),
  on
  [structuring knowledge](http://rs.io/2014/02/24/compressing-knowledge.html),
  and on [different modes of thinking about mathematics](http://rs.io/2013/10/08/heuristics-for-reading-mathematics.html) (but which are broadly applicable).
