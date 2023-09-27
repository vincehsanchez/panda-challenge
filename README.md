# panda-challenge
In this assignment, we create and manipulate Pandas DataFrames to analyze school and standardized test data.

Using Pandas and Jupyter Notebook, we create a report that includes the following data. Our report includes a 

written description of observable trends based on the data.

District Summary

Calculate then create a high-level snapshot of the district's key metrics in a DataFrame with the following:
	
  Total number of unique schools
  
  Total students
	
  Total budget
	
  Average math score
	
  Average reading score
	
  % passing math (the percentage of students who passed math)
	
  % passing reading (the percentage of students who passed reading)
	
  % overall passing (the percentage of students who passed math AND reading)

School Summary
Calculate and then create a DataFrame that summarizes key metrics about each school with the following:
	School name
	School type
	Total students
	Total school budget
	Per student budget
	Average math score
	Average reading score
	Passing math rate (the percentage of students who passed math)
	Passing reading rate (the percentage of students who passed reading)
	Overall passing rate (the percentage of students who passed math AND reading)
	Highest-Performing Schools (by Overall Passing)

Sort schools by Overall Passing in  d e s c e n d i n g  order and display the top 5 rows.
Sort schools by Overall Passing in  a s c e n d i n g  order and display the top 5 rows.

Math Scores by Grade
Create a DataFrame that lists the average math score by grade (9th, 10th, 11th, 12th) at each school.

Reading Scores by Grade
Create a DataFrame that lists the average reading score by grade (9th, 10th, 11th, 12th) at each school.

Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student).
Use bins to create reasonable cutoff values for grouping school spending.
Calculate mean scores per spending range.
Create a DataFrame called spending_summary with the following metrics in the table:
	Average math score
	Average reading score
	Passing math rate (the percentage of students who passed math)
	Passing reading rate (the percentage of students who passed reading)
	Overall passing rate (the percentage of students who passed math AND reading)

Scores by School Size
Use bins to create a DataFrame called size_summary comparing school performance based and school size (small, medium, or large).

Scores by School Type
Use per_school_summary DataFrame to create a new DataFrame called type_summary.
New DataFrame shows school performance based on the "School Type".
