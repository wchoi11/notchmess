---
layout: post
title: "Did you know that knowledge-how is knowledge-that?"
date: 2019-09-14
excerpt_separator: <!--cut-->
comments: true
---

## The Short Version
Knowledge-how is just a type of knowledge-that if you look at standard
linguistic theories.

<!--cut-->

## Why should you care about this?
{: id="anchor"}

Many of us (including me!) buy into the distinction between knowledge-that
and knowledge-how. Knowing that the sky is blue is one type of knowledge,
and knowing how to swim is another type.

Knowledge-that is concerned with propositions, and
knowledge-how is concerned with skills or abilities.
As you've probably noticed, we say
knowledge-that because we always use some form of
"know that" when giving examples
of knowledge-that and some form of "know how" for knowledge-how.


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
will be sufficient for my purposes but note that it is an oversimplification.

</details>

<label for="mn-demo" class="margin-toggle">&#8853;</label>
<input type="checkbox" class="margin-toggle"/>
<span class="marginnote">
  Well, at least for the US K-12 education system.
</span>
I've seen this distinction used the most when talking about education. When we critique
the current education system, we might say that schools focus too much on memorization
(knowledge-that) instead of skills (knowledge-how) such as critical thinking.[^optimistic]
<label for="mn-demo" class="margin-toggle">&#8853;</label>
<input type="checkbox" class="margin-toggle"/>
<span class="marginnote">
  So you can memorize how to swim? I think this is
  one interesting implication of S&W's argument, and
  it makes more sense if you think about it in terms of muscle memory.
</span>
What Jason Stanley & Timothy Williamson (S&W) argue is that this distinction doesn't
exist so knowledge-how is really just propositional knowledge and not a skill or ability.[^paper]

[^optimistic]: I think we should be more optimistic about education if this distinction doesn't exist. If knowledge-how is propositional knowledge, it would be easier to teach skills like critical thinking without assuming that some students simply don't have the capacity to learn the skill.

[^paper]: "Knowing How," *The Journal of Philosophy* 98:8 (2001):p.411-444.


## Ryle's argument
<label for="mn-demo" class="margin-toggle">&#8853;</label>
<input type="checkbox" class="margin-toggle"/>
<span class="marginnote">
  Of course, this isn't the only argument for the distinction, but
  it's the most famous in the literature.
</span>
S&W first challenge the main argument for the distinction between knowledge-that and
knowledge-how. Gilbert Ryle came up with the argument:

<ol class="argument">

  <li>(Assumption) Knowledge-how is a type of knowledge-that.</li>
  <label for="mn-demo" class="margin-toggle">&#8853;</label>
  <input type="checkbox" class="margin-toggle"/>
  <span class="marginnote">
    $F$ is an action, but we'll soon see that it can't be
    <strong>all</strong> actions.
  </span>
  <li>If you $F$, then you use knowledge of how to $F$.</li>
  <li>If you use knowledge that $p$, then you contemplate the proposition $p$.</li>
  <li>(Conclusion) Knowledge-how is not a type of knowledge-that.</li>

</ol>

<label for="mn-demo" class="margin-toggle">&#8853;</label>
<input type="checkbox" class="margin-toggle"/>
<span class="marginnote">
  Philosophers like to sound cool so they call these
  proofs *reductios* for short.
</span>
Ryle's argument is actually a proof by contradiction or *reductio ad absurdum*.
Ryle first assumes that there is no distinction and then derives a contradiction
to show that the assumption is false.

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
Ryle derives one.

<label for="mn-demo" class="margin-toggle">&#8853;</label>
<input type="checkbox" class="margin-toggle"/>
<span class="marginnote">
  Substitute $F$ with "ride a bike."
</span>
If I ride a bike,
I use knowledge of how to ride a bike by premise 2. Then, by the first premise,
knowledge of how to ride a bike is knowledge that some proposition $p$. Then,
applying premise 3, if I use knowledge that $p$, then I contemplate the
proposition $p$.

Here's the trick. Contemplating a proposition is an action just like
riding a bike.
<label for="mn-demo" class="margin-toggle">&#8853;</label>
<input type="checkbox" class="margin-toggle"/>
<span class="marginnote">
  Substitute $F$ with "contemplate a proposition $p$."
</span>
Then, applying premise 2 again, if I contemplate a
proposition $p$,
then I use knowledge of how to contemplate a proposition $p$.
By premise 1, knowledge of how to contemplate a proposition $p$ is
knowledge that some proposition $q$. Then, once again by premise 3,
if I use knowledge that $q$, then I contemplate the proposition $q$.

