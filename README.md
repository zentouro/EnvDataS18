# Course Syllabus: Environmental Data Analysis

- Course number: EAEEE 4257
- Instructor: Upmanu Lall (ula2)
- TA: James Doss-Gollin (jwd2136)
- Meetings: Monday and Wednesday, 2:40pm to 3:55pm in Mudd Building Room 633
- Office Hours: TBD

## Description

This course will provide students with an understanding of fundamental statistical concepts for understanding and modeling environmental data.
In this class we will focus on analyzing and modeling such data sets with a focus on space and time variations, and potential inter-relations between variables.
The aim is to help students develop a conceptual understanding of statistics, rather than memorizing a set of routines and methodologies.
You should take this class if you would like to learn:

- How to think about statistical data and their analysis in the context of typical environmental problems
- Key techniques in statistical modeling and machine learning, their underlying ideas and  applicability, and how to use them
- To building, select, and check statistical models in an applied, computational context

## Broad Course Objectives

Students who take this course should be able to:

- use the language and core concepts of probability theory;
- understand basic paradigms of statistical inference (both Bayesian and frequentist);
- use software (**R**) and simulation to *do* statistics;
- become an informed consumer of statistical information; and will
- refine their written and oral communication skills.

Above all, students should be able to think critically about environmental data and models, and understand and discuss conceptually the limitations of models they use or encounter "in the wild".

## Pre-Requisites

To enroll in this course, students ought to have taken a first course in  probability and statistics, a course in linear algebra, and have some experience in computer programming (in any language).
If you are missing one or more of these pre-requisites but would still like to take the class, please contact us.
You should anticipate additional work in this case.
We will provide a **Homework 0** before the first class date, which will cover review material and which will allow you to determine whether this class is a good fit for your needs and abilities.

## Grading and Academic Integrity


I take the honor code very seriously; students caught cheating or otherwise in violation will face disciplinary action.
Please note the Barnard honor code text:

> We...   resolve  to  uphold  the  honor  of  the  College  by  refraining  from  every  form  of  dishonesty  in  our
academic life.  We consider it dishonest to ask for, give, or receive help in examinations or quizzes, to use
any  papers  or  books  not  authorized  by  the  instructor  in  examinations,  or  to  present  oral  work  or  written
work  which  is  not  entirely  our  own,  unless  otherwise  approved  by  the  instructor....   We  pledge  to  do  all
that is in our power to create a spirit of honesty and honor for its own sake.”

