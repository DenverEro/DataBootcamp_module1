# Crowdfunding Campaign Analysis

## Background
Crowdfunding platforms like Kickstarter and Indiegogo have grown in popularity since the late 2000s, with campaigns ranging from independent creators to well-known celebrities. However, not every project succeeds in reaching its funding goal. To secure funding, a project must meet or exceed its goal, prompting organizations to analyze past projects in search of trends or insights that lead to success. This repository organizes and analyzes a dataset of 1,000 crowdfunding projects to uncover potential patterns in campaign success and failure.

## Project Overview
This project involves analyzing a dataset of 1,000 sample crowdfunding projects using Excel. The goal is to identify trends and factors that contribute to successful campaigns, as well as limitations in the dataset. This repository includes the following:

- **Data cleaning and formatting**: Conditional formatting of columns, creating new columns for calculated metrics like Percent Funded and Average Donation, and splitting combined columns into Parent and Sub-Category.
- **Pivot table analysis**: Counting successful, failed, canceled, or live campaigns by category and sub-category, and filtering by country.
- **Outcomes analysis**: Examining how the launch date impacts campaign success using Unix timestamp conversions.
- **Goal analysis**: Investigating the relationship between campaign goals and success rates using COUNTIFS() formulas and graphing results.

## Key Tasks
1. **Outcome Formatting**: Conditional formatting was used to color-code campaign outcomes (successful, failed, canceled, live).
2. **New Metrics**:
   - *Percent Funded*: Calculated how much funding was achieved relative to the goal.
   - *Average Donation*: Determined the average contribution per backer.
   - *Category Splits*: Separated Category and Sub-Category into two columns.
3. **Pivot Tables**: Created tables and graphs to analyze success rates by category and sub-category, filterable by country.
4. **Date Conversion**: Converted Unix timestamps into Excel date format to analyze outcomes by launch date.
5. **Goal-Based Success Analysis**: Evaluated the success rates of campaigns based on different goal ranges, generating a report with statistics and a line chart showing the relationship between goal amounts and campaign outcomes.
6. **Statistical Summary**: Created summary statistics for the number of backers of successful and unsuccessful campaigns, including mean, median, standard deviation, and more, to assess whether the mean or median better summarizes the data.

## Conclusion
This project provides a comprehensive analysis of crowdfunding data, offering insights into factors that contribute to campaign success. Further analysis and more robust datasets could uncover additional patterns and provide greater predictive power for future campaigns.
