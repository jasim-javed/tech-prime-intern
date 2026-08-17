# Tech Prime Internship

This repository contains my daily progress during my Python internship.

## Day 1
- Installed Anaconda
- Set up Jupyter Notebook
- Learned Python basics:
  - Variables
  - Data types
  - type()
  - int, float, str, bool, bytes, NoneType
## Day 2

- Learned variable casting
- Learned string operations
- Learned string slicing
- Learned string 

## Day 3

- Learned Boolean variables and Boolean evaluation
- Explored Python lists and their operations
- Learned about tuples and their characteristics
- Studied sets and set operations
- Learned Python dictionaries and key-value pairs
- Performed operations on dictionaries:
  - Accessing values
  - Adding and updating items
  - Removing items
  - Using methods such as `keys()`, `values()`, `items()`, `get()`, `update()`, `pop()`, `clear()`, and `copy()`
- Learned the concept of nested dictionaries

## Day 4

- Learned conditional statements:
  - `if`
  - `if-else`
  - `if-elif-else`
  - Nested `if` statements
- Practiced comparison and logical operators in conditions
- Learned `while` loops and loop control
- Learned `for` loops using:
  - `range()`
  - Lists
  - Strings
- Practiced loop control statements:
  - `break`
  - `continue`
- Learned Python functions:
  - Creating functions using `def`
  - Calling functions
  - Function parameters and arguments
  - Variable-length arguments (`*args`)
  - Returning values using `return`

  ## Week 1 Mini Project: Student Management System

### Project Overview
Developed a simple console-based Student Management System using Python fundamentals learned during Week 1.

### Features
- Add a new student
- View all students
- Update student information
- Delete a student record
- Menu-driven interface
- Exit the application


## Day 6

- Installed and imported the NumPy library
- Learned how to create NumPy arrays
- Understood the difference between Python lists and NumPy arrays
- Explored one-dimensional (1D) and two-dimensional (2D) arrays
- Learned the `shape` attribute to determine array dimensions
- Practiced creating arrays using:
  - `np.array()`
- Learned the difference between:
  - Scalar (0D array)
  - 1D arrays
  - 2D arrays
- Accessed array elements using indexing
- Performed basic NumPy array operations

## Day 7

- Learned NumPy array indexing
- Accessed elements in one-dimensional (1D) arrays
- Accessed elements in two-dimensional (2D) arrays
- Understood positive and negative indexing
- Learned NumPy array slicing
- Extracted subarrays using slice notation (`start:stop:step`)
- Practiced row and column slicing in 2D arrays
- Explored slicing with different ranges and step values
- Strengthened understanding of efficient data access and manipulation using NumPy

## Day 8

- Learned NumPy data types (`dtypes`)
- Explored common NumPy data types:
- Understood the `dtype` attribute and how to check an array's data type
- Learned how to specify the data type while creating NumPy arrays
- Studied special NumPy values:
  - `np.inf` (Positive Infinity)
  - `-np.inf` (Negative Infinity)
  - `np.nan` (Not a Number)

## Day 9

- Learned statistical operations in NumPy
- Calculated the sum of array elements using `np.sum()`
- Found the minimum and maximum values using `np.min()` and `np.max()`
- Calculated the average (mean) using `np.mean()`
- Found the median using `np.median()`
- Calculated the standard deviation using `np.std()`
- Calculated the variance using `np.var()`
- Found the index of minimum and maximum values using `np.argmin()` and `np.argmax()`
- Performed statistical operations on one-dimensional and two-dimensional arrays
- Improved understanding of data analysis using NumPy

## Day 10

- Learned array creation using NumPy
- Created arrays using:
  - `np.arange()`
  - `np.linspace()`
  - `np.zeros()`
  - `np.ones()`
  - Random number generation using the `numpy.random` module
- Learned conditional selection using `np.where()`
- Understood the difference between `range()` and `np.arange()`
- Explored the difference between `np.arange()` and `np.linspace()`
- Learned about array dimensions using the `shape` attribute
- Reshaped arrays using `reshape()`
- Converted multi-dimensional arrays into one-dimensional arrays using:
  - `flatten()`
  - `ravel()`
- Understood the difference between `flatten()` and `ravel()`
- Practiced creating, reshaping, and manipulating NumPy arrays

## Week 2 Mini Project: Hospital Patient Data Analysis

### Project Overview
Developed a Hospital Patient Data Analysis system using NumPy to analyze patient information and perform basic statistical operations.

### Features
- Created patient datasets using NumPy arrays
- Displayed patient information
- Performed statistical analysis on patient data
- Calculated:
  - Total values
  - Average (Mean)
  - Minimum and Maximum values
- Used array indexing and slicing to access patient records
- Filtered patient records using `np.where()`
- Generated sample data using:
  - `np.arange()`
  - `np.linspace()`
  - `np.zeros()`
  - `np.ones()`
  - Random number generation
- Reshaped arrays using `reshape()`
- Converted arrays using `flatten()` and `ravel()`
- Generated a simple hospital analysis report

### Concepts Used
- NumPy Arrays
- Array Indexing
- Array Slicing
- Array Shape
- Reshape
- Flatten
- Ravel
- Statistical Operations
- Conditional Selection using `np.where()`
- Array Creation Functions
- Random Number Generation

### Learning Outcome
This project strengthened my understanding of NumPy by applying array creation, indexing, slicing, reshaping, statistical analysis, and conditional filtering to a real-world hospital patient dataset.

## Day 11

- Installed and imported the Pandas library
- Learned the purpose of Pandas for data analysis and manipulation
- Created and worked with Pandas Series
- Created DataFrames from dictionaries and NumPy arrays
- Loaded datasets for analysis
- Explored DataFrames using:
  - `head()`
  - `tail()`
  - `info()`
  - `describe()`
