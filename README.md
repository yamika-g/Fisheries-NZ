# Fisheries NZ

## 📌 Project Overview
New Zealand's fishing industry plays a crucial role in its economy, contributing significantly to GDP, exports, and employment, particularly in coastal communities. It has one of the largest Exclusive Economic Zones (EEZ) in the world, has an area of more than 4M km2 in the ocean and is home to diverse marine species. The country's fisheries management is globally recognized for its sustainability efforts, driven by the Quota Management System (QMS), which regulates catch limits to prevent overfishing.

This project involves gathering catch and export data from different sources and integrating them into a unified **relational data model** to enable deeper analysis of the fishing industry. The raw datasets vary in structure, and contain inconsistencies such as different naming conventions for species, and missing values. To address these challenges, lots of data cleaning and wrangling had to be done before linking the datasets in a way that preserved key relationships. The merged dataset provided richer insights than any individual dataset alone, making it possible to analyze broader industry trends and relationships that were previously fragmented across separate data sources.

## 📂 Project Structure
- `data/` → Fish export data as excel, Mid-stage data (combined/grouped datasets exported for further processing), Final relational data model used for analysis.  
- `FISHERIES.ipynb` → Jupyter Notebook used for analysis
- `results/` → screenshots of visualised data, and Entity-Relationship diagram.
- Final Project Report (PDF)

## Methodology

Skills & Concepts Used:
R    |    Web Scraping    |   Relational Databases
I used R to analyze this dataset, and Jupyter Notebook as my environment. For my analysis, I used the following packages: `tidyverse`, `dplyr`, `rvest`, `visdat`, and `ggplot2`.


## 📊 Results

By analyzing this data, I attempted to find answers to the following questions:

1. In 2021, which fish was the most caught fish in NZ? 
2. What are the top 5 export destinations for fish from NZ?
3. What countries are the top 5 importers of Hoki from NZ?
4. How has the price of fish products changed over the years from 2018-2022?
5. Are there any species that are overfished?

Here are the findings:

1. The top 3 caught species in NZ in 2021 were Hoki, Jack Mackerel, and different kinds of Squid.
2. The top 5 export destinations are China, Australia, USA, Japan and South Africa.
3. The top 5 importers of Hoki are China, Australia, Poland, France, and Germany.
4. The average price of fish products didn't change much over the years.
5. Bluenose was initially overfished, but its fishing decreased in 2021 and 2022. Gemfish was almost always overfished in this 5 year period.

## 📜 License
This project is **copyrighted** and may **not** be used, copied, modified, or distributed.  
It is an academic project submitted for university coursework.  
Any unauthorized use, including plagiarism, will be considered a violation of academic integrity policies.  
