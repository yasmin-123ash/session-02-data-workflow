# Session 02 - Data Workflow

## Project Overview

This project focuses on inspecting, exploring, and auditing the Palmer Penguins dataset before any modeling.

The goal is to understand the structure of the data, identify data quality issues, explore relationships between variables, and document the findings in a reproducible workflow.

## Dataset

The dataset used in this project is the Palmer Penguins dataset.

It contains information about penguin species, islands, body measurements, and sex.

## Questions Investigated

1. Do penguin species differ in average body mass?
2. Is flipper length related to body mass?
3. Does the relationship between flipper length and body mass look different across species?
4. Which islands contain which species?
5. Do male and female penguins appear to differ in body mass?

## Key Findings

- Gentoo penguins have a higher average body mass than Adelie and Chinstrap penguins in this dataset.
- Flipper length and body mass show a strong positive correlation.
- The species form different groups in the relationship between flipper length and body mass.
- Species are not distributed equally across the three islands.
- Male penguins have a higher average body mass than female penguins in this dataset.

## Data Quality Issues

- The dataset contains missing values in some numerical columns and in the sex column.
- There are no duplicate rows.
- IQR analysis did not identify body mass values outside the statistical bounds.
- Missing values and unusual values were not automatically removed or changed.

## How to Run

1. Open the notebook in the `notebooks` folder.
2. Make sure the required Python libraries are installed.
3. Run the notebook from top to bottom.

## Limitations

This project is a descriptive data analysis and data quality audit. No predictive model was trained.

The findings describe patterns in this dataset and do not establish causal relationships.

## Next Step

The next step would be to clean and prepare the data carefully before applying a machine learning model.

The dataset was saved locally in the project so the analysis can be rerun without downloading the data again.
## Reflection

The most important data quality issue was the presence of missing values. Before building a real machine learning model, I would verify the missing values, unusual values, and the meaning of each feature before deciding how to clean the data.