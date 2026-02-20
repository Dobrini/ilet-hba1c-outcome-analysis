## Project Title

HbA1c Outcomes Following Automated Insulin Delivery: Exploratory Analysis of the iLet Bionic Pancreas Trial


## Project Overview

This project analyzes glycemic outcomes among participants enrolled in a diabetes treatment study using different insulin delivery systems, including the iLet Bionic Pancreas and other commercially available insulin pumps. 


The analysis focuses on differences in glycemic improvement across device groups using non-identifiable participant-level data. The objective is analytical rather than clinical, and results should not be interpreted as evidence of treatment efficacy or superiority.


Participants were assigned either to the iLet Bionic Pancreas intervention or to standard diabetes (defined as Usual Care or UC) management. Treatment assignment is incorporated to compare HbA1c outcomes between groups. 


The goal of the project is to demonstrate applied data analysis skills in a biomedical context, including data cleaning, outcome definition, group comparison, and interpretation of observational results. 


Because the dataset is observational and not designed for causal inference, results are interpreted descriptively and are intended to illustrate analytical patterns rather than establish clinical effectiveness or device superiority.


## Data Source

Dataset derived from the Insulin-Only Bionic Pancreas Pivotal Trial public research release.


Data includes:

    - Participant-level treatment information
    - Baseline and follow-up HbA1c measurements
    - Insulin delivery system used during the treatment period


Data are de-identified and contain no personally identifiable information.


## Research Objective 

To examine whether automated insulin delivery using the iLet Bionic Pancreas is associated with differences in HbA1c improvement compared to standard diabetes management within the trial population.


## Key Questions

    - Do participants using the iLet Bionic Pancreas experience differences in HbA1c improvement compared to participants using standard diabetes management?
    - Does baseline HbA1c influence magnitude of improvement within each treatment group?
    - Does diagnosis age (as a proxy for disease history) modify treatment response?
    - Are HbA1c improvements consistent across participants with and without prior CGM use?


## Study Design and Analysis Approach

This project performs a descriptive observational comparison of glycemic outcomes across insulin delivery systems using de-identified participant-level data from a diabetes treatment study. 


The analysis population consists of participants with both baseline and post-treatment HbA1c measurements available. Participants without complete outcome data are excluded from primary analysis to ensure consistent outcome comparison. 


The primary outcome variable is change in HbA1c (∆HbA1c), calculated as:

                
                ∆HbA1c = Post-treatment HbA1c - Baseline HbA1c


Participants are grouped according to the insulin delivery system used during the treatment period, including the iLet Bionic Pancreas and other insulin pump systems where available. 


The analysis focuses on descriptive comparison of outcome distributions between device groups. Results are summarized using group-level statistics and visualizations to evaluate differences in magnitude and variability of glycemic change. 


Dropout information is retained for transparency and may be summarized descriptively but is not included in primary outcome calculations due to incomplete follow-up data. 


## Methods and Tools

Initial data review performed using source documentation and data dictionaries provided with the dataset. 


Analysis conducted using:

    - Python (pandas, matplotlib)
    - Jupyter Notebook for exploratory analysis and visualization

## Skills Demonstrated

    - Clinical data integration across multiple trial tables
    - Data cleaning and deduplication of longitudinal laboratory records
    - Feature engineering of HbA1c change metrics
    - Exploratory statistical analysis and visualization
    - Reproducible research workflow design
    - Clinical data interpretation with explicit limitation framing

## Reproducibility

The analysis pipeline is fully reproducible using the provided notebook and data dictionary. Data preprocessing steps include filtering of laboratory test types, visit-based deduplication, and harmonization of insulin delivery system naming. 

## Compliance and Ethics

All analyses use publicly available, de-identified research data.


No attempt is made to identify individual participants.


Results are reported only in aggregated form.


The source of the data is the Insulin Only Bionic Pancreas Pivotal Trial, but the analyses, content and conclusions presented herein are solely the responsibility of the authors and have not been reviewed or approved by the Bionic Pancreas Research Group or Beta Bionics.

## Disclaimer

This project is exploratory and methodological in nature. Results are descriptive and do not attempt to reproduce or replace findings from the original clinical trial. 

## Project Status

Complete.
