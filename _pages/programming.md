---
layout: single
permalink: /programming/
author_profile: true
title: "Programming"
excerpt: "Development and Data Science in Python"
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/spiral.jpg
layouts_gallery:
  - url: /assets/images/kvmr.jpg
    image_path: /assets/images/kvmr.jpg
    alt: "splash layout example"
  - url: /assets/images/through_harp.jpg
    image_path: /assets/images/through_harp.jpg
    alt: "single layout with comments and related posts"
  - url: /assets/images/wheatstone.jpg
    image_path: /assets/images/wheatstone.jpg
    alt: "archive layout example"
last_modified_at: 2020-10-14T10:15:22-04:00
toc: true
---

I find developing software to be among the  most engaging parts of my research and  I
have also been mindful of many shortcomings in the way software and data analysis is
typically approached in an academic setting. Early on I switched to Python as my
programming language of choice, even though it was uncommon in the field. The change
led me to focus more on programming style, distribution methods, testing and
reproducibility. Outside of my own research, I made a specific effort to learn about
important topics and developments in data science through courses, seminars held by
the Berkley Institute for Data Science, and my own personal side-projects.

## Scientific Code Development

I co-developed on a C++ code with 2 other members of my research group a UC Berkeley
over the past 4 years (with an additional student contributing for part of that
time). This code handles high-precision calculations of the gravitational field for a
planet with an arbitrary density profile, including the effects of rotation and
tides. It is based on an numerical algorithm which I helped develop and improve.  

The code is parellized using OpenMP and optimized to run on supercomputers run by
LBNL and NERSC.  The project has a code base exceeding 24,000 lines of code and was
adapted from a prototype Fortran 90 code I wrote in conjunction with a collaborator from
U. Arizona.

While the source code is proprietary, I put together a  [demonstration of its basic
functionality](https://github.com/smwahl/CMS_Saturn) for [this journal
article](https://seanwahl.com/publications/2019_science)

## Data Analysis and Visualization with Python

I use python on a daily basis for data analysis, file manipulation and data storage
in my research.  This involves extensive use of standard numerical packages (numpy,
scipy) and visualization with matplotlib and other packages.  This work makes
frequent use of  python environments, unit testing, object-oriented programing,
interfacing with operating system and shell scripts, and Interfacing python with
compiled languages (C and Fortran). I also advocate using the pandas package for data
storage and manipulation using (SQL-like) relational database operations.

I am also familiar basic sci-kit learn functionality and image manipulation (sci-kit
image, PIL) from coursework I have helped developed, and with using python for basic
web frameworks, APIS and geospatial data (GIS) from coding side projects.

Here are some tutorials for
[matplotlib](https://github.com/smwahl/thw_matplotlib_presentation) and
[pandas](https://github.com/smwahl/thw_intro_pandas) I wrote for fellow researchers
through the UC Berkeley Chapter of The Hacker Within.


## Other experience

- Bash: I use a unix-based command line interface for file systems, and often run
  code and back up data remotely. I frequently use Bash for simple file manipulation
  scripts.

- SQL: Used for basic operations during coursework (interfacing with python code).
  Also used to manipulate dataset for the CDIPS summer data science workshop at UC
  Berkeley. I more frequently use the pandas python library for relational
  database-like operations (so I am familiar with a lot of the concepts but not so
  much the syntax for SQL.
 
-  I have used numerical, statistical and visualization capabilities in both R and
   MATLAB in coursework, but strongly prefer Python for almost all cases I have come
   across.

- Website development with Jekyll, Markdown and basic html (such as [this
  website](https://seanwahl.com)).

## Side projects


### CDIPS Workshop 

As part of the as part of the CDIPS Data Science Workshop at UC Berkeley, I performed
a statistical study of the relation between social media and billboard success along
with a team of two other. This involved cleaning messy data sets (in this case large
tables of billboard top hits), using social media apis (youtube and twitter) as well
as scraping information from related websites. The goal was to see which social media
activity was the best predictor of billboard hits. 

Find on [Github](https://github.com/trxw/CDIPS_PandoraTeam).

### Tools and Analysis of Traditional Music Databases

I have an ongoing side-project to parse and analyze sheet music in the ‘.abc’ format.
I am interested in applying this extensive traditional music databases (an outside
interest of mine). This includes manipulating and analyzing the ‘.abc’ (encoded sheet
music) as well as a variety of metadata about the music and database users. I plan to
develop tools for the format, such as searching for a tune based on a snippet of
melody, or recommend tunes to a user based on previous choices.


Find on [Github](https://github.com/smwahl/pytrad).

### CIDER Workshop 

I worked with a team of 7 on a month long research project at a geophysics summer
workshop (CIDER) at UC Santa Barbara. This involved writing a code for coupling a
simple 1D thermal evolution code and with an elemental composition model. It was in
python and was coordinated using Git.


Find on [Github](https://github.com/trxw/https://github.com/cider-team-mercury). 

## Relevant Coursework

### Python computing for Data Science (AY 250) 
The most directly relevant Data Science coursework. An overview to a number of
applications of python including numerical and scientific libraries, data
visualization, parallelism, database interaction, web frameworks, machine learning,
image processing and Bayesian programming. As a final project I migrated the data
management system for my research to python using pandas and relational database
concepts. 

[Final Project on Github](https://github.com/smwahl/ay250_swahl/tree/master/final)

### Software Engineering for Scientific Applications (COMPSCI 294)

Introduction to a number of different computer languages and concepts. With regular
exercises in numerical algorithms As a final project, I wrote a simple version of a
quantum Monte Carlo code (A type of calculation relevant to my research). 

### Other

I also followed self-paced courses for algorithms and for working with GIS geospatial
data in python. I also developed relevant coursework on image processing and data
visualization for an introductory python course at UC berkeley.
