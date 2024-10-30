# Using BOLD to determine if the Biodiversity of Tuna is affected due to Overfishing Practices.

## Table of Contents
- [Introduction](Introduction)
- [Methodology](Methodology)
- [Features](Features)
- [Requirements](#requirements)
- [Data Sources](#data-sources)

## Introduction
Due to high demand, tuna species like Yellowfin, Pacific Bluefin, and Atlantic Bigeye are frequently overfished, often through illegal practices, which may threaten their genetic diversity. This program will use BOLD data to assess the geographic distribution of tuna populations and investigate if overfishing significantly impacts their genetic diversity and surrounding ecosystems.

## Methodology
* Data Collection: Obtaining genetic sequence data for multiple tuna species from BOLD.
* Data Processing: Cleaned and formatted the data for analysis.
* Analysis:
  - Calculated genetic diversity metrics for each tuna species.
  - Compared these diversity indices to known fishing practices and population trends.

## Features
* Bioinformatics tools for sequence analysis in R.
* Biodiversity metrics and diversity indices.
* Visualization of results to assess impact on tuna populations.
  - World map to visualize where collection sites of tuna species around the world.
  - PCA Plot to assess the biodiversity of each tuna species.
  - Bar Graph depicting the tuna sampling completness of each country.

## Requirements
* R Version 3.6.0+
* R Packages: `ape`, `Biostrings`, `formatR` ,`ggplot2`,`msa` , `pegas`, ,`seqinur`, `styler`,`sf`, `tidyverse`

## Data Sources
[BOLD System](https://boldsystems.org/)
