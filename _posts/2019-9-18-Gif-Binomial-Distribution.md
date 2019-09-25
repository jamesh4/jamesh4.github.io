---
layout: post
title: The Binomial Distribution
---

The binomial distribution is one of the most commonly seen and used statistical distributions with a variety of applications.

The binomial distribution is a discrete probability distribution simulating a specified number of random events with a chance of a certain outcome happening.

It takes two parameters, p and n, and is commonly written as Bin(p, n).
p represents the chance of the event happening during a trial, and 1-p is the chance of the event not happening, given that 0 =< p =< 1.
n represents the number of times the run will be simulated.

The mean of a binomial distribution is pn, and the variance is np(1-p).

You can think of it as flipping a rigged coin with p chance of heads, for n times.

It's commonly used children/variations include the Bernoulli distribution and the multinomial distribution.

There are many ways to use the binomial distribution in real life, as it is a simple way to model an event with two outcomes; although it makes the assumption that the two outcomes are truly random, and independent of each other.

A way to apply the binomial distribution could be to calculate the expectation and variance of profits with certain casino games that are entirely up to chance, such as roulette. This could be further expanded to games which are not purely random, such as blackjack, but with a large enough sample size of primarily unskilled players whose win/loss is essentially random, the binomial distribution can still be applied.

For example, a bank giving out a loan to an investor to open a new casino needs to analyze whether or not this investment is likely to be sound, and the loans repayable. Given that they know roughly the amount of traffic that would be going through this casino, the house edge on each of the games, and each of the games' popularity, they can use a sum of binomials to calculate the mean and the variance of the revenue of the casino, with the few mentioned underlying assumptions. Then they can use these numbers to calculate the risk of the loan defaulting against the potential interest earned and decide whether or not to give out the loan.

When the sample size (n) of a binomial distribution is sufficiently large, a normal distribution can be used an approximation of the binomial distribution with parameters N(np, np(1-p)) -- the mean and variance of a binomial distribution as mentioned earlier. Advantages of using a normal approximation include but not limited to: the symmetrical bell shape with standard confidence intervals, and wide use in the industry due to its ability to approximate a large variety of distributions.