# My puppy

Check the project requirements for what should go into this file.


- This GitHub repository is part of the TidyTuesday project, a weekly data project by the R4DS community. Each week, it provides a dataset and invites R users to explore, analyze, and visualize the data using tidyverse tools. 

The specific dataset (2022-02-01) focuses on dog breeds, combining their traits (like energy, trainability, grooming needs, etc.) with their popularity rankings over time from the American Kennel Club (AKC).

The code in this project performs the following:
Analyzes the popularity trends of breeds (2013–2020).
Compares traits of top vs bottom 10 breeds.
Clusters breeds based on behavioral traits using K-means.
Visualizes key insights through plots.



- What software (with the version numbers) needs to be installed to run the code?
To run the R code shared from this repository, you’ll need:
 Software
R: Version 4.3.0 or later (the latest as of mid-2024 is 4.4.0)
RStudio: Version 2023.12.1+ (or newer, e.g., 2024.04.1)

 Packages
library(tidyverse)     # v2.0.0+
library(dplyr)         # v1.1.4+
library(ggplot2)       # v3.5.1+
library(tidyr)         # v1.3.1+
library(readr)         # v2.1.5+
library(cluster)       # v2.1.6+
library(factoextra)    # v1.0.7+



-  What steps need to be taken to run the code?
Initial Setup (as you would have done at semester start):
Install R and RStudio (see versions above).
Install required R packages (listed above).
Check internet connection (data is read directly from GitHub URLs).
Run each code chunk sequentially in RStudio.
Steps include:

Reading in the data.
Cleaning and reshaping data.
Performing exploratory data analysis (EDA).
Running clustering algorithms.
Creating data visualizations.
(Optional) Create an RMarkdown (.Rmd) or Quarto (.qmd) file to document your process and render it to HTML or PDF.



4. What does the expected output look like?
### Visualization 1
![Trend Plot 1](images/1.png)

### Visualization 2
![Trend Plot 2](images/2.png)

### Visualization 3
![Trend Plot 3](images/3.png)

### Visualization 4
![Trend Plot 4](images/4.png)

