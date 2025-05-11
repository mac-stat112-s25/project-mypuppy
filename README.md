# My puppy

Check the project requirements for what should go into this file.


1. This GitHub repository is part of the TidyTuesday project, a weekly data project by the R4DS community. Each week, it provides a dataset and invites R users to explore, analyze, and visualize the data using tidyverse tools. 

The specific dataset (2022-02-01) focuses on dog breeds, combining their traits (like energy, trainability, grooming needs, etc.) with their popularity rankings over time from the American Kennel Club (AKC).

The code in this project performs the following:
Analyzes the popularity trends of breeds (2013–2020).
Compares traits of top vs bottom 10 breeds.
Clusters breeds based on behavioral traits using K-means.
Visualizes key insights through plots.



2. What software (with the version numbers) needs to be installed to run the code?
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



3. What steps need to be taken to run the code?
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
You can expect visual outputs like the following (screenshots are described, but you can generate them by running the code):
A. Bar Plot – Traits of Top 10 vs Bottom 10 Breeds
A flipped bar chart showing how traits like "Trainability", "Energy Level", and "Affectionate With Family" differ between the most and least popular breeds.
Example output:
| Trait                    | Mean Score (Top 10 vs Bottom 10) |
|--------------------------|----------------------------------|
| Trainability Level       | Top 10: 4.5, Bottom 10: 2.3       |
| Shedding Level           | Top 10: 2.0, Bottom 10: 4.2       |
| Energy Level             | Top 10: 4.6, Bottom 10: 3.1       |

B. K-Means Cluster Plot – Trait-Based Clustering
A scatter plot showing breeds grouped into 4 clusters based on similar behavioral traits.
Cluster 1: Obedient family dogs
Cluster 2: High-drive working breeds
Cluster 3: Low-energy companion breeds
Cluster 4: High-maintenance show breeds

C. Bar Plot – Average Popularity Rank by Cluster
A bar chart showing which trait cluster is the most or least popular based on average AKC rank.


D. Line Graphs – Breeds Gaining or Losing Popularity
Two line plots:
Top 5 breeds increasing in popularity (2013–2020)
Top 5 breeds falling in popularity
Each line represents a breed’s rank over time, with y-axis reversed (rank 1 = top).


E. Trait Comparison: Rising vs Falling Breeds
Another bar chart showing which traits are more common in breeds gaining or losing popularity.