See also [http://barnard.edu/node/2875](http://barnard.edu/node/2875) and
[https://www.college.columbia.edu/academics/academicintegrity](https://www.college.columbia.edu/academics/academicintegrity).

Your grade will be determined by three different components:
-  Homework (50%) will contain both written and **R** data analysis elements. This is due on Courseworks at the beginning of class on the due date. Homeworks will be due approximately every two weeks. **Homework 0** will be due after the first week of class.
- Final Exam (20%) will be given as a take-home exam during finals week.
- Final Project (30%) will begin at the beginning of the semester, will have check-ins throughout the semester, and will be due during finals week.

More information on the final project and final exam will be provided later in the semester.

### Homework

Students  are  encouraged  to  work  together,  but  **homework  write-ups  must  be  done  individually and  must  be  entirely  the  author’s  own  work.**
Homework is due at the beginning of the class for which it is due.
Late homework will receive a penalty of 10% per day late, and will never be accepted more than a week after it is due because we will discuss the answers in class.
To receive full credit, students must thoroughly explain how they arrived at their solutions.
All homework must be turned in online through Courseworks.
If the homework is computational (as most will be), it should be turned in as a `Rmarkdown` (`.Rmd`) file, along with the `.html` file which is the result of running it.
If the homework is not computational, it should be turned in as a `.pdf` file.
Printed homework will not be accepted.

## Computing


All computation in this course will be done in the **R** language, and in particular we will use the ["tidyverse"](https://www.tidyverse.org/) package ecosystem wherever possible.
This is not to say that other languages or frameworks are not helpful -- we regularly other languages and other sets of packages.
However, we feel that the wide availibility of statistical methods already implemented in **R**, the interactive `RStudio` environment, and easy-to-learn `tidyverse` packages give us the most "bang for our buck".

We do not expect that students enrolling in this class have used **R** before, but those who have not -- and particularly those who have never done any computer programming before -- should expect to do some additional work in the first weeks of the semester to make up this gap.

The fastest and most painless way to learn **R** is through [datacamp.com](https://www.datacamp.com/).
This is a great way to learn **R**, because it is interactive, the lessons are of a high quality, and you do not need to install **R** before you start learning.
As part of the course, you will be asked to:
- create a _paid_ account on data camp. You will only need to maintain your paid subscription for one month, at a cost of $25; we will not require you to purchase any other textbooks or materials. If the cost is a problem, please contact us ASAP.
- Take several online courses (will be specified)
- Turn in the certificate of completion


## Textbooks and References

We will not follow a single textbook, but the following sources are helpful.
Specific readings may be assigned throughout the semester, and these will be announced on Slack.

- R for Data Science by Hadley Wickham, available free online at [the author's website](http://r4ds.had.co.nz/) should be your primary reference for **R**; it covers reading data into **R**, plotting with `ggplot2`, selecting and grouping data with `dplyr`, writing functions, and much more.
- The  [free edX course](https://www.edx.org/course/data-science-r-basics-harvardx-ph125-1x-0) "R Basics" is highly encouraged. In particular, this course will be a key reference for Homework 1, which will focus on basic **R** concepts.
- Zico Kolter's [Linear Algebra Review and Reference](http://cs229.stanford.edu/section/cs229-linalg.pdf) is an excellent reference for those who have had some exposure to linear algebra but are feeling a bit rusty
- the MIT OCW class [18.05](https://ocw.mit.edu/courses/mathematics/18-05-introduction-to-probability-and-statistics-spring-2014/syllabus/) by  Jeremy Orloff and Jonathan Bloom is a fantastic introduction to probability and statistics, and review of their lecture slides is highly encouraged
- An Introduction to Statistical Learning, by James et al (2013) is available for free through the Columbia library and has a comprehensive (and faily mathematical) treatment of many machine learning algorithms, going far beyond what we will cover in this course.

## Course Communication

All course communication will be conducted through the slack channel at [envdataanalysis.slack.com](envdataanalysis.slack.com).
This will reduce the number of e-mails we all get and will encourage collaboration.
Please note:

- use the `general` channel sparingly -- we will post homework assignments and other essential logistics here
- use the `random` channel for interesting news articles you see or cool blog posts related to the course
- use the `math-stats` channel (you will need to join it!) for questions about probability and statistics
- use the `r-computing` channel for questions about **R** syntax, installation, packages, etc.
- use direct messages only if strictly necessary!

We will check the Slack page at least daily.

Course files and code examples will be posted on [our `Github` page](https://github.com/jdossgollin/EnvDataS18).

Assignments will be posted on Courseworks and must be turned in through Courseworks.
We will also use Courseworks to share any readings which we are not permitted to share publicly.
We will notify you through Slack whenever an assignment or reading is posted to Courseworks.

## Topics

Lectures will focus on statistical methods, but tailored for common scenarios and challenges in the analysis of environmental data.
In particular, environmental data typically varies over space and in time, and comes from processes which

### Pre-Requisites

These topics are pre-requisites for the course and will _not_ be covered.
We will post a Homework 0 prior to the first day of class so that you can assess your knowledge.

- Matrix and vector algebra
- Discrete probability distributions (particularly Bernoulli, binomial, and Poisson)
- Continuous probability distributions (particularly normal, exponential, and uniform)
- Sample Estimates
- Correlation and Covariance

### Fundamentals of Probability

We will spend 4-5 Lectures on these topics, which will provide us with a core background in probability and estimation:

- Nonlinear dynamics and the relationship between statistics and physics
- Functions and sums of random variables
- Moments of a distribution
- Bootstraps and NHST
- Comparing two samples
- Likelihood functions
- Maximum likelihood estimators
- Moment-based estimators
- Brief introduction to Bayesian estimation

### Modeling Toolbox

We will attempt to distill the wealth of statistical and machine learning tools available into 5-6 lectures on the most widely used and foundational techniques.
We will focus on both parametric and semi-parametric tools for function approximation:

- Linear Regression
- Multivariate Linear Regression
- Generalized Linear Models
- Kernels
- Local regression
- Splines (if time allows)
- Nearest-neighbor models

###  Model Selection and Checking

Real-world data analysis does not simply involve estimating one model, but rather selecting the most relevant variables and functional forms to use as well as the methods of approximation.
We typically want to maximize our ability to fit the data while avoiding over-fitting.
We will spend 3-4 lectures developing fundamental tools for selecting variables, comparing models, and identifying the limitations of our models:

- Residual plots
- Quantitative ($R^2$, RMSE, AIC, BIC, Deviance) and qualitative comparisons between models
- Principal components analysis (PCA)
- Step regression
- Automated variable selection (i.e. Ridge/LASSO regression)
- Posterior predictive checks and $T$-tests
- "The Garden of Forking Paths", overfitting, and perils of model selection

### Special Topics in Environmental Data Analysis

We will almost certainly not cover every topic below, but will go through those most relevant to student interest as time allows.
If we do not cover a particular topic but you would like to learn more about it, we will be happy to recommend relevant reading and guide you through it.

- Spatial processes and variograms
- Serial correlation, ARMA models, and spectral analysis
- Seasonality
- Changepoints and trends
- Nonstationarity
- Extreme value statistics
- Partial correlations and canonical correlation analysis
- Wavelet analysis
- Clustering and classification techniques
- Imputation and missing data models
- Latent variable models, HMM, NHMM, and EM
- Censored data regression
