

# User Data Analysis

This project involves the analysis of user data using Python and the Pandas library. The dataset is obtained from [this source](https://raw.githubusercontent.com/justmarkham/DAT8/master/data/u.user), and it contains information about users' ages, genders, occupations, and more.

## Project Overview

This repository contains Python code for analyzing user data using the Pandas library. The analysis includes various steps to explore and understand the dataset, such as calculating statistics, summarizing columns, and determining frequent values. The primary goals of this project are:

- Analyze user data dataset using Pandas.
- Calculate statistics like the number of observations, number of columns, and more.
- Summarize columns to gain insights into data.
- Determine the mean age of users and the least frequent age.

## Steps in the Analysis

1. Import necessary libraries, including Pandas and NumPy.
2. Import the user data dataset from the provided source.
3. Assign the dataset to a variable called `users` and set 'user_id' as the index.
4. Display the first 25 and last 10 entries in the dataset.
5. Determine the number of observations and columns in the dataset.
6. Print the names of all the columns.
7. Explore dataset indexing.
8. Print the data type of each column.
9. Print only the 'occupation' column.
10. Calculate the number of different occupations in the dataset.
11. Determine the most frequent occupation.
12. Summarize the DataFrame using `describe()` and `info()` functions.
13. Summarize all the columns using `describe()` with `include='all'`.
14. Summarize only the 'occupation' column using `describe()`.
15. Calculate the mean age of users.
16. Determine the age with the least occurrence.

## Repository Structure

```
User-Data-Analysis/
│
├── user_analysis.ipynb            # Jupyter Notebook with analysis code
├── u.user                         # Dataset file
└── readme.md                      # Project summary
```

## Usage

1. Clone the repository using: `git clone https://github.com/your-username/User-Data-Analysis.git`
2. Navigate to the repository: `cd User-Data-Analysis`
3. Open the `user_analysis.ipynb` notebook to see the detailed analysis steps and results.

## Acknowledgments

- The dataset is sourced from [justmarkham](https://github.com/justmarkham) on GitHub.
- Special thanks to the contributors of the Pandas and NumPy libraries for providing the tools for data analysis.

---
