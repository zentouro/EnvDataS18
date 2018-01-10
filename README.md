# Course Syllabus: Environmental Data Analysis

- Course number: EAEEE 4257
- Instructor: Upmanu Lall (ula2)
- TA: James Doss-Gollin (jwd2136)
- Meetings: Monday and Wednesday, 2:40pm to 3:55pm in Mudd Building Room 633
- Office Hours: TBD

## Summary

This course will provide students with an understanding of fundamental statistical concepts for understanding and modeling environmental data.
In this class we will focus on analyzing and modeling such data sets with a focus on space and time variations, and potential inter-relations between variables.
The aim is to help students develop a conceptual understanding of statistics, rather than memorizing a set of routines and methodologies.
You should take this class if you would like to learn:

- How to think about statistical data and their analysis in the context of typical environmental problems
- Key techniques in statistical modeling and machine learning, their underlying ideas and  applicability, and how to use them
- How to build, select, and check statistical models using modern computational techniques
- How to address core challenges in environmental data analysis, including spatial correlation, structured time series behavior, changepoints, and trends

Above all, students who take this course will learn to think critically about environmental data and models, and will be able to understand and discuss conceptually the limitations of models they use or encounter "in the wild".

## Pre-Requisites

There are three pre-requisites for this course:

- a first course in  probability, statistics, econometrics, or similar;
- some exposure to linear algebra;
- and some experience writing programs on a computer (in any language)

If you are missing one or more of these pre-requisites but would still like to take the class, it is very much possible but may lead to some additional work, particularly during the first weeks of the semester.
**Homework 0**, which we will post before the first class date, will cover review material and which will allow you to determine whether this class is a good fit for your needs and abilities.
If you're not sure whether this class is a good fit for you, please contact us!

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
-  Homework (50%) will contain both written and **R** data analysis elements. This is due on Courseworks at the beginning of class on the due date. Homeworks will be due approximately every two weeks.
- Final Exam (20%) will be given as a take-home exam during finals week.
- Final Project (30%) will begin at the beginning of the semester, will have check-ins throughout the semester, and will be due during finals week.

More information on the final project and final exam will be provided later in the semester.

### Homework

Students  are  encouraged  to  work  together,  but  **homework  write-ups  must  be  done  individually and  must  be  entirely  the  author’s  own  work.**
If you're not sure what this means, please contact the TA.

Homework is due at the beginning of the class for which it is due.
Late homework will receive a penalty of 10% per day late, and will never be accepted more than a week after it is due because we will discuss the answers in class.

All homework must be turned in online through Courseworks.
To receive full credit, students must thoroughly explain how they arrived at their solutions.
If the homework is computational (as most will be), it should be turned in as a `Rmarkdown` (`.Rmd`) file, along with the `.html` file which is the result of running it.
If the homework is not computational, it should be turned in as a `.pdf` file.
Printed homework will not be accepted.

### Final Exam

A take-home final exam will be assigned during the final exam period.
The final exam will focus special topics discussed during the last weeks of class.

### Final Project

All students will complete a final project of their design.
Students will pick an environmental data analysis problem of interest to them and use the tools learned in class to explore it.
Students will choose a topic before spring break, and the final project write-up will be due on the last day of class.
We will use the final exam period for student project presentations.

## Computing

