# Probability Theory

## Introduction to Series

This is the first article in a series of articles under the category - **Topics in Mathematics with their applications in Finance** based 
on a course by the same name at MIT. 
This is going to be a series of articles explaining concepts of mathematics for their applications in **Modern Finance**. One should agree 
that mathematics is deep and they have a full-fledged degree for it. So it is obvious that this article isn’t going to be exhaustive, 
however, it will be sufficient for us to deal with complex, volatile financial data and models. 


## Probability

This article assumes a college first-year understanding of probability and statistics by Indian standards.

### Introduction to Random Variables

Random variables are confusing when heard for the first time in a sense that we might think about them just like we think about other
mathematical variables (like ‘x’ we solve for in linear algebra). However, a random variable as the name suggests doesn’t have a constant
real value. They are essentially some random functions and hence have completely ‘random’ values. For example, the outcome of a coin toss
is a random variable. The weight of a random person on earth is a random variable. Random variables come in 2 categories.

* **Discrete Random Variables** : As the name suggests, these variables have particularly discrete values. That is the total values they 
assume can be counted - they can be large like millions, billions but still exactly countable.
* **Continuous Random Variables** : These are random variables which have infinitely many values. Like the set ![r](https://latex.codecogs.com/gif.latex?%5Cinline%20%5Cdpi%7B100%7D%20A%20%5Cepsilon%20%5B0%2C1%5D).

## Probability Density Function and Cumulative Density Function

Variables like the outcome of a coin toss are discrete variables and hence we can exactly know the probability of each possible outcome.
A plot between the discrete variable and its probability is known as Probability Mass Function. It is given by some ![y](https://latex.codecogs.com/gif.latex?%5Cinline%20%5Cdpi%7B100%7D%20f_%7BX%7D%20%3A%20%5COmega%20%5Crightarrow%20R_%7B%5Cgeq%200%7D)
satisfying ![y](https://latex.codecogs.com/gif.latex?%5Cinline%20%5Cdpi%7B100%7D%20%5Csum_%7B%5COmega%20%7D%5E%7B%7Df_%7BX%7D%28x%29%20%3D%201).
An example is given as follows : <br /> <br />
![u](https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20f_%7BX%7D%28x%29%20%3D%20%5Cleft%5C%7B%5Cbegin%7Bmatrix%7D%201/3%20%26%20x%20%3D%201%20%5C%5C%202/3%20%26%20x%20%3D%20-1%5C%5C%200%20%26%20otherwise%20%5Cend%7Bmatrix%7D%5Cright.)

