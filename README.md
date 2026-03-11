# Gambierdiscus abundance by depth – Balearic Islands

## Author
Alba Garriga

## Description

This repository contains R scripts used to analyse the abundance of *Gambierdiscus* and *Fukuyoa* across different depths and sampling campaigns in the Balearic Islands (MA16 and MA17).

The analysis calculates mean abundance and standard deviation per site, campaign and depth, and generates bar plots showing depth distribution patterns.

## Data structure

The dataset includes the following variables:

- Site
- Campaign
- Depth
- Gamb Abundance (cells·g ww⁻¹)
- Fuku Abundance (cells·g ww⁻¹)

### Depth distribution plots

Bar plots were generated to visualise the depth distribution of *Gambierdiscus* abundance at each sampling site.

For each site, the mean abundance (cells·g ww⁻¹ wet weight of macrophytes) was calculated per depth and sampling campaign. Error bars represent the standard deviation of the samples within each group.

Depth levels were treated as categorical variables (4, 10, 20 and 30 m). Bars are coloured by sampling campaign to allow comparison between surveys.

The plots were generated using the ggplot2 package in R.


## Repository structure

project/

data/  
Raw input datasets

scripts/  
R scripts used for analysis

figures/  
Generated plots

output/  
Processed data tables

README.md  

## Required R packages

The analysis requires the following packages:

- tidyverse
- dplyr
- ggplot2


