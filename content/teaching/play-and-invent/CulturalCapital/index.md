---
title: "Cultural Capital"
author: "Arvind V"
date: "2024-08-09"
output: md_document
type: page
toc: TRUE
weight: 30
tags:
  - Cultural Capital
  - Pierre Bourdieu
links:
  - icon_pack: fab
    icon: twitter
    name: Follow
    url: 'https://twitter.com/arvind_v'
  - icon_pack: fab
    icon: pdf
    name: Slides
    url: 'publication/conference-paper/conference-paper.pdf'
slides: ""
url_slides: ""
url_code: ""

---


## R Package Setup



## Introduction

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

## Including Plots

You can also embed plots, for example:


``` r
penguins %>% 
  gf_point(body_mass_g ~ flipper_length_mm, colour = ~ species) %>% 
  gf_theme(theme = theme_classic())
```

```
## Warning: Removed 2 rows containing missing values or values outside the scale range
## (`geom_point()`).
```

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-2-1.png" width="672" />


Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
