---
title: "Bayesian Epistemology"
tags: ["literature-notes","probability","epistemology","philosophy"]
source: "https://www.youtube.com/watch?v=YRz8deiJ57E&list=PLz0n_SjOttTdIqlgDjdNFfLUFVrl5j1J4"
date: 2021-08-30 23:48:56
---

Beliefs should have a defined degree of certainity rather than a binary true/false(like in classical [[Epistemology]]).

## Laws of Probability

Probability of a certain statement S is `P(S)`

### Probability Range Principle

For any event S, `0 ≤ P(S) ≤ 1` - Probability is between 0 and 1 inclusive.

## Probability Tautology Principle

For all logical truths L, the probability of L = 1.

`P(L) = 1`

## Principle of Finite Additivity

Probability of S OR R happening is probability of S + probability of R. This assumes that S and R - both can't happen together.

`S|R = P(S) + P(R)`

Sum of the probability of S and NOT S = 1

`P(~S) + P(S) = 1`

## Bayesian Theorem

`Pe(H) = (P(H) / P(E)) / Ph(E)`

`Pe(H) = P(H & E) / P(E)`

Pe(H): Probability of H given that E

PS: `Pe(H)` should be read as P<sub>E</sub>(H)

Pe(H) is the inverse of Ph(E)

## Inductive Argument / Dutch Book Argument

Degree of belief: The probability that someone assigns to a event / how much money(upto 1$) that someone is willing to bet on the event that incase it happens, they get double the money.

Dutch Book - when you have a set of conditions that others will bet on - but the probability will be higher than 1. 

Example: In a horse race, chance of Horse 1 winning is .5, Horse 2 is .25 and Horse 3 is .3. Here, the total is 1.05. So no matter the outcome, the house will get some money.

Synchronic Dutch Book: If someone has a set of degree of belief at the same time that will result in a loss no matter the outcome. Eg. Someone bets .51 that horse 1 will win and .51 that horse 1 will lose. They will get back 1$ no matter the outcome - but will lose .02$.

Diachronic Dutch Book: If someone has a set of degree of belief at different times that will result in a loss no matter the outcome. This happens when you don't update your probabilities correctly when a event with related probability is shown to be true.

## Confirmation Theory

Paradox of Dogmatism: If you are certain of an E event(P = 1), you can safely ignore all evidence against it. This will lead to un-updated priors.

Simple Principle of Conditionalization: You should update your belief when you find evidence with set confidence about a related condition.

- Confirmation: Evidence E confirm theory H if and only if our degree of belief in H is increased if E is known to be true.
- Disconfirmation: Evidence E confirm theory H if and only if our degree of belief in H is DECREASED if E is known to be true.

## Entailment

If H entails E, then E confirms H(as long as E != 1 and E != 0 - probability of E can't be certain)
 
## Bayesian Dogmatism

If you are certain anything(Probability = 1), then if you change your belief even with overwhelming evidence that the thing you believe is NOT true, you will be irrational.

Do not have absolute certainty - no Probability = 1 or 0.

## Objections to Bayesian Epistemology

### Immutability of Logic

To believe in Bayesian Epistemology, you have believe that the Laws of Probability to be certain - which is against the Bayesian Dogmatism principle - you should not be certain of anything.

### Problem of Logical Omniscience

Bayesian Epistemology requires us to map our degrees of belief to the probability values. But there will be a lot of things that we don't know - enough to make any probability assignments to be unreliable. Unless we are Omniscient, we can't use Bayesian Epistemology.

### Prediction vs Accommodation

If our theory predicts something - and that something actually happens, that should increase our degree of belief in the theory. Compare this to creating a theory that accommodates/explains something that has already happened. The theory that predicted and proven true should have more weight. But acc. to Bayesian Epistemology, both have the same value.

## Problem of the Priors

We can use Bayesian Epistemology to determine the Probability of an outcome - but this will only work if the probability assigned to all linked events and theories are correct. Bayesian Epistemology does to validate those probabilities.

- Uncertain Evidence
- Problem of Old Evidence
- Problem of new theories
