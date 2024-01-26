# Implementation of the Exponential Family with Examples



***STATUS:*** **Completed**


## Project Objectives:

The goal of the project was to demonstrate a set of statistical distributions from the exponential family. The main motivation for implementing the project was to create a convenient and practical cheat sheet with examples that may be encountered in practice. Next, I will demonstrate the results of the work on each distribution I have considered.

## Poisson Distribution: 

The Poisson distribution is useful in any scenario where you want to model the occurrence of independent events happening at a certain rate.

Let’s say you are looking at an intersection and expect cars to take a left turn at a rate of 5 per minute. You could calculate the probability of observing 3 cars turning left by using the Poisson distribution.

<img src="" alt="Poisson"/>

### Result of Poisson Distribution case:

The probability of obesrving 3 cars turning left at a intersection is equivalent to 14%

## Exponential Distribution: 

The exponential distribution models the time interval between continuously occurring, independent events. Exponential distribution models the wait time between events in a Poisson process.

Let’s assume that this function models the wait time for a bus arriving once per hour at a bus stop. If we wanted to calculate the probability that the bus arrives two hours or later, we could plug the following values into the function.

<img src="" alt="Exponential"/>

### Result of Exponential Distribution case:

Probability of observing a bus arriving at or after 2 hours of waiting is 13%

## Gamma Distribution: 

Assume you are waiting at a bus station. Busses are passing by at a rate of two per hour. You want to know the probability that you have to wait less than two hours until at least three busses have passed. The distribution of wait times for busses looks like this.

<img src="" alt="Gamma"/>

### Result of Gamma Distribution case:

The probability that 3 busses have passed by after two hours is 76% when the average arrival rate is 2 busses per hour.

## Beta Distribution: 

The beta distribution models a distribution of probabilities. If we don’t know the probability of the outcome of an event, we can use the beta distribution to model the distribution of probabilities given the prior information.

Let’s say you have 20 customers. 10 of them buy and 10 leave without buying.

<img src="" alt="Beta"/>

### Result of Beta Distribution case:

The average probability of making a purchase or conversion rate is now 50% (0.5). But 20 people isn’t a very reliable sample size. Your real probability of converting customers could be lower or higher.

## Geometric Distribution: 

The geometric distribution describes the probability of the number of failures before a successful outcome in a Bernoulli trial.

Suppose you are a recruiter and you need to find a suitable candidate to fill an IT job. Your chance that a suitable candidate will be interested is 15%. Let’s calculate the probability of finding a suitable candidate on the third attempt.

<img src="" alt="Geometric"/>

### Result of Geometric Distribution case:

Our chances of having at least one candidate who replies positively stand at almost 40%

## Project Tools

- Python
- Scipy.stats
- Numpy
- Matplotlib.pyplot
