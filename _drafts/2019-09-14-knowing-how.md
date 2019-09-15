---
layout: post
title: "Did you know that knowledge-how is knowledge-that?"
date: 2019-09-04
excerpt_separator: <!--cut-->
---

## The Short Version
Knowing how is just a type of knowing that if you look at standard
linguistic theories.

<!--cut-->

## Why should you care about this?
{: id="anchor"}

Many of us (including me!) seem to buy into the distinction between knowledge-that
and knowledge-how. Knowledge-that is concerned with propositions, and knowledge-how
is concerned with skills or abilities.


<details class="explanation">
  <summary>
    What is a proposition?
  </summary>

Here's one way to define propositions. A proposition is a statement that is
either true or false. For example, "The cat is on the table" is a proposition.
The cat could either be on the table or not on the table.

This is surprisingly (or maybe predictably) a contentious area of debate for philosophers. For example,
if you look up propositions in the Stanford Encyclopedia of Philosophy, a quick skim will show
that there's no single definition of a proposition. I think my definition
will be sufficient for my purposes, but note that it is an oversimplification.

</details>

The most common topic I've seen this distinction used is on education. When we critique
the current education system, we might say that schools focus too much on memorization
(knowledge-that) instead of skills (knowledge-how) such as critical thinking.
What Jason Stanley & Timothy Williamson (S&W) argue is that this distinction doesn't
exist so knowledge-how is really propositional knowledge and not a skill or ability.[^paper]

[^paper]: "Knowing How," *The Journal of Philosophy* 98:8 (2001):p.411-444.


## Ryle's argument
S&W first challenge the main argument for the distinction between knowledge-that and
knowledge-how. It's credited to Gilbert Ryle:

<ol class="argument">

  <li>(Assumption) Knowledge-how is a type of knowledge-that.</li>
  <li>If you $F$, then you use knowledge of how to $F$.</li>
  <li>If you use knowledge that $p$, then you contemplate the proposition $p$.</li>
  <li>(Conclusion) Knowledge-how is not a type of knowledge-that</li>

</ol>

Ryle's argument is actually a proof by contradiction or *reductio ad absurdum*.
Ryle first assumes that there is no distinction and then derives a contradiction
to show that the assumption that there is no distinction is false.

<details class="explanation">
  <summary>
    What is a proof by contradiction?
  </summary>

This is a proof technique from math. To show that something is false, first
assume that it is true and then using premises that you know are true
show that a contradiction is reached. Since it shouldn't be possible
to reach a contradiction from true premises, the first assumption must be
false.

For example, here is an argument to show that there is no largest prime number:

<ol class="argument">

  <li>(Assumption) There is a largest prime number.</li>
  <li>$p_1, p_2, \dots ,p_n$ are all the primes,
  where $p_n$ is the largest prime.</li>
  <li>$(p_1 \cdot p_2 \cdot \dots \cdot p_n) + 1$ is a prime.</li>
  <li>$(p_1 \cdot p_2 \cdot \dots \cdot p_n) + 1 > p_n$.</li>
  <li>(Conclusion) There is no largest prime because we reached a contradiction;
  $p_n$ is both the largest prime and not the largest prime.</li>

</ol>

</details>

So what is the contradiction? Let's walk through an example to see how
Ryle derives one. If I ride a bike (substitute $F$ with "ride a bike"),
I use knowledge of how to ride a bike by premise 2. Then, by the first premise,
knowledge of how to ride a bike is knowledge that some proposition $p$. Then,
applying premise 3, if I use knowledge that $p$, then I contemplate the
proposition $p$.

Here's the trick. Contemplating a proposition is an action just like
riding a bike. Then, applying premise 2 again, if I contemplate a
proposition $p$ (substitute $F$ with "contemplate a proposition $p$"),
then I use knowledge of how to contemplate a proposition $p$.
By premise 1, knowledge of how to contemplate a proposition $p$ is
knowledge that some proposition $q$. Then, once again by premise 3,
if I use knowledge that $q$, then I contemplate the proposition $q$.

We can keep on applying the same premises over and over again. This means
that to ride a bike I have to contemplate an infinite number of
propositions, but this would mean I would never be able to ride a bike!
This is a contradiction because we do actions like riding a bike without
thinking of an infinite number of propositions.

What are $p$ and $q$? We're assuming that there is some way of converting
knowledge-how to knowledge-that so we're using variables to stand in
for the result of that process. It's not necessary to know exactly what
$p$ and $q$ are for the argument to work.

