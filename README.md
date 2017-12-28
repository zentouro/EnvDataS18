# Environmental Data Analysis

| Name              | Role      | UNI     |
|-------------------|-----------|---------|
| Upmanu Lall       | Professor | ula2    |
| James Doss-Gollin | TA        | jwd2136 |

## Learning Objectives

_cute blurb about environmental data_

- Data Science:
  - Read data from common formats into **R**
  - Use `Rmarkdown` to generate reproducible data analysis
  - Clean, filter, subset, sort, and group data using `dplyr`
  - Visualize data using `ggplot2` to gain insight into the relationships between different variables
- Probability:
  - Know common probability distribution functions and the processes they model
  - Sample from a known probability distribution function
  - Sample from an unknown probability distribution
  - Assess the probability that a data sample is from a particular (posited) distribution
  - Compare two different samples and assess the probability that they are from the same distribution
- Estimation:
  - Calculate and interpret moments of data and other summary statistics
  - Use moments of data to estimate the parameters of a statistical model
  - Write down the optimization problem which maximum likelihood methods solve
  - Use maximum likelihood to estimate the parameters of a statistical model
  - Understand Bayes' rule
  - Understand advantages and disadvantages of moment-based estimators, maximum likelihood estimators, and Bayesian estimators
- Modeling:
  - Write probability models for a known processes
  - Posit a (reasonable) probability model for an unknown process and write the full model
  - Know when Gaussian approximations to other statistical distributions are valid and what their benefits are
  - Use parametric (generalized linear models) and semi-parametric/non-parametric (kernel, spline, or local regression models) for approximating data-generating processes and know advantages and limitations of each approach
- Model Selection and Troubleshooting:
  - Identify serial correlation in data
  - Identify variable dependence in data
  - Comparing two different models (of the same data)
  - Use ridge regression, step regression, and LASSO for variable selection, and know what quantity each maximizes or minimizes
  - Interpret $p$-values from a regression
  - Use simulations from the fitted model (posterior predictive distribution) and $T$-tests to assess the fit of the model to data
- Conditional Simulation:
  - Write generalized regression and kriging models as probability models
  - Apply kriging models to account for spatial correlation
  - Apply local regression models to account for spatial correlation
  -

### Pre-Requisites

## Organization

### Course Communication

Course files will be posted on the course `GitHub` page.
All class communication will be conducted through the Slack channel.
Please read [this article](https://www.techrepublic.com/article/slack-goes-to-college-how-it-can-improve-the-classroom-experience/) to learn why we are using Slack for communication.
While the direct (private) messages are a great feature, please try to ask questions about course content in a public thread so that others can view and comment.

## Grading

The final grade will be determined by homework assignments (70%) and a final project (30%)

Assignments will use the **R** programming language.
We do not expect that you have used **R** before, but if you have not done any simple programming in the past you should be expected to do some extra work in the first weeks of the semester to catch up.

Computational assignments are to be written as executable [`Rmarkdown`](rmarkdown.rstudio.com/) files which contain blocks of code, text, and code output (i.e. graphics) in a single document.
Please turn in the `.Rmd` file and the `.html` output file that it generates.

## Textbooks

In this course we will not use any single textbook exhaustively, but will draw from the following textbooks.
Readings will be announced on the syllabus and in class.
Some readings may be posted on Courseworks if we cannot legally distribute them outside the Columbia community, but these will be announced in class and on Slack.

- Your first reference for anything related to programming, visualizing, or working with data in the R language is the R for Data Science book, available free online at [the author's website](http://r4ds.had.co.nz/).  Reference this book for questions about reading data into R, using `Rmarkdown`, filtering and cleaning data, plotting data, dealing with dates, or dealing with strings.
- The book [An Introduction to Statistical Learning](http://link.springer.com/10.1007/978-1-4614-7138-7) is also available for free and is worth downloading. This book is focused on machine learning (which has not been clearly separated from the field of statistics) and has detailed mathematical information on many common machine learning algorithms. If you are interested in a particular topic or procedure, you should look it up here.

The following textbooks may be useful in your life and may be useful in small doses, but will not be required reading.

- Richard McElreath's [Statistical Rethinking](http://xcelab.net/rm/statistical-rethinking/) is an excellent introduction course in Bayesian Data Analysis and statistical thinking in general. It is, however, designed to be a course so you'll want to start from the beginning.
