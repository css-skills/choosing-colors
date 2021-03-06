---
title: "Optimizing selection of color palettes"
description: |
  Researchers frequently use color to communicate numeric values in a data visualization.
  Most software will implement a default algorithm to select a color palette, and these
  palettes frequently are hard-to-interpret or are inaccessible to individuals with vision
  impairments. In this workshop we will develop approaches to readily generate optimized
  color palettes for continuous and categorical variables.
author:
  - name: Benjamin Soltoff
    url: https://www.bensoltoff.com
    affiliation: University of Chicago
    affiliation_url: https://macss.uchicago.edu
date: 11-02-2021
output:
  distill::distill_article:
    keep_md: true
---



## Overview

Researchers frequently use color to communicate numeric values in a data visualization. Most software will implement a default algorithm to select a color palette, and these palettes frequently are hard-to-interpret or are inaccessible to individuals with vision impairments. In this workshop we will develop approaches to readily generate optimized color palettes for continuous and categorical variables.

## Objectives

- Identify when color is used to visualize data
- Distinguish between hue palettes and gradients
- Demonstrate the importance of selecting appropriate palettes/gradients for interpretation and accessibility
- Evaluate use cases for quantitative vs. qualitative color scales
- Evaluate use cases for sequential vs. diverging color scales
- Evaluate use cases for discrete vs. continuous color scales
- Consider how to interpolate values to colors
- Implement ready-to-use optimized color scales using `ggplot2` and existing R packages

## Audience

This workshop is designed for individuals with a basic familiarity using R and `ggplot2` for data visualization.

## Location

Room 295 in [1155 E 60th St](https://goo.gl/maps/7n7wDsd9mjnfRBtR8).

## Prework

- Register for this workshop. Due to the current public health crisis, all participants must register in advance using [this form.](https://forms.gle/7JEkgjoiGEnM2MGu5)
- Please sign up for a free [RStudio Cloud account](https://rstudio.cloud).
- If you have not participated in a previous workshop meeting, [join the workshop organization.](https://rstudio.cloud/spaces/177434/join?access_code=cGV7c0V8%2Bpr0kFC5NkOX%2FgxNNhIm3PchWX1CjdBf)

## Links

- [Slides](https://css-skills.github.io/choosing-colors/slides/)
- [Source materials for the workshop on GitHub](https://github.com/css-skills/choosing-colors)

## Acknowledgments

- Overview of color palettes drawn from ["Which color scale to use when visualizing data" by Lisa Charlotte Muth](https://blog.datawrapper.de/which-color-scale-to-use-in-data-vis/)
```{.r .distill-force-highlighting-css}
```
