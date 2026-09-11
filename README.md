# UIDAI Data Hackathon 2026 – Aadhaar Data Analysis

## Overview

This project analyzes Aadhaar enrolment, demographic updates, and biometric updates across India using large-scale UIDAI open datasets.

The objective is to identify regional trends, update patterns, operational gaps, and meaningful insights through data preprocessing, aggregation, ratio analysis, and visualization.

## Team

- Sahil Laghave – Team Leader
- Om Dhanapune – Member
- Atharva Kandalkar – Member

## Datasets

The analysis uses three UIDAI datasets:

- Aadhaar Enrolment Dataset
- Demographic Update Dataset
- Biometric Update Dataset

The datasets contain information related to dates, states, districts, pincodes, age groups, demographic updates, and biometric updates.

## Methodology

1. Loaded and merged large CSV datasets using Python and Pandas.
2. Standardized date formats and cleaned the data.
3. Created total enrolment, demographic update, and biometric update metrics.
4. Aggregated data at state and district levels.
5. Performed enrolment-to-update and biometric-to-enrolment ratio analysis.
6. Created visualizations using Matplotlib.
7. Analyzed regional patterns, trends, anomalies, and operational differences.

## Key Insights

- The 0–5 age group accounts for the largest share of Aadhaar enrolments.
- Uttar Pradesh, Bihar, and Madhya Pradesh have high overall enrolment volumes.
- Thane emerged as a major district in enrolment activity.
- High enrolment volumes do not always correspond to proportional demographic or biometric updates.
- Smaller administrative regions show relatively higher biometric-to-enrolment ratios.
- Ratio-based analysis provides additional insights beyond absolute enrolment counts.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Future Scope

- Region-specific performance benchmarking
- Time-series analysis of update completion
- Predictive modeling for biometric backlog
- Integration with population-density metrics

## Project Report

The detailed analysis and findings are available in the project report included in this repository.
