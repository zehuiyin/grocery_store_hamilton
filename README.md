# Food Deserts or Food Oases? Predicting Grocery Store Locations in Hamilton, Ontario

# Authors:

- [Zehui Yin](https://zehuiyin.github.io/), [yinz39@mcmaster.ca](mailto:yinz39@mcmaster.ca)

## Supervision:

- [Dr. Antonio Paez](https://experts.mcmaster.ca/display/paezha)

## Project Overview:

This repository contains the source code for the R-based data analysis of the project 
**Food Deserts or Food Oases? Predicting Grocery Store Locations in Hamilton, Ontario**. 
This project was the final project for the course 
[GEOG 712 Reproducible Research Workflow with GitHub and R](https://academiccalendars.romcmaster.ca/preview_course.php?catoid=55&coid=274877) 
at McMaster University in Fall 2024.

You can access the paper [here](https://github.com/zehuiyin/grocery_store_hamilton/blob/main/grocery_store_hamilton/grocery_store_hamilton.pdf), or download [here](https://raw.githubusercontent.com/zehuiyin/grocery_store_hamilton/refs/heads/main/grocery_store_hamilton/grocery_store_hamilton.pdf).

It is worth noting that the paper was generated using RMarkdown (`Rmd`) with the analysis source code embedded directly within. You can access the `Rmd` file [here](https://github.com/zehuiyin/grocery_store_hamilton/blob/main/grocery_store_hamilton/grocery_store_hamilton.Rmd).

## Abstract:

Grocery stores play a crucial role, especially for urban residents, as they provide essential daily food supplies. The locations of grocery stores are not randomly chosen but are the result of detailed decision-making processes by grocery companies. Understanding the locations these grocers choose to establish themselves is important for public health and urban planning, as geographic access to grocery stores impacts personal health. In this paper, I utilize open data to examine grocery store locations in Hamilton, Ontario, as a case study. A zero-inflated negative binomial regression model with spatial lagged terms is fitted and estimated using maximum likelihood methods. I identified noticeable spatial patterns in grocery store locations. Grocery stores tend to cluster in nearby dissemination areas, but when there are too many grocery stores, they tend to disperse. The number of grocery stores is also significantly associated with population density, dissemination area size, the percentage of residents who do not speak an official language at home, those living in single detached houses, and the distance to Hamilton downtown.

## Research Questions:

This project addresses the following research question:
- What areas in Hamilton have more or fewer grocery stores compared to other areas?

## Data:

To facilitate reproducibility and open science, all the data used in this paper have been packaged into an R package (Yin, 2024), which is hosted on GitHub. You can access it at <https://github.com/zehuiyin/geog712package>.
