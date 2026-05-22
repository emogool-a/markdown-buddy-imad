# R Data Analysis Project

## Overview
This project demonstrates a simple R data analysis workflow using a synthetic dataset.

## Objectives
- Import and inspect data
- Summarize key variables
- Create simple visualizations
- Document the workflow clearly

## Data Description
The project uses a synthetic dataset for learning purposes. No real or personal data is used.

## Installation
Install the required R packages:

```r
install.packages("tidyverse")
Usage

Run the R script in RStudio or Posit Cloud.
library(tidyverse)

data <- data.frame(
  category = c("A", "B", "C"),
  value = c(10, 20, 15)
)

summary(data)
