Healthcare Access in Maine
================
Cedar Callahan

``` r
library(tidyverse)
library(broom)
```

``` r
ahrf_2019_2023 <- read.csv("/cloud/project/data/ahrf_2019_2023.csv")
```

## 1. Introduction

This project will be done using the Area Health Resource Files data
collected by the Health Resources and Services Administration. The
collected data is between 5000 and 75000 variables (depending on the
year), most of which I will not be using. My primary research question
concerns the distribution of medical professionals. Is the number of
medical professionals per county proportional to the population of each
county? Within that, I am curious about the distribution of specialists,
the average distance to the nearest hospital, and insurance coverage.
While the `ahrf_2019_2023` dataset is the primary dataset, I will be
loading in additional data as needed.

## 2. Data

## 3. Ethics review

## 4. Data analysis plan
