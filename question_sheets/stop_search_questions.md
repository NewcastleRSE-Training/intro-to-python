# Notebook 4: Introduction to Working with Data

The filename for your data is ```stop_search```.

This data came from the UK Police force, https://data.police.uk/docs/, and relates to a sample of stop and searches conducted during June 2018. It has been edited for the purposes of this exercise. 

## Exercises
These exercises tie in with the notes in your notebook. Make sure you read the information in the notebook for each section of questions before attempting them. There are code blocks already created telling you where to write the code for each question.

### 1. Unique values
a. Create a list of the unique values that are in one of the columns and print the results.  
b. How many unique values are there in this column? You can look back at the previous notebook if you need a reminder how to do this.  

### 2. Basic statistics
a. See what happens when you run the ```.describe()``` command with the 'officers_present' column and a non-numerical column.
b. What is the mean age of people stopped in this dataset?

### 3. Grouping and aggregating
a. Print to the screen the mean ages of people in the dataset grouped by self_defined_ethnicity.
b. What is the max of numerical columns for stations grouped by outcome and gender?

### 4. Conditional selections
a.View only entries where the ethnicity is listed as 'White - English/Welsh/Scottish/Northern Irish/British'
b. Save the results in a variable called `new_df` (new DataFrame) and view summary information to see how many entries there are. 
c. Out of the entries in your new DataFrame, now narrow the selection to those that have are 35 years old or older.
