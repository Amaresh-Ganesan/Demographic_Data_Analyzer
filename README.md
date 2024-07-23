
# Demographic Data Analysis

This repository contains a Python script for analyzing demographic data from the UCI Machine Learning Repository's Adult dataset. The script calculates various statistics about the dataset, including race counts, average age of men, percentage of people with Bachelor's degrees, and more.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Output](#output)
- [Contributing](#contributing)


## Introduction

The **Demographic Data Analysis** project uses a dataset containing demographic information to compute various statistics. This tool is useful for understanding the composition and characteristics of the dataset, particularly in terms of education, work hours, and income.

## Features

- Counts the number of people of each race represented in the dataset.
- Calculates the average age of men.
- Computes the percentage of people who have a Bachelor's degree.
- Determines the percentage of people with advanced education (Bachelor's, Master's, or Doctorate) who earn more than 50K.
- Calculates the percentage of people without advanced education who earn more than 50K.
- Finds the minimum number of hours a person works per week.
- Computes the percentage of people who work the minimum number of hours per week and earn more than 50K.
- Identifies the country with the highest percentage of people earning more than 50K.
- Finds the most popular occupation for those who earn more than 50K in India.

## Installation

To use this project, you need to have Python and Pandas installed on your system. You can install Pandas using pip:

\`\`\`bash
pip install pandas
\`\`\`

## Usage

1. Clone this repository to your local machine.
2. Ensure that you have the required dependencies installed.
3. Place the dataset file (\`adult.data.csv\`) in the same directory as the script.
4. Run the script to compute and display the statistics.

\`\`\`python
from demographic_data_analyzer import calculate_demographic_data

calculate_demographic_data(print_data=True)
\`\`\`

## Output

The script will output the following information:

- Number of each race:
  \`\`\`
  White                 27816
  Black                  3124
  Asian-Pac-Islander     1039
  Amer-Indian-Eskimo      311
  Other                   271
  \`\`\`

- Average age of men: \`39.4\`

- Percentage with Bachelor's degrees: \`16.4%\`

- Percentage with higher education that earn >50K: \`46.5%\`

- Percentage without higher education that earn >50K: \`17.4%\`

- Minimum work time: \`1 hours/week\`

- Percentage of rich among those who work fewest hours: \`10.0%\`

- Country with highest percentage of rich: \`Iran\`

- Highest percentage of rich people in country: \`41.9%\`

- Top occupations in India: \`Prof-specialty\`

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


