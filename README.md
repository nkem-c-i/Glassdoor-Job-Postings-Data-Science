# Glassdoor Data Cleaning

This repository contains cleaned and enriched Glassdoor Data Science job postings for two regions:

- **San Francisco** (`sf_jobs_enriched.csv`): Includes average salary, normalized salary ranges, and binned salary categories.  
- **Washington State** (`Data_Job_WA_cleaned.csv`): Features cleaned company names, standardized job types and industries, and one-hot encoded categorical variables.

## Files

- `data/Data_Job_WA_cleaned.csv`: Raw WA data after categorical cleanup & enrichment.  
- `data/sf_jobs_enriched.csv`: Raw SF data after salary normalization & analysis.

## How to Use

1. Clone this repo:
   ```bash
   git clone https://github.com/<yourusername>/glassdoor-data-cleaning.git
   cd glassdoor-data-cleaning
