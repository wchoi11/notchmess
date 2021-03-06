---
layout: post
title: "Why Pascal was wrong after all"
date: 2019-06-22
excerpt_separator: <!--cut-->
comments: true
---

## The Short Version
Pascal's Wager is an invalid argument because wagering for God is not the action with highest expected utility.

<!--cut-->
## Pascal's Wager
{: id="anchor"}
Pascal's Wager is an argument for why you should believe in God (not to be confused with an argument for God's existence!). Here is the Wager first, but Alan Hájek doesn't think it works in the end.[^paper]

Let's start with the first premise of the argument. No matter how committed of an atheist you might be, you should give some **positive** probability (just needs to be greater than 0) that God exists.
<label for="mn-demo" class="margin-toggle">&#8853;</label>
<input type="checkbox" class="margin-toggle"/>
<span class="marginnote">
  A Googol is $10^{100}$, more than the number of atoms in the universe!
</span>
You might give a one in a Googol chance that God exists or a very high probability that God exists, but if you think the probability is 0, how are you so sure?

[^paper]: "Waging War on Pascal's Wager," *The Philosophical Review* 112:1 (2003):p.27-56

With this first premise in mind (there's a positive probability that God exists), here are all the possible outcomes for either wagering for God or wagering against God.

Action | God Exists | God Doesn't Exist
:---: | :---: | :---:
Wager for God  | $\infty$ | $f_1$
Wager against God  | $f_2$ | $f_3$

<label for="mn-demo" class="margin-toggle">&#8853;</label>
<input type="checkbox" class="margin-toggle"/>
<span class="marginnote">
  For example, going to church if you're Christian.
</span>
To wager for God means "adopting a certain set of practices and living the kind of life that fosters belief in God" for the rest of your life (p.28). This means you need to commit yourself to believing in God. To fail at this means you wager against God.

Each action and outcome is associated with some utility value which can be seen in the table. You can think of utility as a unit for measuring happiness. For example, if I wager for God and it turns out that God exists, I will (supposedly) be granted salvation, which is infinite utility. All other values ($f_1,\; f_2, \; f_3$) are finite. We could imagine that $f_1$ and $f_2$ are negative and $f_3$ is positive, but the lesson will be that their actual values do not matter.

With this second premise (the utility table), we have one more premise to think about. That is, we should choose to do the action that has maximum expected utility. This should seem intuitive, but of course, you might have some objections to this premise. Hájek actually grants this premise (and all other premises) and shows that the argument still doesn't work so let's set aside any objections you might have.

<details class="explanation">
  <summary>
    What is expectation?
  </summary>

Expectation or expected value is a weighted sum. It answers the question of what do we expect to happen when there is more than one possible outcome for some action we take. To calculate expectation, we take each outcome and weight it by its corresponding probability of occurring. To find the expected utility of wagering for God, we multiply the probability that God exists by $\infty$ and add the result of multiplying the probability that God doesn't exist by $f_1$. This sum is $\infty$ so the expected utility of wagering for God is $\infty$.

</details>
<br>
Now, we have all 3 premises of Pascal's Wager: (1) we should give a positive probability to God's existence, (2) the utility table, and (3) we should do the action that has maximum expected utility. If we calculate the expected utility for each action from the table, wagering for God wins out because it has an expected utility of $\infty$ and wagering against God has some finite expected utility.

<label for="mn-demo" class="margin-toggle">&#8853;</label>
<input type="checkbox" class="margin-toggle"/>
<span class="marginnote">
  These properties are called reflexivity of multiplication and
  reflexivity of addition.
</span>
It's important to note here that anything multiplied by $\infty$ is still $\infty$ and anything added to $\infty$ is still $\infty$ so it doesn't matter how low of a probability you give to God's existence as long as it's greater than 0. This is why the actual values in the table do not matter.

Here are the premises and conclusion as promised:

<ol class="argument">
  <li>We should give a positive probability to God's existence.</li>
  <li>The utility table</li>
  <li>We should do the action that has maximum expected utility.</li>
  <li>(Conclusion) We should wager for God.</li>
</ol>

## Why Pascal was Wrong
Not convinced? There is a whole slew of arguments out there against each premise of the Wager. For example, "the many Gods objection" disputes that the table is exhaustive because there are many religions out there. How do we know which God to wager for? We might need to add rows for wagering for other Gods. Then, Pascal's Wager fails because it doesn't tell us which God to wager for.

<label for="mn-demo" class="margin-toggle">&#8853;</label>
<input type="checkbox" class="margin-toggle"/>
<span class="marginnote">
  Hájek credits Antony Duff and Richard C. Jeffrey for the origins of his argument.
</span>
But Hájek thinks that the Wager fails at a more fundamental level. He argues that the Wager is an *invalid argument*.

<details class="explanation">
    <summary>
        What is a valid argument?
    </summary>

First, an argument is a list composed of some premises (there may be none!) and a conclusion. An argument is valid if its conclusion is always true when its premises are true. For example:

<ol class="argument">
    <li>If I am an egg, then I can fly.</li>
    <li> I am an egg.</li>
    <li>I can fly.</li>
</ol>

Our argument&mdash;though I agree looks absurd&mdash;is in fact valid. If premises 1 and 2 are true, there is no way 3 can be false. We think this argument is absurd because premises 1 and 2 are false. Then, we may call this argument unsound. Although the argument is valid, the premises are false so the argument cannot be sound. A sound argument is a valid one, where its premises are also true.

</details>

By arguing that the Wager is invalid, Hájek doesn't need to show that one of the premises is false in order to show the argument fails. He grants all the premises of the Wager but still shows that the argument fails. Hájek is essentially beating Pascal at his own game.

<label for="mn-demo" class="margin-toggle">&#8853;</label>
<input type="checkbox" class="margin-toggle"/>
<span class="marginnote">
  It's unclear to me why this is not just another attack on premise 2
  with the table. Isn't Hájek arguing that the table doesn't contain
  all possible actions? Mixed strategies are not included so the argument
  ends up being invalid? Maybe it's a bit of both?
</span>
Here's how it goes. What Hájek shows is that there are other actions (he calls these *mixed strategies*) that also have infinite expected utility. Then, wagering for God will not be the only action that has infinite expected utility so it won't be true that we should wager for God because it has the highest expected utility. We could instead do this other action that has infinite expected utility.

Notice that this reasoning means the premises of the Wager could be all true but the conclusion false. It could be the case that we should do some mixed strategy instead of wagering for God because it also has the highest expected utility. Thus, the Wager is invalid.

A mixed strategy is best explained with an example. For starters, let's say the strategy is that I flip a coin and wager for God if it lands heads and wager against God if it lands tails. Then, if we calculate the expected utility, where p is the probability that we give to God existing, we get $\infty$! This mixed strategy of flipping the coin also has infinite expected utility just like wagering for God.

$$
\class{eq}{\overbrace{0.5}^{\text{Probability of} \\ \text{flipping heads}} \cdot \underbrace{(p \cdot \infty + (1-p) \cdot f_1)}_\text{(Expected) utility of wagering for God} + \overbrace{0.5}^{\text{Probability of} \\ \text{flipping tails}} \cdot \underbrace{(p \cdot f_2 + (1-p) \cdot f_3)}_\text{(Expected) utility of not wagering for God}}
$$

<p class="eq-caption"><em>How to calculate the expected utility for a mixed strategy of flipping a coin</em></p>

But it gets worse. We can use other absurdly low-probability events in mixed strategies. One strategy could be wagering for God if I win the lottery and another could be wagering for God if an asteroid lands on top of me today. These all have infinite expected utility so it isn't the case that we should simply wager for God. There's no reason to simply wager for God over all these mixed strategies. They all have the same expected utility of infinity.

If you think this is bad for Pascal, it gets even worse. As Hájek points out, **every** action we take is a mixed strategy. There's a positive probability that you'll wager for God by the time you finish reading this sentence. Thus, the act of reading that sentence had infinite expected utility. By similar reasoning, every action has infinite expected utility. It seems like things have really gone off the rails now.

## Can the Wager be Saved?
But not all is lost. Hájek swoops to the rescue here, offering 4 different reformulations of the Wager that don't fall victim to the mixed strategies objection.
<label for="mn-demo" class="margin-toggle">&#8853;</label>
<input type="checkbox" class="margin-toggle"/>
<span class="marginnote">
  One reformulation uses *surreal numbers* and another
  uses vectors.
</span>
I won't go into all of them (they do get a bit technical), but the idea is to give the utility of salvation a "finite-looking gloss" (p.35). This means the reformulation must satisfy two conditions as Hájek specifies: (1) the utility of salvation "must completely override" any other utilities and (2) we should be able to distinguish the expected utility of wagering for God from the expected utility of any mixed strategy (p.35).

The first condition ensures that Hájek is consistent with Pascal's view on salvation. Salvation must be the best possible thing so it should be far greater than any other utility. This is why we assigned salvation infinite utility before. The first condition also ensures that no matter what probability we assign to God's existence the utility of salvation is still far greater than any other utility when we calculate expected utility. This was the original trick behind the Wager to make wagering for God have the highest expected utility.

The second condition is actually the important one here because the mixed strategy objection is fatal to the Wager. If the expected utilities are different, then we could argue that wagering for God has the highest expected utility.

Here's one reformulation (which I think is hacky) from the four that Hájek offers. Consider all the people from the past, present, and future and get the lowest probability that someone attributes to the existence of God. Let's call this probability $p$. Then, we can find a $f_0$ (with some light arithmetic) such that even with this lowest probability the expected utility of wagering for God wins out. Then, everyone (again from the past, present, or future) should wager for God because the expected utility of wagering for God is highest for everyone's probability that God exists.

$$
\class{eq}{\underbrace{p \cdot f_0 + (1-p) \cdot f_1}_{\text{Expected utility} \\ \text{of wagering for God}} > \underbrace{p \cdot f_3 + (1-p) \cdot f_4}_{\text{Expected utility} \\ \text{of not wagering for God}}}
$$

<p class="eq-caption"><em>Solve this inequality to find $f_0$</em></p>

This satisfies both of the conditions from before. The utility of salvation ($f_0$) overrides all other utilities because we picked it this way, and we can distinguish the expected utility of wagering for God from the expected utility of any mixed strategy. Pick any event with probability $q$ ($q>0$) for a mixed strategy. Then, its expected utility is less than the expected utility of wagering for God.

$$
\class{eq}{\underbrace{p \cdot f_0 + (1-p) \cdot f_1}_{\text{Expected utility} \\ \text{of wagering for God}} > \underbrace{q \cdot (p \cdot f_0 + (1-p) \cdot f_1) + (1-q) \cdot (p \cdot f_3 + (1-p) \cdot f_4)}_{\text{Expected utility of wagering for any mixed strategy}}}
$$

<p class="eq-caption"><em>Now we can differentiate the expected utilities of mixed strategies from wagering for God</em></p>

<!-- Why is the expectation less than the expectation for wagering? We have q parts of a and (1-q) parts of b, but one whole a is still larger than this sum because a > b. Mathemtically, (1-q) a > (1-q) b and q * a + (1-q) * a > q * a + (1-q) * b and a > q * a + (1-q) * b-->

Hájek points out (and this goes for all the reformulations) that the problem with this reformulation is that the utility of salvation is not *reflexive under addition*. This is another way of saying that adding something makes the utility of salvation a different number. Remember, originally the utility of salvation was reflexive under addition because anything added to infinity is infinity. But if the utility of salvation is not reflexive under addition (because it's now finite), salvation is now not the best thing possible because its utility could be even greater. Because this reformulation is inconsistent with Pascal's view on salvation, it fails.

But why can't we just make the utility of salvation reflexive under addition? Because if we do so, the utility of salvation also becomes reflexive under multiplication (adding the same number over and over is just multiplication!), opening the door again to the mixed strategies objection. Once the utility of salvation has both of these properties, we're back to where we started.

<details class="explanation">
    <summary>
        Why not just give up on salvation having infinite utility?
     </summary>

 Because someone might object that having finite utility over an infinite time still becomes infinite utility so either we shouldn't wager for God or we start to challenge some theological thoughts about heaven (one being that the afterlife is eternal).

</details>

Then, Pascal and anyone who buys into the Wager face a **dilemma**: either attribute both reflexivity of addition and multiplication to the utility of salvation or attribute neither of them.
<label for="mn-demo" class="margin-toggle">&#8853;</label>
<input type="checkbox" class="margin-toggle"/>
<span class="marginnote">
  You might also want to check out Nick Bostrom's "Pascal's Mugging"
  for an entertaining (and short) read about why a finite utility
  value for salvation still doesn't work.
</span>
The first option lets in mixed strategies and the second is inconsistent with Pascal's view on salvation so it doesn't seem like there's an easy way out. **So fear not!**
You don't have to convert because of Pascal's Wager.[^thanks]

[^thanks]: Many thanks to DS for taking the time to give feedback on this post.
