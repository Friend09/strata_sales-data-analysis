# strata_sales-data-analysis

stratascratch data project
[assignment_link](https://platform.stratascratch.com/data-projects/sales-data-analysis)

# Sales Data Analysis

_This data project has been used as a take-home assignment in the recruitment process for the data science positions at 23andMe._

## Assignment

### EDA

Please answer the questions below based on the data provided:

1. Plot daily sales for all 50 weeks.
2. It looks like there has been a sudden change in daily sales. What date did it occur?
3. Is the change in daily sales at the date you selected statistically significant? If so, what is the p-value?
4. Does the data suggest that the change in daily sales is due to a shift in the proportion of male-vs-female customers? Please use plots to support your answer (a rigorous statistical analysis is not necessary).
5. Assume a given day is divided into four dayparts:
   - night (12:00AM - 6:00AM),
   - morning (6:00AM - 12:00PM),
   - afternoon (12:00PM - 6:00PM),
   - evening (6:00PM - 12:00AM).
     What is the percentage of sales in each daypart over all 50 weeks?

## Data Description

The `datasets/` directory contains fifty CSV files (one per week) of timestamped sales data. Each row in a file has two columns:

- `sale_time` - The timestamp on which the sale was made e.g. `2012-10-01 01:42:22`
- `purchaser_gender` - The gender of the person who purchased (male or female)

## Practicalities

Please work on the questions in the displayed order. Make sure that the solution reflects your entire thought process - it is more important how the code is structured rather than the final answers. You are expected to spend no more than 1-2 hours solving this project.

## Project setup

- first create a repo on github
  - include a README.md file
  - include .gitignore file (python based template)
- then clone the repo to a local directory
- cd into the cloned directory
- create the following
  - a practise jupyter notebook
  - requirements.txt
  - Makefile
- create a virtual environment `python3 -m venv venv`
- activate the venv `source venv/bin/activate`
- open the notebook to start the work (prefer PyCharm for this project)
  - read all the instructions first from the URL

## Project approach

- load the data
