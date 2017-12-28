# Environmental Data Analysis Course Syllabus

| Name              | Role      | UNI     |
|-------------------|-----------|---------|
| Upmanu Lall       | Professor | ula2    |
| James Doss-Gollin | TA        | jwd2136 |



## Course Overview

Sensors, satellites, cell phones, and manual recordings provide large quantities of data about the climate, water, natural resources, ecology, and human behavior.
In this class we will focus on analyzing and modeling such data sets with a focus on space and time variations, and potential inter-relations between variables.
You should take this class if you would like to learn:

- How to think about statistical data and their analysis in the context of typical environmental problems
- Key techniques in statistical modeling and machine learning, their underlying ideas and  applicability, and how to use them
- Building, selecting, and checking statistical models in an applied, computational context

## Pre-Requisites

The **pre-requisites** for this course are a first course in probability and statistics, a course in linear algebra, and some experience writing simple programming scripts.
If you are missing one or more of these pre-requisites but would still like to take the class, please contact us.
You should anticipate additional work in this case.
We will provide a Homework 0 before the first class date to allow you to evaluate your background.

## Learning Objectives

Environmental data analysis is a large and complex topic, covering much more material than we can hope to learn in a single semester.
With this in mind, I have tried to clarify our course’s learning goals using [Bloom’s taxonomy](https://en.wikipedia.org/wiki/Bloom%27s_taxonomy).
Education research has demonstrated that students learn best when the learning goals are clearly articulated.
These may be updated over the course of the semester.

The semester will be divided into three main units, which we will go through somewhat out of order:

### Foundations of Statistics and Data Science

#### Data Science

Since it is difficult to learn to program from a lecture, we will review this material only briefly.
You will be expected to use the references below throughout the semester.
We will assign homeworks in which you will:

- install and load packages into **R**
- import data from plain-text formats (`.tsv`, `.csv`, `.txt`) into **R**
- download data directly from the web and read it into **R**
- use the **R** `?` function to get help with functions or packages
- write scripts and use `Rmarkdown` to generate reproducible data analysis
- clean, filter, subset, sort, combine, and group data using `dplyr`
- create visually appealing plots using `ggplot2`
- write functions in **R** for repeatable data analysis

References:

- R for Data Science by Hadley Wickham, available free online at [the author's website](http://r4ds.had.co.nz/).
- Data Science: R Basics [free edX course](https://www.edx.org/course/data-science-r-basics-harvardx-ph125-1x-0). It is highly encouraged that work through this course, as there will be a homework drawing heavily from it.

#### Linear Algebra

We will pay minimal attention to linear algebra in class, as it is an expected pre-requisite.
To complete homeworks you should know how to:

- transpose a matrix
- multiply two matrices
- know what a matrix inverse is and perform the inversion analytically or using a computer
- know what the eigenvalues and eigenvectors of a matrix are, and calculate them analytically or using a computer

References:

- Zico Kolter's [Linear Algebra Review and Reference](http://cs229.stanford.edu/section/cs229-linalg.pdf) is an excellent reference for those who have had some exposure but need to review core concepts

#### Probability:

We will review introductory probability theory in class.
You will learn how to:

- write the range and nature (discrete or continuous) of common probability functions (Normal, Beta, Binomial, Bernoulli, Poisson, Gamma)
- use the `rnorm`, `rbeta`, etc function to generate random samples from a known probability distribution function
- use the `qnorm`, `dnorm`, and `pnorm` functions (and corresponding functions for other probability distributions)
- assess the probability that a data sample is from a specified distribution
- Compare two different samples and assess the probability that they are from the same distribution

References:

- Grinstead and Snell's [Introduction to Probability](http://www.stat.yale.edu/~jtc5/251/readings/ProbabilityBook_GrinsteadSnell.pdf), and in particular chapters 1, 2, 5, 6

### Statistical Model Building

### Models for Environmental Data

### Estimation:

- Calculate and interpret moments of data and other summary statistics
- Use moments of data to estimate the parameters of a statistical model
- Write down the optimization problem which maximum likelihood methods solve
- Use maximum likelihood to estimate the parameters of a statistical model
- Understand Bayes' rule
- Understand advantages and disadvantages of moment-based estimators, maximum likelihood estimators, and Bayesian estimators


###  Modeling:

- Write probability models for a known processes
- Posit a (reasonable) probability model for an unknown process and write the full model
- Know when Gaussian approximations to other statistical distributions are valid and what their benefits are
- Use parametric (generalized linear models) and semi-parametric/non-parametric (kernel, spline, or local regression models) for approximating data-generating processes and know advantages and limitations of each approach

### Model Selection and Troubleshooting:

- Identify serial correlation in data
- Identify variable dependence in data
- Comparing two different models (of the same data)
- Use ridge regression, step regression, and LASSO for variable selection, and know what quantity each maximizes or minimizes
- Interpret $p$-values from a regression
- Use simulations from the fitted model (posterior predictive distribution) and $T$-tests to assess the fit of the model to data

### Conditional Simulation:

- Write generalized regression and kriging models as probability models
- Apply kriging models to account for spatial correlation
- Apply local regression models to account for spatial correlation

## Course Communication

Course files and code examples will be posted on our `Github` page (LINK!).

All course communication will be conducted through the slack channel at [envdataanalysis.slack.com](envdataanalysis.slack.com).
This will reduce the number of e-mails we all get and will encourage collaboration.
Please note:

- use the `general` channel sparingly -- we will post homework assignments and other essential logistics here
- use the `random` channel for interesting news articles you see or cool blog posts related to the course
- use the `math-stats` channel (you will need to join it!) for questions about probability and statistics
- use the `r-computing` channel for questions about **R** syntax, installation, packages, etc.
- use direct messages only if strictly necessary!

We will check the Slack page at least daily.

## Grading

The final grade will be determined by homework assignments (70%) and a final project (30%)

Assignments will use the **R** programming language.
We do not expect that you have used **R** before, but if you have not done any simple programming in the past you should be expected to do some extra work in the first weeks of the semester to catch up.

Computational assignments are to be written as executable [`Rmarkdown`](rmarkdown.rstudio.com/) files which contain blocks of code, text, and code output (i.e. graphics) in a single document.
Please turn in the `.Rmd` file and the `.html` output file that it generates.