We can keep on applying the same premises over and over again. This means
that to ride a bike I have to contemplate an infinite number of
propositions, but this would mean I would never be able to ride a bike!
This is a contradiction because we, in fact, do actions
like riding a bike without thinking of an infinite number of propositions.

What are $p$ and $q$? We're assuming that there is some way of converting
knowledge-how to knowledge-that so we're using variables to stand in
for the result of that process. It's not necessary to know exactly what
$p$ and $q$ are for the argument to work.

## Why Ryle's argument doesn't work
<label for="mn-demo" class="margin-toggle">&#8853;</label>
<input type="checkbox" class="margin-toggle"/>
<span class="marginnote">
  Unsound in the sense that one of the premises is false.
</span>
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
digesting food make premise 2 false.
<label for="mn-demo" class="margin-toggle">&#8853;</label>
<input type="checkbox" class="margin-toggle"/>
<span class="marginnote">
  So we can only substitute intentional actions for $F$
  in premise 2.
</span>
Thus, premise 2 is only true
for intentional actions.

Now let's look at premise 3: "If you use knowledge that $p$, then
you contemplate the proposition $p$." S&W point out that Carl Ginet
showed there are cases where this is false. If I type the letter "f,"
I know that the "f" key is under my index finger, but I don't think
this in my mind when I type the word "fox".

S&W suggest that I
*unintentionally* contemplate the proposition that the "f" key is
under my index finger so premise 3 is true only if contemplating
a proposition is interpreted as an unintentional action. What
Ginet actually showed is that premise 3 is false if contemplating a
proposition is an intentional action.

<label for="mn-demo" class="margin-toggle">&#8853;</label>
<input type="checkbox" class="margin-toggle"/>
<span class="marginnote">
  It's a proof by cases.
</span>
Now we have all the ingredients to see why Ryle's argument is
unsound.

If contemplating a proposition is intentional, then premise 3 is false.
This means Ryle's argument is unsound.

If contemplating a proposition is unintentional, then
we can't substitute
"contemplating a proposition $p$" for $F$ because premise 2 is true
only for intentional actions. This means premise 2 would be false
when we substitute contemplating a proposition. Then, Ryle's
argument is unsound in this case too.

No matter how we interpret the intentionality of contemplating
a proposition, Ryle's argument is unsound.

## What is knowledge-how?

### Ryle's account
S&W first offer a counterexample to Ryle's account of knowledge-how.
Ryle thought that knowledge of how to $F$ is the ability to $F$, and
I believe this is roughly what we think too. If I know how to ride a
bike, I have the ability to ride a bike.
<label for="mn-demo" class="margin-toggle">&#8853;</label>
<input type="checkbox" class="margin-toggle"/>
<span class="marginnote">
  It actually doesn't sound intuitive to me for the last example.
</span>
If I know how to fly, I
have the ability to fly.

Here is a rather dark counterexample.
Imagine a famous pianist has
lost both her arms in a terrible accident.
<label for="mn-demo" class="margin-toggle">&#8853;</label>
<input type="checkbox" class="margin-toggle"/>
<span class="marginnote">
  But what if the pianist got prosthetic arms
  (like <strong>really</strong> good ones)? Wouldn't
  we say the pianist always had the ability to play piano?
  Maybe it's more accurate to call it a latent ability
  when she didn't have arms.
</span>
The pianist knows
how to play the piano, but she does not have the ability to
play the piano anymore.
Thus, knowledge of how to $F$
is not the ability to $F$.

### Stanley & Williamson's account
<label for="mn-demo" class="margin-toggle">&#8853;</label>
<input type="checkbox" class="margin-toggle"/>
<span class="marginnote">
  I'm not a linguist by training so forgive me if I butcher anything.
</span>
S&W's account gets rather technical (linguistically) so I will
limit myself to the key points.

The example S&W work with is "Hannah knows how to ride a bike." Let's refer
to this sentence as (1).

The key observation S&W make is that (1) has an *embedded question*,
"how to ride a bike." Under standard linguistic theory, embedded
questions denote (stand in for) the "set of its true answers" (p.420).[^dishonest]

[^dishonest]: I'm actually being a little dishonest here. Instead of standard linguistic theory, it's really Lauri Karttunen's semantics that S&W are using, but S&W think that standard linguistic theories agree with the basics of Karttunen's semantics for embedded questions.

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
muse over, but S&W think that knowledge-how is really just knowledge-that
because of how the semantics for embedded questions works out.[^thanks]

[^thanks]: Many thanks to DS and SGS for taking the time to give feedback on this post.
