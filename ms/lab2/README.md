# Laboratory work nr. 2

### Deadlines
Group 1: March 19th, 02:00 GMT+2

Group 2: March 26th, 02:00 GMT+2

### Grading system

### What to do?
- 2 problems on **Densities**
- 1 problem on **Random Variables**
- 2 problems on **Important Distribution**
- 1 problem on **Continuous Conditional probability**

### 1. Densities
Take a stick of unit length and break it into two pieces, choosing the breakpoint at random. Now break the longer of the two pieces at a random point. What is the probability that the three pieces can be used to form a triangle?

Write a computer program that would simulate the experiment. Explain your results.

### 2. Densities
Three points are chosen at random on a circle of unit circumference. What is the probability that the triangle defined by these points as vertices has three acute angles?

### 3. Densities
Choose independently two numbers `B` and `C` at random from the interval `[-1, 1]` with uniform distribution, and consider the quadratic equation `X^2 + B*X + C = 0`. Find the probability that the roots of this equation

- are both real
- are both positive

### 4. Densities
At the Ziua Vinului, a coin toss game works as follows. Coins of `25 bani` are tossed onto a checkerboard. The management keeps all the coins, but for each coin landing entirely within one square of the checkerboard the management pays `1 leu`. Assume that the edge of each square is twice the diameter of a coin, and that the outcomes are described by coordinates chosen at random. Is this a fair game?

### 5. Densities

Write a program to carry out the following experiment. A coin is tossed `100` times and the number of heads that turn up is recorded. This experiment is then repeated `1000` times. Have your program plot a bar graph for the proportion of the `1000` experiments in which the number of heads is `n`, for each `n` in the interval `[35, 65]`. Does the bar graph look as though it can be fit with a normal curve?

### 6. Densities
At a mathematical conference, `10` participants are randomly seated around a circular table for meals. Using simulation, estimate the probability that no two people sit next to each other at both lunch and dinner. Can you make an intelligent conjecture for the case of `n` participants when `n` is large?

### 7. Random Variables
A game is played as follows: A random number X is chosen uniformly from `[0, 1]`. Then a sequence `Y1, Y2`, . . . of random numbers is chosen independently and uniformly from `[0, 1]`. The game ends the first time that `Yi > X`. You are then paid `(i - 1)` dollars. What is a fair entrance fee for this game?

### 8. Random Variables
An insurance company has `1000` policies on men of age `50`. The company estimates that the probability that a man of age `50` dies within a year is `0.01`. Estimate the number of claims that the company can expect from beneficiaries of these men within a year.

### 10. Important Distributions
Jora Petrovici never pays the *troleibuz* (cost = `2 lei` in Chisinau). He assumes that there is a probability of `0.05` that he will be caught by the *controlor*. The first offense costs `50 lei`, the second costs `150 lei`, and subsequent offenses cost `300 lei`. There’s also an empirically proven probability of `0.02` that the *taxatoarea* is a hairy muscular guy, which means that he’ll have to pay the 2 lei anyway. How does the expected cost of riding the *troleibuz* for a year (two times a day) without paying compare to the cost that is paid by us, law-abiding students?

### 11. Important Distributions
Assume that the probability that there is a significant accident in a nuclear power plant during one year’s time is `0.001`. If a country has `100` nuclear plants, estimate the probability that there is at least one Chernobyl (or Black Mesa) during a given year.

### 12. Important Distributions
Let `U` be a uniformly distributed random variable on `[0, 1]`. What is the probability that the equation `X^2 + 4U*X + 1 = 0` has two distinct real roots `x1` and `x2` ?

### 12. Continuous Probability
Suppose you toss a dart at a circular target of radius 10 inches. Given that the dart lands in the upper half of the target, find the probability that

- it lands in the right half of the target
- its distance from the center is less than 5 inches
- its distance from the center is greater than 5 inches
- it lands within 5 inches of the point (0, 5)

### 13. Continuous Probability
*Suppose we have a floor made of parallel strips of wood, each the same width, and we drop a needle onto the floor. What is the probability that the needle will lie across a line between two strips?*

This is known as the Buffon’s needle problem. Your task is to write a program that will estimate `π` using the Buffon method. Now google away.
