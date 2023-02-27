# Overview

A file and folder structure containing the Module 8 exercise for MADA 2023 by Irene Cavros. 

# Pre-requisites

This is a data analysis project using R, Quarto, Github and a reference manager that can handle bibtex. It is also assumed that you have a word processor installed (e.g. MS Word or [LibreOffice](https://www.libreoffice.org/)). You need that software stack to make use of this template.

# Structure

* All data is found inside the `data` folder.
* All code is found in the `code` folder. 

# Content 

* The untouched raw dataset can be found in the `data` folder. It is titled `SympAct_Any_Pos.rda` 
* The `wrangling.qmd` file in the `code` folder loads the raw data, performs a bit of cleaning, and saves the result in the `data` folder as `cleandata.rds` 
* The `exploration.qmd` file in the `code` folder loads the processed data and does an exploratory analysis. 
and fit a simple model. 
*The `fitting.qmd` file in the `code` folder fits a few models and compares results. 

# Getting started

This is a Github repository. The best way to get it and start using it is [by following these steps.](https://help.github.com/en/articles/creating-a-repository-from-a-template)

Once you got the repository, you can check out the analysis by executing code in order. First run the wrangling code, which will produce the processed data from our raw data. Then run the exploration and fitting scripts, which will take the processed data and produce some results. 


