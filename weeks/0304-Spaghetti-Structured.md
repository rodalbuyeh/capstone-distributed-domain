---
layout: week
title: Week 03 - 04
permalink: /weeks/0304-Spaghetti-Structured/
doodle: /doodle.png
---

# From Spaghetti to Structured: The Essentials of Production Ready Code 

## Topics

This week's assignments will introduce you to tools and workflows that
will help you be more efficient and structured in your ML development process, 
including:
* how to leverage IDEs to accelerate productivity
* how to modularize and package your code 
* how to automate workflow steps
* how to employ code versioning tools

### Viewing

Please view one of the following IDE tutorials, either on pycharm or VSCode:
* Video: [Pycharm Tutorial](https://www.youtube.com/watch?v=hc50ALh_x5g) - this is long (2 hrs) but comprehensive.
* Video: [Visual Studio Tutorial](https://www.youtube.com/watch?v=E9U-EBG8jVk)
* If you're wondering why we're doing this stuff, see: [I don't like notebooks by Joel Grus](https://www.youtube.com/watch?v=7jiPeIFXb6U&t=776s). Look into setup.cfg as an alternative to setup.py, and also be aware of MANIFEST.in

On bash terminal: 
* Video: [Beginner's guide to bash terminal](https://www.youtube.com/watch?v=oxuRxtrO2Ag)

On git: 
* Video: [View this entire playlist](https://www.youtube.com/playlist?list=PL4cUxeGkcC9goXbgTDQ0n_4TBzOO0ocPR)

On python packaging: 
* Video: [How to Build a Complete Python Package Step-by-Step](https://www.youtube.com/watch?v=5KEObONUkik&t=328s)

On Makefiles for automation: 
* Video: [Makefiles in python projects](https://www.youtube.com/watch?v=MICrNQm5btQ)

On configs for python applications: 
* Video: [Config Files & Parsing in Python](https://www.youtube.com/watch?v=68I-oxeJ4HE)

Recommended viewing: 
- [Type annotations](https://www.youtube.com/watch?v=QORvB-_mbZ0)
- [Docstrings](https://www.youtube.com/watch?v=0YUdYk5E-w4&t=250s)
- [Unit testing, specifically pytest](https://www.youtube.com/watch?v=YbpKMIUjvK8)
- [Logging](https://www.youtube.com/watch?v=-ARI4Cz-awo)


## Tasks 

The following tasks are broad objectives, you may choose one or more to focus on. 
Also recommennd working together potentially to divide and conquer, or at least for support in debugging.

Based on feedback from last week, proceed as follows: 
* If you received feedback on labeling or sample definitions,
make necessary adjustments and refer to legacy code for guidance.

* Swap out pandas dataframes and swap in either [dask dataframes](https://docs.dask.org/en/stable/dataframe.html) or [ray datasets](https://docs.ray.io/en/latest/data/data.html)

* Migrate your code out of jupyter and into your IDE. Set it up as a package instead of a single script.

* Push to a git repository and use git to track your work.

* Leverage the categorical encoder found in the legacy repository. 
Consider opportunities to leverage ray to speed it up by parallelizing iterations over columns. 

## Weekly Questions

Answer the following questions on Gradescope:

* What are the tradeoffs of jupyter vs IDEs? 
* What are the benefits of using git to track work? 
* Why should we modularize our code?  