All computation in this course will be done in the **R** language, and in particular we will use the ["tidyverse"](https://www.tidyverse.org/) package ecosystem wherever possible.
This is not to say that other languages or frameworks are not helpful -- we regularly other languages and other sets of packages.
However, we feel that the wide availibility of statistical methods already implemented in **R**, the interactive `RStudio` environment, and easy-to-learn `tidyverse` packages give us the most "bang for our buck".

We do not expect that students enrolling in this class have used **R** before.

## Topics

Lectures will focus on statistical methods, but tailored for common scenarios and challenges in the analysis of environmental data.
We will split the course into approximately 4 topics as follows:

### Pre-Requisites

These topics are pre-requisites for the course and will _not_ be covered.
We will post a **Homework 0** prior to the first day of class so that you can assess your knowledge.

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
- Quantitative (R-squared, RMSE, AIC, BIC, Deviance) and qualitative comparisons between models
- Principal components analysis (PCA)
- Step regression
- Automated variable selection (i.e. Ridge/LASSO regression)
- Posterior predictive checks and T-tests
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
- Gridded data

## Schedule

The approximate schedule follows, but may change over the course of the semester.

**Lecture**|**Date**|**Assignments**|**Theme**|
-----|-----|-----|-----|
1|Wednesday, January 17, 2018| |Course outline & motivation
2|Monday, January 22, 2018|HW0 due|Fundamentals of probability
3|Wednesday, January 24, 2018| |Fundamentals of probability
4|Monday, January 29, 2018| |Fundamentals of probability
5|Wednesday, January 31, 2018| |Fundamentals of probability
6|Monday, February 5, 2018| |Modeling toolbox
7|Wednesday, February 7, 2018|HW1 due|Modeling toolbox
8|Monday, February 12, 2018| |Modeling toolbox
9|Wednesday, February 14, 2018| |Modeling toolbox
10|Monday, February 19, 2018| |Modeling toolbox
11|Wednesday, February 21, 2018|HW2 due|Modeling toolbox
12|Monday, February 26, 2018| |Model checking & selection
13|Wednesday, February 28, 2018| |Model checking & selection
14|Monday, March 5, 2018| |Model checking & selection
15|Wednesday, March 7, 2018|HW3 due|Model checking & selection
16|Monday, March 12, 2018| |SPRING BREAK
17|Wednesday, March 14, 2018| |SPRING BREAK
18|Monday, March 19, 2018| |Model checking & selection
19|Wednesday, March 21, 2018| |Model checking & selection
20|Monday, March 26, 2018| |Special topics
21|Wednesday, March 28, 2018|HW4 due|Special topics
22|Monday, April 2, 2018| |Special topics
23|Wednesday, April 4, 2018| |Special topics
24|Monday, April 9, 2018| |Special topics
25|Wednesday, April 11, 2018|HW5 due|Special topics
26|Monday, April 16, 2018| |Special topics
27|Wednesday, April 18, 2018| |Special topics
28|Monday, April 23, 2018| |Special topics
29|Wednesday, April 25, 2018| |Special topics
30|Monday, April 30, 2018|Final project due|
 |Final exam period (TBD)|Final project presentation|
 |5/11/18|Take-home final exam due|

## Textbooks and References

We will not follow a single textbook, but the following sources are helpful.
Specific readings may be assigned throughout the semester, and these will be announced on Slack.

- R for Data Science by Hadley Wickham, available free online at [the author's website](http://r4ds.had.co.nz/) should be your primary reference for **R**; it covers reading data into **R**, plotting with `ggplot2`, selecting and grouping data with `dplyr`, writing functions, and much more.
- The [free edX course](https://www.edx.org/course/data-science-r-basics-harvardx-ph125-1x-0) "R Basics" is recommended to those who wish to gain further experience with **R**
- Zico Kolter's [Linear Algebra Review and Reference](http://cs229.stanford.edu/section/cs229-linalg.pdf) is an excellent reference for those who have had some exposure to linear algebra but are feeling a bit rusty
- the MIT OCW class [18.05](https://ocw.mit.edu/courses/mathematics/18-05-introduction-to-probability-and-statistics-spring-2014/syllabus/) by  Jeremy Orloff and Jonathan Bloom is a fantastic introduction to probability and statistics, and review of their lecture slides is highly encouraged
- An Introduction to Statistical Learning, by James et al (2013) is available for free through the Columbia library and has a comprehensive (and faily mathematical) treatment of many machine learning algorithms, going far beyond what we will cover in this course.
- Andrew Gelman's "Data Analysis using Regression and Multilevel/Hierarchical Models" may be helpful, particularly for topics on model checking and selection, but is not required. The book website is [here](http://stat.columbia.edu/~gelman/arm/).
- Helsel, D.R. and R. M. Hirsch, 2002. Statistical Methods in Water Resources Techniques of Water Resources Investigations, Book 4, chapter A3. U.S. Geological Survey. 522 pages. Freely available at [https://pubs.usgs.gov/twri/twri4a3/](https://pubs.usgs.gov/twri/twri4a3/). This book is a very traditional approach to statistical analysis of hydrologic timre series.

Another good way to build your skills in **R**, data science, and statistics is to follow good blogs and potentially twitter feeds.
There are also online web communities for beginning programmers, statistitians, and for more advanced debugging of computer issues.
Some resources that may be particularly worth checking out are:

- The [RStudio Community Page](https://community.rstudio.com/) has great information on getting started using **R**.
- If you search for **R** problems online, you will almost certainly come across [Stack Overflow](https://stackoverflow.com/) or [Stack Exchange](https://stackexchange.com/). These are great resources but _please be careful_ posting on these sites. They take their rules very seriously and if you write a question that is not properly formatted or is a duplicate of an existing question, people will shut you down and are not friendly. I recommend posting your questions on the `r-computing` slack channel before posting on these sites. You can, however, learn a lot by browsing other peoples' questions.
- The [blog](http://andrewgelman.com/) of Andrew Gelman, a statistics professor at Columbia, focuses on Bayesian data analysis and critiques of applied statistics. The tone can be a bit hard to follow -- you may not always be sure if he is joking -- and some of the topics are more advacned than what we will cover in this class
- Twitter user [`@dataandme`](https://twitter.com/dataandme) searches out and retweets the best posts on data science, particularly using **R**
- Twitter user [`@JennyBryan`](https://twitter.com/JennyBryan) is a statistics professor who posts about basic ideas around computing and statistics
- Many people use the twitter hashtag `#rstats` to post interesting statistical analyses in **R**
- The [r-bloggers](https://www.r-bloggers.com/) website collects blogs from over 750 different contributors who use **R** to do interesting analyses -- you can often learn a lot by reading their code and looking at their results.
- Ryan Abernathey's (Columbia professor) [Research Computing for the Earth Sciences](https://rabernat.github.io/research_computing/) course covers python, Fortran, C, and a bunch of useful data science skills that we _won't_ be covering here

There are many more resources out there, but it's worth checking these out before madly googling things.
However, if you find any other great resources, please share them on the Slack `# random` channel!

### Data Camp

The fastest and most painless way to learn **R** is through [datacamp.com](https://www.datacamp.com/).
This is a great way to learn **R**, because it is interactive, the lessons are of a high quality, and you do not need to install **R** before you start learning.
As part of the homeworks 1 and 2, you will be asked to:

- create a _paid_ account on data camp
- Take several online courses (will be specified)
- Turn in the certificate of completion

Once the semester begins, we will provide you with a code for free access to Data Camp this semester -- you do not need to create your own premium (paid) account.
Thanks to Data Camp for sponsoring this course!
