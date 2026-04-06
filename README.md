# NYC PM2.5 Air Quality Case Study

This repository contains the materials for a case study where you will analyze fine‑particle pollution (PM2.5) across New York City Community Districts. Your goal is to determine whether population level (high vs. low) is associated with differences in PM2.5 trends, seasonality, or variability.

You will start from the raw dataset only and build the entire workflow yourself.

## What You Will Do
- Load the raw NYC air‑quality dataset
- Write your own data‑cleaning script
- Filter the data to keep only PM2.5 observations
- Prepare a cleaned dataset for analysis
- Run STL decomposition for each Community District
- Extract trend slope, seasonal amplitude, and residual RMSE
- Split districts into high‑ and low‑population groups
- Compare groups using the Mann–Whitney U‑test
- Interpret whether population density affects PM2.5 behavior

## How to Get Started
1. Download or clone this repository  
   It contains the raw dataset and all supporting documents.

2. Write your own data‑cleaning script  
   Your script should:  
   - Load the raw CSV  
   - Filter rows where the Indicator ID corresponds to PM2.5  
   - Keep only Community District–level data  
   - Parse dates  
   - Handle missing values  
   - Save a cleaned dataset for analysis

3. Perform your analysis  
   Using your cleaned dataset:  
   - Run STL decomposition  
   - Extract the required metrics  
   - Group CDs by population  
   - Run the Mann–Whitney U‑test  
   - Create visualizations  
   - Summarize your findings

## Materials Included
You can find the following in this repository:

- Hook Document – a 1‑page overview introducing the scenario and your mission
- Rubric – detailed expectations for your final report
- Raw Data – the NYC air‑quality dataset you will clean and analyze
- Case Study Description – instructions and context for the assignment
- Blog‑Style Explainer – an accessible introduction to PM2.5 and why it matters
- Technical Article – a reference to help you understand STL decomposition

These materials are here to guide you, but you are responsible for building the full analysis from scratch.