## Why Ryle's argument doesn't work
I found Ryle's argument quite convincing, but S&W show that Ryle's
argument is actually *unsound*.

<details class="explanation">
    <summary>
        What is a sound argument?
    </summary>

A sound argument is a valid one, where its premises are also true. An unsound
argument is one where either the argument is invalid or one of its
premises are false.

Here's a quick refresher on what a valid argument is
in case you need it:

An argument is valid if its conclusion is always true when its premises
are true. For example:

<ol class="argument">
    <li>If I am an egg, then I can fly.</li>
    <li> I am an egg.</li>
    <li>I can fly.</li>
</ol>

Our argument&mdash;though I agree looks absurd&mdash;is in fact valid. If premises 1 and 2 are true, there is no way 3 can be false. We think this argument is absurd because premises 1 and 2 are false. Then, we call this argument unsound. Although the argument is valid, the premises are false so the argument cannot be sound.

</details>

Let's first consider premise 2: "If you $F$, then you use knowledge
of how to $F$." S&W point out that there are counterexamples to this
premise. For example, "If you digest food, then you use knowledge of
how to digest food" is clearly false. Unintentional actions like
digesting food make premise 2 false. Thus, premise 2 is only true
for intentional actions.

Now let's look at premise 3: "If you use knowledge that $p$, then
you contemplate the proposition $p$." S&W point out that Carl Ginet
showed there are cases where this is false. If I type the letter "f,"
I know that the "f" key is under my index finger, but I don't think
this in my mind when I type the word "fox". S&W suggest that I
*unintentionally* contemplate the proposition that the "f" key is
under my index finger so premise 3 is true only if contemplating
a proposition is interpreted as an intentional action.

Now we have all the ingredients to see why Ryle's argument is
unsound.

If contemplating a proposition is intentional, then we can't substitute
"contemplating a proposition $p$" for $F$ because premise 2 is true
only for intentional actions. This means premise 2 would be false
when we reapply premise 2. Once again, Ryle's argument is unsound.

If contemplating a proposition is unintentional, then
premise 3 is false so Ryle's argument is unsound.

No matter how we interpret the intentionality of contemplating
a proposition, Ryle's argument is unsound.

## What is knowledge-how?

### Ryle's account
S&W first offer a counterexample to Ryle's account of knowledge-how.
Ryle thought that knowledge of how to $F$ is the ability to $F$, and
I think this is roughly what we think too. If I know how to ride a
bike, I have the ability to ride a bike. If I know how to fly, I
have the ability to fly.

Here is a rather dark counterexample.[^who] Imagine a famous pianist has
lost both her arms in a terrible accident. The pianist knows
how to play the piano, but she does not have the ability to
play the piano anymore.[^worry] Then, knowledge of how to $F$
is not the ability to $F$.

[^who]: S&W came up with this, not me!

[^worry]: But what if the pianist got prosthetic arms? Wouldn't we say the pianist always had the ability to play piano? It's just that she couldn't exercise her ability. Maybe it's more accurate to call it a latent ability when she didn't have arms.

### Stanley & Williamson's account
S&W's account gets rather technical (linguistically) so I will
limit myself to the key points.[^forgive]

[^forgive]: I'm not a linguist by training so please forgive me if I butcher anything.

The example S&W work with is "Hannah knows how to ride a bike." Let's refer
to this sentence as (1).

The key observation S&W make is that (1) has an *embedded question*,
"how to ride a bike." Under standard linguistic theory, embedded
questions denote (stand in for) the "set of its true answers" (p.420).[^dishonest]

[^dishonest]: I'm actually being dishonest here. Instead of standard linguistic theory, it's really Lauri Karttunen's semantics that S&W are using, but S&W think that standard linguistic theories agree with the basics of Karttunen's semantics for embedded questions.

It's easier to see what this means with another embedded question. If I
say, "I know where my bike is," then the embedded question is "where my bike
is." The answer(s) to the embedded question could be in front of my house or
at the bike rack. Then, "I know where my bike is" could mean "I know that
my bike is at the bike rack."

For embedded questions with "how," the answers are ways. For example,
"how to ride a bike" could be answered with $w$ is a way to ride a bike.
Then, (1) means "Hannah knows that $w$ is a way to ride a bike." There's
no easy way (heh) to say exactly what $w$ is, but it would probably include
descriptions like "turning the handles to the right to turn right" and
"pressing down on the pedals to move forward."

And that's the gist of it. There are a lot more technicalities that S&W
muse over, but with the semantics for embedded questions it's easy
to see why S&W think that knowledge-how is really just knowledge-that.
