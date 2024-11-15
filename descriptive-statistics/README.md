# Trades of Financial Operations

Welcome to the "Trades of Financial Operations" project. This project involves modifying a provided spreadsheet to gain a deeper understanding of trading data and perform various financial analyses. Below you will find a comprehensive overview of the project, instructions for using the Excel file, and explanations of the tasks and analyses conducted.

## Project Overview

This project is designed to help you analyze and manipulate financial trading data. The provided Excel workbook consists of four sheets, each serving a different purpose in analyzing Bob's trades from January 1, 2021, onward. The goal is to explore the data, calculate insights, and visualize key metrics.

### Dataset Description

The dataset represents trading operations performed by Bob, with the following columns:

- **TradeID:** Unique identifier for the trade (8-digit number).
- **Stock Exchange:** Market where the trade occurred.
- **Region:** Country or confederation of the stock exchange.
- **Date Added:** Date when the trade was made (YYYY-MM-DD format).
- **Quantity:** Number of shares traded (bought/sold).
- **Buy Price:** Price per share when the trade was executed.
- **Date Sold:** Date when the trade was completed (YYYY-MM-DD format).
- **Sell Price:** Price per share at the time of sale.

## Excel Workbook Structure

The Excel workbook contains four sheets, each focused on different aspects of the trading data. Below are detailed descriptions for each sheet, including the required styles, contents, and tasks to be performed.

### 1. `My Trades`

- **Description:** This sheet contains the raw trading data with the required date formatting and additional calculations.
- **Contents:**
  - **TradeID:** Trade identifier.
  - **Stock Exchange:** Market of the trade.
  - **Region:** Country or confederation.
  - **Date Added:** Date of trade in DD/MM/YY format.
  - **Quantity:** Number of shares traded.
  - **Buy Price:** Price per share at purchase.
  - **Date Sold:** Date of trade completion in DD/MM/YY format.
  - **Sell Price:** Price per share at sale.
- **Tasks:**
  - Format the dates in `Date Added` and `Date Sold` columns to DD/MM/YY.
  - **Add the following columns:**
    - **Duration:** Calculate the number of days between `Date Added` and `Date Sold`.
    - **Profit:** Calculate the profit (or loss) from each trade. Use the formula:
      ```
      Profit = (Sell Price - Buy Price) * Quantity
      ```
    - **Format:** Ensure that the `Profit` column is displayed as USD currency with 5 decimal places.
  - **Visualization:** Create a bar chart showing the frequency of different durations of trades.
  - **Commentary:** Add a text box below the bar chart to comment on the distribution of trade durations and discuss whether it follows a normal distribution.

- **Styling:**
  - **Header Font:** Comics Sans MS, 12pt, blue color.
  - **Borders:** Double border around the header; single border around all other cells.
  - **Cell Background:** White with no extra borders or lines outside the table.

### 2. `Stock Exchanges`

- **Description:** This sheet summarizes trade activities by stock exchange and region.
- **Contents:**
  - **Region:** Country or confederation.
  - **Stock Exchange:** Market of the trade.
  - **Num of Trades:** Total number of trades per region.
  - **Mandatory to Pay Taxes:** Whether taxes must be paid based on the total quantity of trades in the region.
- **Tasks:**
  - **Pivot Table:** Create a pivot table to group markets by region and calculate the number of trades per region.
  - **Tax Calculation:** Add a column to indicate "yes" or "no" for tax payment requirements based on whether the total number of shares traded in a region is 67 or more.
  - **Styling:**
    - **Header Font:** Comics Sans MS, 12pt, blue color.
    - **Borders:** Double border around the header; single border around all other cells.
    - **Cell Background:** White with no extra borders or lines outside the table.

### 3. `Profit Insights`

- **Description:** This sheet provides a detailed analysis of trade profits and the duration of trades.
- **Contents:**
  - **TradeID:** References to all trades from the `My Trades` sheet.
  - **Duration:** Number of days between `Date Added` and `Date Sold`.
  - **Profit:** Calculated profit for each trade.
- **Tasks:**
  - **Profit Calculation:** Ensure that profit values are displayed in USD with 5 decimal places.
  - **Chart:** Create a bar chart to show the frequency distribution of trade durations.
  - **Commentary:** Add a text box to explain the chart and assess whether the duration of trades follows a normal distribution.
- **Styling:**
  - **Header Font:** Comics Sans MS, 12pt, blue color.
  - **Borders:** Double border around the header; single border around all other cells.
  - **Cell Background:** White with no extra borders or lines outside the table.

### 4. `Number of Trades Exchanged`

- **Description:** This sheet analyzes the distribution of the number of trades across regions and calculates specific probabilities.
- **Contents:**
  - **Region:** Country or confederation.
  - **Number of Trades:** Count of trades per region.
- **Tasks:**
  - **Contingency Table:** Create a table to show the number of trades per region.
  - **Marginal Distributions:** Add marginal distributions for both regions and trade counts, with a grand total in the bottom-right corner.
  - **Probability Calculations:**
    - **UK Probability:** Calculate the probability that a randomly chosen trade was executed exactly 7 times in the UK.
    - **Asian Probability:** Calculate the probability that a randomly chosen trade was executed in any Asian state with a quantity not exceeding 8 units.
    - **Add Results:** Place these calculations in columns starting from column M.
- **Styling:**
  - **Header Font:** Comics Sans MS, 12pt, blue color.
  - **Borders:** Double border around the header; single border around all other cells.
  - **Cell Background:** White with no extra borders or lines outside the table.

## Instructions for Using the Excel Workbook

1. **Open the Excel File:** Download the `Trading_Financial_Operations.xlsx` file from the repository.
2. **Review `My Trades`:** Check the `My Trades` sheet for the raw data and perform the required calculations and visualizations.
3. **Explore `Stock Exchanges`:** Use the `Stock Exchanges` sheet to analyze trade activity by region and determine tax requirements.
4. **Analyze `Profit Insights`:** In the `Profit Insights` sheet, calculate profits, visualize trade durations, and add comments on the trade duration distribution.
5. **Examine `Number of Trades Exchanged`:** Create the contingency table, calculate probabilities, and add results in the specified columns.

## Results and Analysis

- **Profit Analysis:** The `Profit Insights` sheet provides a detailed breakdown of trade profits and the distribution of trade durations.
- **Trade Activity Summary:** The `Stock Exchanges` sheet summarizes the number of trades by market and region, including tax obligations.
- **Trade Distribution:** The `Number of Trades Exchanged` sheet shows how trades are distributed across regions and calculates specific probabilities related to trade quantities.




