# Module 4 Challenge

## Analysis

For this challenge we used the Pandas library to import, collect, prepare, summarize, drill down and compare data. 

### Step 1

Used the os.path.join to import the csv data and tested using student_df.head() to make sure it was imported correctly

### Step 2

Prepapred the data by cleaning up any null values, dropping duplicates and removing the "th" from the grades. Then converted the grades into integers

### Step 3

Summarized the data using .describe() and displayed different things like the mean, minimum for different columns.

### Step 4

Used loc and iloc to find different columns, as well as getting a specific column to describe.

### Step 5

Used groupby and loc to compare different sets of data: budget, scores and total number of students in a school.