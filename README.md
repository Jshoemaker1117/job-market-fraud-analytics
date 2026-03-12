# Job Market Fraud Analytics
Detecting Suspicious Tech Job Postings Using Data Analysis

## Overview
Online job scams have become increasingly common, especially in the tech industry where remote work opportunities attract a large number of applicants. Fraudulent job postings can mislead job seekers, steal personal information, or request money under false pretenses.

This project analyzes job posting data to identify patterns associated with fraudulent job opportunities and builds a simple fraud risk scoring framework.

## Business Question
How can data analysis help detect suspicious tech job postings and identify patterns associated with fraud?

## Dataset
The dataset contains 3,000 job postings with attributes including:

- job title
- company name
- salary range
- industry
- location
- contact email
- company website
- telecommuting status
- job description length
- fraud label (`is_fake`)

## Key Analysis Steps
1. Data Inspection
2. Fraud vs Real Job Distribution
3. Missing Company Information Analysis
4. Remote Job Pattern Analysis
5. Email Domain Analysis
6. Salary Pattern Analysis
7. Job Description Length Analysis
8. Fraud Signal Engineering
9. Fraud Risk Scoring System
10. Fraud Rate Visualization

## Key Findings
- Fraudulent job postings consistently lacked company identity information.
- Fake postings used free email providers (e.g., Gmail), while real postings used corporate domains.
- Legitimate job postings contained longer job descriptions.
- Remote job status alone was not a strong fraud indicator.
- Combining multiple fraud signals into a fraud score clearly separated legitimate postings from fraudulent ones.

## Fraud Detection Signals
The project engineered several fraud indicators:

- Missing company information
- Free email domains
- Short job descriptions
- Remote job indicator

These signals were combined to produce a **fraud risk score** that predicts suspicious job postings.

## Visualization
A fraud score visualization demonstrates that the probability of fraud increases as more suspicious signals appear in a job posting.

## Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Project Outcome
This project demonstrates how exploratory data analysis and feature engineering can be used to identify patterns associated with fraudulent job postings and build a simple fraud detection framework.
