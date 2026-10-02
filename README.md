# Predicting Late Delivery Risk in a Supply Chain Using R

This repository contains my project for the **Virtual Data Science with R Apprentice Internship** (01 October 2026 to 05 November 2026).

## Project Overview

Late deliveries reduce customer satisfaction and increase operating costs. This project uses R to answer one main question:

> Can we predict whether an order will be delivered late using only the information available when the order is placed, and which factors contribute most to that risk?

## Dataset

- **Name:** DataCo Smart Supply Chain for Big Data Analysis
- **Source:** Mendeley Data (Constante, Silva and Pereira, 2019), also available on Kaggle
- **Size:** About 180,000 order records with 53 columns
- **Target variable:** Late delivery risk (1 = late, 0 = on time)

The raw data file is not stored in this repository because of its size. Download it from the source above and place it in `data/raw/`.

## Tools and Packages

- R and RStudio
- tidyverse (readr, dplyr, tidyr, ggplot2, forcats)
- lubridate, janitor, skimr
- tidymodels, rpart, ranger, vip
- renv for package version control
- Quarto for reports

## Project Plan

| Week | Phase | Status |
|------|-------|--------|
| 1 | Project planning and strategy | Completed |
| 2 | Data collection and cleaning | Planned |
| 3 | Exploratory data analysis | Planned |
| 4 | Model development and tuning | Planned |
| 5 | Evaluation and final reporting | Planned |

## Repository Structure