- Selected rows and columns from DataFrames
- Accessed data using:
  - `loc[]`
  - `iloc[]`
- Filtered data using conditional statements
- Identified and handled missing values
- Performed basic statistical analysis on datasets
- Understood the relationship between NumPy and Pandas in data analysis

### Learning Outcome
This session introduced Pandas for efficient data analysis and manipulation. I learned how to create, explore, filter, and analyze tabular data using DataFrames and Series, preparing me for real-world data analysis projects.


## Day 12

- Installed and imported the Pandas library
- Learned the purpose of Pandas for data analysis
- Explored the `Series` data structure
- Created Series from:
  - Python lists
  - Dictionaries
- Created Series with custom indexes
- Accessed Series elements using index labels
- Explored Series attributes:
  - `values`
  - `index`
  - `shape`
- Performed basic operations on Series:
  - `sum()`
  - `mean()`
  - `max()`
  - `min()`
- Filtered Series using conditional expressions
- Practiced data manipulation using Pandas Series

### Learning Outcome
This session introduced the fundamentals of the Pandas library. I learned how to create, access, analyze, and manipulate data using Pandas Series, providing a foundation for working with DataFrames and real-world datasets.

## day 13


### Pandas DataFrame Operations

#### Topics Covered

- Created Pandas DataFrames from scratch using dictionaries
- Read datasets from CSV and Excel files into DataFrames
- Performed column manipulation by adding, updating, and deleting columns
- Applied arithmetic operations on DataFrame columns
- Identified and handled missing (null) values using Pandas functions
- Filtered data using conditional statements
- Explored unique values and detected duplicate records
- Retrieved rows using index labels with `loc[]` and positions with `iloc[]`
- Replaced values using the `replace()` method
- Renamed columns and row indexes using `rename()`
- Applied custom functions using `apply()` and `lambda`
- Grouped data using `groupby()`
- Performed grouping with multiple columns for advanced analysis
- Combined DataFrames using `concat()`
- Merged DataFrames using `merge()`
- Joined DataFrames using `join()`
- Worked with date and time data using Pandas datetime functions

### Learning Outcome

This session strengthened my understanding of Pandas DataFrame operations, including data creation, manipulation, filtering, handling missing values, grouping, combining datasets, and working with date and time. These concepts provide the foundation for performing real-world data analysis and preparing datasets for visualization and machine learning.

## week 4

### Data Visualization using Matplotlib

#### Topics Covered

- Imported and configured the Matplotlib library for data visualization
- Created basic line plots
- Visualized IMDb movie revenue using line plots
- Plotted relationships between runtime, votes, and metascore
- Customized line plots using:
  - Colors
  - Line styles
  - Markers
  - Line width
- Added chart elements:
  - Titles
  - X-axis labels
  - Y-axis labels
  - Grid
  - Legends
- Created scatter plots to visualize relationships between variables
- Created bar charts for categorical data comparison
- Generated histograms to analyze data distribution
- Worked with subplots to display multiple charts in a single figure
- Created zoomed-in subplots to highlight specific data regions
- Designed pie charts to visualize percentage distributions
- Customized figure size and layout using `figure()` and `figsize`

### Learning Outcome

This session introduced the fundamentals of data visualization using Matplotlib. I learned how to create and customize different types of charts, compare datasets visually, and present data effectively through line plots, scatter plots, bar charts, histograms, pie charts, and subplots. These visualization techniques are essential for exploratory data analysis and reporting.

## Week 4 Mini Project: Netflix Data Analysis

### Project Overview

Developed a Netflix Data Analysis project using **Pandas** for data manipulation and **Matplotlib** for data visualization. The project analyzes a sample Netflix dataset to gain insights into ratings, genres, views, and release years through statistical analysis and graphical representation.

### Features

- Created and managed a Netflix dataset using a Pandas DataFrame
- Explored the dataset using:
  - `head()`
  - `info()`
  - `describe()`
- Filtered data based on different conditions
- Found the highest and lowest rated shows
- Calculated average ratings and views
- Counted shows by genre using `value_counts()`
- Retrieved the most viewed shows using `nlargest()`
- Created new columns using `apply()` with `lambda`
- Performed data grouping using `groupby()`
- Visualized the dataset using:
  - Line Plot
  - Scatter Plot
  - Bar Chart
  - Pie Chart
- Customized charts with titles, labels, markers, and grid

### Concepts Used

- Pandas DataFrame
- Data Exploration
- Data Filtering
- Statistical Analysis
- `value_counts()`
- `groupby()`
- `apply()` with `lambda`
- Matplotlib
- Line Plot
- Scatter Plot
- Bar Chart
- Pie Chart
- Data Visualization

### Learning Outcome

This project enhanced my understanding of data analysis and visualization using Pandas and Matplotlib. I learned how to organize, analyze, summarize, and visualize datasets to extract meaningful insights, strengthening my practical skills in Python for data analysis.


## EDA Practice

- Practiced Exploratory Data Analysis (EDA) using Pandas
- Explored datasets using `head()`, `shape`, and `describe()`
- Checked missing and duplicate values
- Worked with unique values and value counts
- Practiced filtering DataFrames
- Performed basic statistical analysis
- Used `groupby()` for data analysis
- Practiced correlation between numerical columns
- Created basic visualizations using Matplotlib:
  - Histogram
  - Scatter Plot
  - Bar Chart

### Learning Outcome

Practiced the basic process of exploring, understanding, and analyzing data using Pandas and Matplotlib as part of Exploratory Data Analysis (EDA).