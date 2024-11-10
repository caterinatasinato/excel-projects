# Data Generation for Luggnagg Population

Welcome to the repository for the Data Generation and Analysis for the population of Luggnagg. This project involves creating a dataset, performing data manipulations, and conducting statistical analyses using Excel. Below, you will find a detailed overview of the project, instructions on how to use the provided Excel file, and explanations of the analysis conducted.

## Project Overview

This project is designed to consolidate the concepts learned in the course of inferential statistics with Excel that I learned in my MA in Data Analytics by generating and analyzing data. The Excel workbook consists of 6 sheets, each dedicated to different aspects of data manipulation and analysis. The dataset simulates the ages of a population and involves statistical operations including sampling, correlation analysis, and linear regression.

### Dataset Description

The dataset simulates the ages of 250 individuals in a fictional population of Luggnagg. The data is generated using a normal distribution with specified parameters.

**Dataset Structure:**
- **Number of Rows:** 250
- **Number of Columns:** 2
- **Columns:**
  - **Age:** The age of the individual.
  - **Group:** A randomly assigned group number from 1 to 4.

## Excel Workbook Structure

### Sheet 1. `Parameters`

- **Description:** This sheet contains the parameters used for generating the age data.
- **Contents:**
  - **Probability:** The probability value.
  - **Mean:** The mean age of the population.
  - **StdDev:** The standard deviation of the age distribution.
- **Styling:** 
  - **Header Font:** Comics Sans MS, 12pt, blue color.
  - **Borders:** Double border around header; single border around other cells.
  - **Cell Background:** White with no borders or lines outside the table.

### Sheet 2. `Data`

- **Description:** This sheet contains the generated age data and group assignments.
- **Contents:**
  - **Age:** A column with the ages of 250 individuals.
  - **Groups:** Randomly assigned group numbers between 1 and 4.
- **Styling:** 
  - **Header Font:** Comics Sans MS, 12pt, blue color.
  - **Borders:** Double border around header; single border around other cells.
  - **Cell Background:** White with no borders or lines outside the table.

### Sheet 3. `Sample`

- **Description:** This sheet includes the generated age data, assigned groups, and a filtered sample based on the selected group.
- **Contents:**
  - **Data:** The ages copied from the `Data` sheet.
  - **Groups:** The group numbers assigned to each age.
  - **Sample Data:** Ages from one of the groups (chosen between 1, 2, 3, or 4).
- **Styling:** 
  - **Header Font:** Comics Sans MS, 12pt, blue color.
  - **Borders:** Double border around header; single border around other cells.
  - **Cell Background:** White with no borders or lines outside the table.

### Sheet 4. `Statistical Insight`

- **Description:** This sheet provides statistical insights and calculations based on the sample data.
- **Contents:**
  - **STDDEV:** Standard deviation of the sample.
  - **EXPECTED VALUE:** The expected value (mean) of the sample.
  - **COUNT:** The count of numbers in the sample.
  - **CONFIDENCE RATE:** The confidence level used for the confidence interval.
  - **Estimation of p parameter:** p-value estimation.
  - **Confidence Interval:** The confidence interval for the sample mean.
  - **Explanation:** A text box explaining the obtained values and their significance.
- **Styling:** 
  - **Header Font:** Comics Sans MS, 12pt, blue color.
  - **Borders:** Double border around header; single border around other cells.
  - **Cell Background:** White with no borders or lines outside the table.

### Sheet 5. `Uncorrelated Variables`

- **Description:** This sheet explores the correlation between age and the number of cats, and between age and the age of a partner.
- **Contents:**
  - **Sample Data:** Ages copied from the `Sample` sheet.
  - **Number of Cats:** Random numbers from 1 to 7.
  - **Age of Partner:** Age calculated based on correlation and other variables.
  - **Correlation Analysis:** Calculates and explains the correlation between age and the number of cats.
  - **Desired Correlation:** A correlation value you aim to achieve.
  - **Actual Correlation:** The actual calculated correlation.
  - **Explanation:** A text box explaining the results of the correlation analysis.
- **Styling:** 
  - **Header Font:** Comics Sans MS, 12pt, blue color.
  - **Borders:** Double border around header; single border around other cells.
  - **Cell Background:** White with no borders or lines outside the table.

### Sheet 6. `Linear Regression`

- **Description:** This sheet contains a linear regression analysis between age and rank.
- **Contents:**
  - **Y (age):** Ages of the sample and partners.
  - **X (rank):** A progressive integer indicating the order of sampling.
  - **Scatterplot:** Scatterplot of age versus rank.
  - **Regression Analysis:** Linear regression for the 160th participant.
  - **Explanation:** A text box explaining the results of the linear regression.
- **Styling:** 
  - **Header Font:** Comics Sans MS, 12pt, blue color.
  - **Borders:** Double border around header; single border around other cells.
  - **Cell Background:** White with no borders or lines outside the table.

## How to Use the Excel Workbook

1. **Review the Parameters:** Check the `Parameters` sheet for the values used in the data generation.
2. **Explore the Data:** Analyze the `Data` sheet to view the generated age data and group assignments.
3. **Analyze the Sample:** Use the `Sample` sheet to review the subset of data and analyze the chosen group.
4. **Perform Statistical Analysis:** Review the `Statistical Insight` sheet for statistical calculations and interpretations.
5. **Examine Correlations:** Check the `Uncorrelated Variables` sheet for the correlation analysis and explanations.
6. **Review the Linear Regression:** Use the `Linear Regression` sheet to view the regression analysis and the related scatterplot.

## Results and Analysis

- **Statistical Insights:** The `Statistical Insight` sheet provides a comprehensive summary of the sample data's statistics including standard deviation, mean, confidence interval, and p-value.
- **Correlation Analysis:** The `Uncorrelated Variables` sheet demonstrates how the chosen variables relate to one another, and the actual versus desired correlation values are explained.
- **Linear Regression:** The `Linear Regression` sheet contains a scatterplot and regression results, providing insights into the relationship between age and rank.
  



