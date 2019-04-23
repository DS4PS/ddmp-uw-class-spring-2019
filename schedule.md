---
layout: schedule
title: Schedule
---
 
<!--- 
New sections start with 2 stars:  ** Section Title
New units start with 3 stars:     *** {Unit Metadata}
-----------------------------start example
** Section-I
*** { @unit = "15th Nov", @title = "Course Overview", @reading, @lecture, @assignment, @foldout }
-----------------------------end example
Unit Metadata is comprised of:
@unit - date or number
@title - unit name
@reading - turn on reading icon
@assignment - turn on lecture icon
@lecture - turn on lecture icon
@foldout - activate unit content (allow foldout)
-->



** Prerequisites


*** { @unit = "Prior to April 1st", @title = "Why Learn R", @reading, @foldout }


# Why Learn R (or Python)?

Data programming languages are different from traditional programming languages. They were designed to make data analytics fast and powerful. R and Python are two of the primary tools of the data science communities.

<iframe src="https://player.vimeo.com/video/180644880" width="800" height="440" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

[Past and Future of R](https://www.stat.auckland.ac.nz/~ihaka/downloads/Interface98.pdf)

This course focuses on R and Markdown (not quite a language, but a formatting convention for data-driven documents). Python and Notebooks are similar tools that you will encounter in this space, and they are somewhat interchangeable. If you start out as a computer scientist or engineer and evolve into working in the data science space you will likely use Python. If you start as as a social scientists or a statistician and venture into the data science space chances are you are using R. The differences between the two is more cultural than practical.



*** { @unit = "", @title = "Installation", @reading, @foldout }

# Installing R and R Studio

Go to [r-project.org](https://www.r-project.org/) to find instructions for downloading R. R is necessary for your computer to operate R Studio.

R Studio is an integrated development environment (IDE) for R which we'll be using in the class. Once R is downloaded download [R Studio](https://www.rstudio.com/). Both are free.


*** { @unit = "", @title = "Getting Started with R", @reading, @foldout }

# Getting Familiar with R

If this is your first time working with R, we recommend spending 4 hours to work through some of these examples to become familiar with the syntax and basic data structures:

[Introduction to R](https://www.datacamp.com/courses/free-introduction-to-r)



** Section-I Course Overview


*** { @unit = "1st April", @title = "Intro to Data-Driven Management and Policy", @reading, @lecture, @assignment, @foldout }

# Topics

* Introduction to the course
* Overview of R, R Studio, and Markdown,
* Uses of data in public management


# Readings

### Required

Textbook: [Chapter 1](https://ds4ps.org/Data-Science-Class/TEXTBOOK/docs/introduction-to-r.html)

[R Markdown: The bigger picture - Garrett Grolemund](https://resources.rstudio.com/rstudio-conf-2019/r-markdown-the-bigger-picture)

[Markdown Basics](https://ds4ps.github.io/data-driven-management-textbook/markdown/)

### Suggested

[The Promise of Big Data ](https://www.theregister.co.uk/2017/06/07/go_small_on_big_data/)

[Go Small on Big Data](https://www.theregister.co.uk/2017/06/07/go_small_on_big_data/)

[Becoming a Data Drive Org](https://sloanreview.mit.edu/case-study/lessons-from-becoming-a-data-driven-organization/)

# Lab

[Overview](labs/Lab_01_Overview_and_Example.html)

[Template](labs/Lab-01-Template.Rmd)


# Class Examples

[Powerpoint](https://github.com/DS4PS/ddmp-uw-class-spring-2019/blob/master/Reading/Lecture%2001%20-%20Introduction%20to%20the%20Class.pptx)

[Recording of Lecture](https://asu.zoom.us/recording/play/EKu_Dv5Gp7k452S5v5y_o_pYEKuHUNPpn7FT0yoHW2M3-rcrd5wN1nOaU_n1XWqq?continueMode=true)


** Section-II Data Programming



*** { @unit = "8th April", @title = "R Basics", @reading, @lecture, @assignment, @foldout }

# Topics

* Data types in R
* Ways  of  collecting  data:  passive,  active,  administrative  intro  to  life  logging  and  semester project.
* Design of Experiments.

# Readings

### Required

[Getting Started on Quantified Life](https://quantifiedself.com/get-started/)

[Reality Mining](https://github.com/DS4PS/ddmp-uw-class-spring-2019/blob/master/Reading/Reality_Mining_Chapter%201pdf.pdf)

[TED - What to Do With Big Data](https://www.ted.com/talks/susan_etlinger_what_do_we_do_with_all_this_big_data)

[Managerial Experiments](https://github.com/DS4PS/ddmp-uw-class-spring-2019/blob/master/Reading/Appendix%20A%20-%20Experiment%20Design%20(1).pdf)

### Suggested

[Challenges of Harnessing Data](https://sloanreview.mit.edu/case-study/lessons-from-becoming-a-data-driven-organization/)

[Abundant Data by Itself Solves Nothing ](https://graymattersystems.com/cio-survey-reveals-challenges-opportunities-potential-industrial-big-data/)

[Big Data: The Management Revolution](https://github.com/DS4PS/ddmp-uw-class-spring-2019/blob/master/Reading/Big%20Data_%20The%20Management%20Revolution.pdf)

[Building a Learning Organization](https://hbr.org/1993/07/building-a-learning-organization)

# Lab

[Lab for Homework](https://github.com/DS4PS/ddmp-uw-class-spring-2019/blob/master/labs/Lab%2002%20Template.Rmd)

# Class Examples

[In Class Work](https://github.com/DS4PS/ddmp-uw-class-spring-2019/blob/master/labs/In%20Class%202.Rmd)

[Recording of Lecture](https://asu.zoom.us/recording/share/xiGjNWxnP33Y4xIjbacyfFtMOABFywTfFfquD3urC1E?startTime=1554767802000)

[Powerpoint](https://github.com/DS4PS/ddmp-uw-class-spring-2019/blob/master/Reading/Lecture%2002%20-%20Intrroduction%20to%20Experiments.pptx)


*** { @unit = "15th April", @title = "Data Structures in R", @reading, @lecture, @assignment, @foldout }

# Topics

* Lists 
* Vectors 
* Data frames 

# Readings

### Required

Textbook: [Chapter 2-3](https://ds4ps.org/Data-Science-Class/TEXTBOOK/docs/data-types.html)

### Suggested

[Data Sources from Lab 2](https://github.com/DS4PS/ddmp-uw-class-spring-2019/blob/master/Reading/Lab%20Assignment%202%20Data%20Sources.pdf)

# Lab

[Lab for Homework](https://escience.washington.edu/wp-content/uploads/2019/04/Session3_DataStructures_LAB.html)

# Class Examples
<a href="https://escience.washington.edu/wp-content/uploads/2019/04/Session3_DataStructures.html" target="_blank">Lesson code</a>

<br>
* [download ALL files for session 3](https://github.com/EvansDataScience/DataDriven_ManagementAndPolicy/raw/master/Session3.zip)

[Recording of Lecture](https://asu.zoom.us/recording/share/QZZRh26ZkHz4KYkKbm5QLGrpUWmBsz-UQGd_p_N5t0-wIumekTziMw)


*** { @unit = "22th April", @title = "Working with Data Frames", @reading, @lecture, @assignment, @foldout }

# Topics

* Logical operators
* Control of execution
* Functions

# Readings

### Required

Textbook: [Chapter 4-8](https://ds4ps.org/Data-Science-Class/TEXTBOOK/docs/logical-statements.html)


### Suggested

# Lab

[Lab for Homework](https://escience.washington.edu/wp-content/uploads/2019/04/session4_LAB.html)



# Class Examples

<a href="https://escience.washington.edu/wp-content/uploads/2019/04/session4_DataFrame.html" target="_blank">Lesson code</a>


* [download ALL files for session 4](https://github.com/EvansDataScience/DataDriven_ManagementAndPolicy/raw/master/session4.zip)

[Recording of Class](https://asu.zoom.us/recording/share/UzY4YVDixOsmkCU5LlA7JqVNpZuT0f6jfg8ICmtwaquwIumekTziMw)

*** { @unit = "29th April", @title = "Intro to Visualization", @reading, @lecture, @assignment, @foldout }

# Topics

* Visualization guidelines 
* R and the grammar of graphics 

# Readings

### Required

Textbook: [Chapter 9-11](https://ds4ps.org/Data-Science-Class/TEXTBOOK/docs/the-plot-function.html)


### Suggested

# Lab

# Class Examples



*** { @unit = "6th May", @title = "Spatial and Multidimensional visualization", @reading, @lecture, @assignment, @foldout }

# Topics

* Bivariate and multivariate plots
* Mapping in R

# Readings

### Required

### Suggested

# Lab

# Class Examples

** Section-III Dashboards




*** { @unit = "13th May", @title = "Dynamic visualization", @reading, @lecture, @assignment }

# Topics

* The design and construction of dashboards.

# Readings

### Required

### Suggested

# Lab

# Class Examples

*** { @unit = "20th May", @title = "Analyzing Managerial Experiments", @reading, @lecture, @assignment }

# Topics

* Analysis of experiments
* Testing outcomes in R

# Readings

### Required

### Suggested

# Lab

# Class Examples

*** { @unit = "27th May", @title = "MEMORIAL DAY" }

# No Classs

Instructions will be given on what to do for this week.




*** { @unit = "3rd June", @title = "Dashboards II", @reading, @lecture, @assignment }

# Topics

* Shiny widgets.
* Advanced dashboards.

# Readings

### Required

### Suggested

# Lab

# Class Examples

*** { @unit = "10th June", @title = "FINAL PROJECTS DUE", @assignment }

# Instructions











***  


