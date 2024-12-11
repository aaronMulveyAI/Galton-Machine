README

Project: Distribution Simulations and Galton Board

This project is a comprehensive exploration of statistical concepts, focusing on the Beta distribution and the behavior of a Galton board. It combines mathematical derivations, visualizations, and simulations to demonstrate fundamental principles in probability and statistics.

Overview

The project is structured as follows:

Beta Distribution Analysis:

Finding the median of a Beta distribution with parameters  and .

Using numerical methods and graphical validation to verify the solution.

Developing a custom implementation of the Beta CDF without relying on built-in functions.

Galton Board Simulation:

Simulating the distribution of balls in a Galton board.

Demonstrating the Central Limit Theorem (CLT) by approximating the binomial distribution as normal for large sample sizes.

Visualizing biased and unbiased Bernoulli trials.

Features

1. Beta Distribution

Numerical Median Calculation:

Uses the bisection method via uniroot to find the median.

Implements a custom Beta CDF function to avoid built-in solutions.

Approximation:

Compares the numerical median with an approximation formula:

Error Calculation:

Quantifies the difference between the numerical median and its approximation.

2. Galton Board Simulation

Animation:

Simulates the Galton board in real-time, visualizing the paths of balls.

Generates a histogram of the final distribution.

Numeric Simulation:

Models the distribution using a sequence of Bernoulli trials.

Explores cases with fair () and biased (e.g., ) trials.

3. Central Limit Theorem (CLT)

Demonstrates that the binomial distribution approximates a normal distribution as  increases:

Usage

Requirements

R with the following libraries:

animation

knitr

Running the Code

Open the provided RMarkdown file (Assigment_3.Rmd) in RStudio.

Knit the file to HTML or PDF to generate a comprehensive report with interactive animations and plots.

Highlights

Beta Distribution Visualizations:

Graphs of the CDF help identify the median and validate results.

Comparisons between numerical and approximated medians.

Interactive Galton Board Animation:

Watch the balls fall through the Galton board and see how they accumulate in bins.

Histograms and Normal Approximation:

Observe how the distribution of balls converges to a normal distribution as the number of levels increases.

Author

Aaron Mulvey

Date: October 7, 2022

Feel free to reach out for questions or further discussions on this project!
