# Notebook 4: Introduction to Working with Data

The filename for your data is ```flood_stations```.

This data came from the environment agency: https://environment.data.gov.uk/flood-monitoring/doc/reference#stations. It has been edited for the purposes of this exercise. 

## Exercises
These exercises tie in with the notes in your notebook. Make sure you read the information in the notebook for each section of questions before attempting them. There are code blocks already created telling you where to write the code for each question.

### 1. Unique values
a. Create a list of the unique values that are in one of the columns and print the results.  
b. How many unique values are there in this column? You can look back at the previous notebook if you need a reminder how to do this.  

### 2. Basic statistics
a. See what happens when you run the ```.describe()``` command with a numerical and non-numerical column.
b. What is the largest number in the 'limit' column?

### 3. Grouping and aggregating
a. Print to the screen the max limits grouped by catchment. 
b. What is the mean of numerical columns for stations gruped by river name and whether they are active?

### 4. Conditional selections
a.View only stations associated with the River Thames.
b. Save the results in a variable called `new_df` (new DataFrame) and view summary information to see how many entries there are.
c. Out of the entries in your new DataFrame, now narrow the selection to those that have a limit that is greater than or equal to 500 and print the first 3 entries to the screen. 
