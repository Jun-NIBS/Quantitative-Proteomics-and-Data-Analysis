---
title: "Quantitative Proteomics and Data Analysis"
author: "Laurent Gatto"
output:
  rmdshower::shower_presentation:
    self_contained: true
    katex: true
    theme: ribbon
    ratio: 16x10
---

## Inspection, visualisation and analysis of quantitative proteomics data

```
Laurent Gatto                      Computational Proteomics Unit
https://lgatto.github.io           University of Cambridge
lg390@cam.ac.uk                    @lgatt0
```

Slides: http://bit.ly/qprotda -- Vignette: http://bit.ly/qprotdavig

**Acknowledgements**  BBSRC for funding; Sebastian Gibb and Lisa Breckels for coding.

```
```

(Last update Mon Jun  6 08:58:52 2016)

##

These slides are available under a
[**creative common CC-BY**](http://creativecommons.org/licenses/by/4.0/)
license. You are free to **share** (copy and redistribute the material
in any medium or format) and **adapt** (remix, transform, and build
upon the material) for any purpose, even commercially.

<img src="Figures/cc1.jpg">

## Content

1. Introduction on data analysis
2. Quantitative proteomics data analysis - overview
3. Visualisation
4. Quantitative proteomics data analysis - examples
5. Data analysis
6. References and resources


## What is data analysis

> Data analysis is the process by which data becomes understanding,
> knowledge and insight. Hadley Wickham

The ability to prepare and **explore** data, identify **patterns**
(good and pathological ones) and convincingly demonstrate that the
patterns are **genuine** (rather than random).

It's not analysing data, it's *investigating* data - requires flexibility.

##

<img src="./Figures/Data_Analysis_Hadley_Wickham.png" class="cover">  


## And also

* Reproducibility/replicability
* Automation
* Plain text: tracking, re-use, share, communicable


`Programming`,  but:

* Learning curve (although, I would argue that the
reflecting/investigating/analysing the data is the real challenge)


## To analyse data, you need

* ~~Programming skills~~
* ~~Be a statistician/machine learner~~

## To analyse data, you need

* ~~Programming skills~~
* ~~Be a statistician/machine learner~~
* Knowledge about the domain
* Know about your data
* Be able to manipulate/visualise it
* How good do we need to be?

## To analyse data, you need

* ~~Programming skills~~
* ~~Be a statistician/machine learner~~
* Knowledge about the domain
* Know about your data
* Be able to manipulate/visualise it
* How good do we need to be? **Good enough**

## Quantitative proteomics data analysis

* What data do we have? 
* What analyses can we apply?
* Track/check the data throughout the analysis.

##

<img src="./Figures/qprotda.png" class="cover">

## Visualisation

> Graphics reveal data.

  

> Visualization can surprise you, but it doesn’t scale well. Modeling
> scales well, but it can’t surprise you. Hadley Wickham



##

<img src="./Figures/choosing-a-good-chart.jpg" class="cover">

##

<img src="./Figures/qprotda-with-plots.png" class="cover">

##

[Inspection, visualisation and analysis of quantitative proteomics data](http://bit.ly/qprotdavig)

<div class="double">
<p class="double-flow">
<img src="./Figures/msanim1.gif" class="one-col-image">
</p><p class="double-flow">
<img src="./Figures/msanim2.gif" class="one-col-image">
</p>
</div>


## Data analysis tools

should enables you to **manipulate** your data, give some guarantees
about the **integrity** of the data, support effective
**extract/subset** components of the data, **visualise** them, enable
**transformation** of the data, give access to infrastucture for
**statistical analysis**, and enable **annotation** of the data.

## Data analysis tools

* Store data as *computational objects* (rigorously defined data
  structures): knowing where to find things
* Consistency in data structures (and conventions)
* Easily manipluate/transform/visualise these data (*Application
  programming interface*)

## The `MSnSet` class for quantitative data

<div class="double">
<p class="double-flow">
* Expression/quantitative data
* Feature meta-data
* Sample meta-data
* Dimension constrains

</p><p class="double-flow">
<img src="Figures/msnset.png" class="one-col-image">
</p>
</div>

Can be subsetted, transformed, visualised, annotated, statistics, ...

## References, resources

* [Visualisation of proteomics data using R and Bioconductor](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC4510819/)
* [Using R and Bioconductor for proteomics data analysis](http://arxiv.org/pdf/1305.6559v1.pdf)
* `RforProteomics`: http://bioconductor.org/packages/RforProteomics
* [R/Bioconductor workflow](http://bioconductor.org/help/workflows/proteomics/)
* [Teaching material](http://lgatto.github.io/TeachingMaterial/) for
  R and more
* Workshops: [Software](http://software-carpentry.org/) and
  [Data Carpentry](http://www.datacarpentry.org/), 
  [Data Programmers](http://www.dataprogrammers.net/)


**Thank you for your attention**
