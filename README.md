## Statistics
### Premier League Nmber of Goals Modelisation using Poisson Distribution

This repository contains the solutions to a Statistics Project, which consists of two independent problems related to Poisson distribution and its application to model the number of goals scored in football.

### Part 1: Estimating Parameters of a Poisson Distribution

In this part, we are asked to estimate the parameters of a Poisson distribution using maximum likelihood estimation (MLE) and method of moments. We also need to prove some theoretical results and compute the bias, variance, and quadratic risk of the MLE estimator.

The R Markdown file part1.Rmd contains the solutions to all the questions, along with explanations and code examples. The corresponding PDF file part1.pdf is also provided.

### Part 2: Application to Premier League Scores

In this part, we are asked to model the number of goals scored by the home team and the visiting team in the Premier League using a Poisson distribution. We need to fit the model to the data, compute the MLE estimators, and compare the performance of different teams.

The R Markdown file part2.Rmd contains the solutions to all the questions, along with explanations and code examples. The corresponding PDF file part2.pdf is also provided.

### Dependencies

To run the code in this repository, you will need to have the following software installed:

R (version 4.0.3 or higher)
RStudio (version 1.4.1106 or higher)
The following R packages: dplyr, ggplot2, tidyr, readr, knitr, kableExtra, tseries, forecast, tseries, vars, urca, lmtest, zoo
You can install the required packages by running the following command in R:


install.packages(c("dplyr", "ggplot2", "tidyr", "readr", "knitr", "kableExtra", "tseries", "forecast", "vars", "urca", "lmtest", "zoo"))
