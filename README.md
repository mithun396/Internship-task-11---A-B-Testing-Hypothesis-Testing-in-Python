# Internship-task-11---A-B-Testing-Hypothesis-Testing-in-Python

## Project Overview
This project performs an A/B test analysis on a marketing dataset to evaluate whether displaying advertisements (Ad) leads to higher user conversion compared to a Public Service Announcement (PSA).
Using statistical hypothesis testing, the project determines if the observed difference in conversion rates is statistically significant, enabling data-driven marketing decisions.

## Dataset
- Name: Marketing A/B Testing Dataset
- File: marketing_AB.csv

## Key Columns

| Column Name     | Description                             |
| --------------- | --------------------------------------- |
| `user id`       | Unique user identifier                  |
| `test group`    | Group type (`ad` or `psa`)              |
| `converted`     | Whether the user converted (True/False) |
| `total ads`     | Number of ads shown                     |
| `most ads day`  | Day with most ad exposure               |
| `most ads hour` | Hour with most ad exposure              |

## Tools & Libraries

- Platform: Google Colab
- Language: Python

## Libraries:

- pandas
- numpy
- scipy

## Methodology

- Load and clean dataset
- Split users into control (psa) and treatment (ad)
- Calculate conversion rates
- Perform two-sample t-test
- Compute 95% confidence interval
- Visualize conversion rates

## Results Summary

| Group          | Conversion Rate |
| -------------- | --------------- |
| PSA (Control)  | Lower           |
| Ad (Treatment) | Higher          |

## Final Outcome

- Ability to make data-driven product and marketing decisions
- Real-world A/B testing experience
- Strong portfolio-ready project

