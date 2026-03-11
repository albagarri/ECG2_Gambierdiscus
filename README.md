# Gambierdiscus abundance by depth – Balearic Islands

## Author
Alba Garriga

## Description

This repository contains R scripts used to analyse the abundance of *Gambierdiscus* and *Fukuyoa* across different depths and sampling campaigns in the Balearic Islands.

The analysis calculates mean abundance and standard deviation per site, campaign and depth, and generates bar plots showing depth distribution patterns.

## Data structure

The dataset includes the following variables:

- Site
- Campaign
- Depth
- Gamb Abundance (cells·g ww⁻¹)
- Fuku Abundance (cells·g ww⁻¹)

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

Install them with:
