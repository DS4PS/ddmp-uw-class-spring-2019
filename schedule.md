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


*** { @unit = "Prior to April 1st", @title = "Why Learn R", @reading, @lecture, @assignment, @foldout }


# Why Learn R (or Python)?

Data programming languages are different from traditional programming languages. They were designed to make data analytics fast and powerful. R and Python are two of the primary tools of the data science communities.

<iframe src="https://player.vimeo.com/video/180644880" width="800" height="440" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

This course focuses on R and Markdown (not quite a language, but a formatting convention for data-driven documents). Python and Notebooks are similar tools that you will encounter in this space, and they are somewhat interchangeable. If you start out as a computer scientist or engineer and evolve into working in the data science space you will likely use Python. If you start as as a social scientists or a statistician and venture into the data science space chances are you are using R. The differences between the two is more cultural than practical.



*** { @unit = "", @title = "Installation", @reading, @lecture, @assignment, @foldout }

# Installing R and R Studio

asdfasfd....


*** { @unit = "", @title = "Data-Driven Documents with Markdown", @reading, @lecture, @assignment, @foldout }

[R Markdown: The bigger picture - Garrett Grolemund](https://resources.rstudio.com/rstudio-conf-2019/r-markdown-the-bigger-picture)


[Markdown Basics](https://ds4ps.github.io/data-driven-management-textbook/markdown/)



# My First Markdown File

asdfasdf


![](/assets/img/analysis_pipieline.png)




*** { @unit = "", @title = "Getting Started with R", @reading, @lecture, @assignment, @foldout }

# Getting Familiar with R

If this is your first time working with R, we recommend spending 4 hours to work through some of these examples to become familiar with the syntax and basic data structures:

[Introduction to R](https://www.datacamp.com/courses/free-introduction-to-r)

```
x <- 1:100
y <- 2*x + rnorm(100)
plot( x, y )
```

Example code...






** Section-I Course Overview


*** { @unit = "1st April", @title = "Intro to Data-Driven Management and Policy", @reading, @lecture, @assignment, @foldout }

# Topics

* Introduction to Markdown, R, and R Studio
* Uses of data in public management, reasons for doing experiments.




*** { @unit = "", @title = "Data-Driven Management", @reading, @foldout }

# Readings

## Textbook

Required: [Chapter 1](https://ds4ps.org/Data-Science-Class/TEXTBOOK/docs/introduction-to-r.html)

## Big Data: The Management Revolution

What's new here? Organizations have always used data, but the difference now is the (1) volume, (2) velocity, and (3) variety of data. 

"We can measure and therefore manage more precisely than ever before. We can make better predictions and smarter decisions. We can target more-effective interventions, and can do so in areas that so far have been dominated by gut and intuition rather than by data and rigor....The more companies characterized themselves as data-driven, the better they performed on objective measures of financial and operational results."

"Companies succeed in the big data era not simply because they have more or better data, but because they have leadership teams that set clear goals, define what success looks like, and ask the right questions...As data become cheaper, the complements to data become more valuable. Some of the most crucial of these are data scientists and other professionals skilled at working with large quantities of information. Statistics are important, but many of the key techniques for using big data are rarely taught in traditional statistics courses. Perhaps even more important are skills in cleaning and organizing large data sets; the new kinds of data rarely come in structured formats. Visualization tools and techniques are also increasing in value."

[cite](https://hbr.org/2012/10/big-data-the-management-revolution)


## The Promise of Big Data 

In 2017 The Economist declared, "Data is to this century what oil was to the last one: a driver of growth and change. Flows of data have created new infrastructure, new businesses, new monopolies, new politics and – crucially – new economics."

In 2011 McKinsey & Co. described big data as "the next frontier for innovation, competition, and productivity.” 

GE looked to big data to drive "changes as profound as industrialization... in the late 1700s".

[cite](https://www.theregister.co.uk/2017/06/07/go_small_on_big_data/)


## Challenges of Harnessing Data

Many organizations have been slow in compiling, classifying, and organizing the data sitting in siloes and dark corners. It’s “a boring, boring job,” says Ger Baron, Amsterdam’s first-ever chief technology officer. “But very useful!” 

He ought to know. The Netherlands’ capital has 12,000 different datasets, and even they can’t tell him everything about the city. For example, no one knows exactly how many bridges span Amsterdam’s famous canals, because the city’s individual districts have not centralized their infrastructure data. 

That story underscores the challenges organizations face in the realm of data governance, or the methods and rules that organizations use to assure the quality of data, manage it, integrate it into business processes, and manage its risks. 

[cite](https://sloanreview.mit.edu/case-study/lessons-from-becoming-a-data-driven-organization/)


## Abundant Data by Itself Solves Nothing 

Despite the promise of big data, industrial enterprises are struggling to maximize its value. Why? Abundant data by itself solves nothing. Its unstructured nature, sheer volume, and variety exceed human capacity and traditional tools to organize it efficiently and at a cost which supports return on investment requirements. Inherent challenges tied to evolution and integration of industrial information and operational technology, make it difficult to glean intelligence from operational data, compromising projects underway and promise for further investment and value.  [cite](https://graymattersystems.com/cio-survey-reveals-challenges-opportunities-potential-industrial-big-data/)

## Firms are years away from getting full value from their data assets

Throwing cash at the problem isn't helping matters either. Companies need to scale back their ambitions to invest in projects that are more evolutionary than revolutionary in nature, looking to tweak rather than overhaul existing operational practices. In short, the best big data strategy may be to go small. [cite](https://www.theregister.co.uk/2017/06/07/go_small_on_big_data/)



## Effective Approaches Entail 

Organizations across the business spectrum are awakening to the transformative power of data and analytics. They are also coming to grips with the daunting difficulty of the task that lies before them. It’s tough enough for many organizations to catalog and categorize the data at their disposal and devise the rules and processes for using it. It’s even tougher to translate that data into tangible value.

There  would be no data and analytics revolution without easily accessible, increasingly inexpensive computing power: the cloud, the Internet, and powerful, versatile software and algorithms. Yet technology is only part of the story. People are equally important.

The technology and the people who deploy it also need a process or system of rules to guide how people create and use information. Rules help transform the noise of disordered information into legible signals with the power to sharpen and deepen the focus on the customer (broadly defined), and in the process improve health outcomes, the customer experience, the realization of business value, and civic life and engagement.

[cite](https://sloanreview.mit.edu/case-study/lessons-from-becoming-a-data-driven-organization/)







** Section-II Data Programming



*** { @unit = "8th April", @title = "R Basics", @reading, @lecture, @assignment, @foldout }

# Topics

* Data types in R
* Ways  of  collecting  data:  passive,  active,  administrative  intro  to  life  logging  and  semester project.
* Design of Experiments.






*** { @unit = "15th April", @title = "Data Structures in R", @reading, @lecture, @assignment, @foldout }

# Topics

* Lists 
* Vectors 
* Data frames 






*** { @unit = "22th April", @title = "Working with Data Frames", @reading, @lecture, @assignment, @foldout }

# Topics

* Logical operators
* Control of execution
* Functions





*** { @unit = "29th April", @title = "Intro to Visualization", @reading, @lecture, @assignment, @foldout }

# Topics

* Visualization guidelines 
* R and the grammar of graphics 





*** { @unit = "6th May", @title = "Spatial and Multidimensional visualization", @reading, @lecture, @assignment, @foldout }

# Topics

* Bivariate and multivariate plots
* Mapping in R



** Section-III Dashboards




*** { @unit = "13th May", @title = "Dynamic visualization:", @reading, @lecture, @assignment }

# Topics

* The design and construction of dashboards.



*** { @unit = "20th May", @title = "Analyzing Managerial Experiments", @reading, @lecture, @assignment }

# Topics

* Analysis of experiments
* Testing outcomes in R


*** { @unit = "27th May", @title = "MEMORIAL DAY" }

# No Classs

Instructions will be given on what to do for this week.




*** { @unit = "3rd June", @title = "Dashboards II", @reading, @lecture, @assignment }

# Topics

* Shiny widgets.
* Advanced dashboards.



*** { @unit = "10th June", @title = "FINAL PROJECTS DUE", @assignment }

# Instructions











***  


