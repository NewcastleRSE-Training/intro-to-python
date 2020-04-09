# Instructions for Notebook 4: Introduction to Working with Data

The filename for your data is ```medical_insurance```.

Dataset sourced from: https://www.kaggle.com/datasets. It has been edited for the purposes of this exercise. 

## Exercises
These exercises tie in with the notes in your notebook. Make sure you read the information in the notebook for each section of questions before attempting them. There are code blocks already created telling you where to write the code for each question.

### 1. Unique values
a. Create a list of the unique values that are in one of the columns and print to the screen.  
b. How many unique values are there in this column? You can look back at the previous notebook if you need a reminder how to do this.  

### 2. Basic statistics
a. See what happens when you run the ```.describe()``` command with a numerical and non-numerical column.
b. What is the highest charge?

### 3. Grouping and aggregating
a. What is the mean charge for non-smokers? Hint: begin by creating data that is grouped by the smoker column. 
b. What is the mean bmi for people grouped by gender and whether or not they smoke?   

### 4. Conditional selections
a. View only entries for people over the age of 35. 
b. Save the results in a variable called `new_df` (new DataFrame) and view summary information to see how many entries there are.  
c. Out of the entries in your new DataFrame, now narrow the selection to those that have a bmi that is less than or equal to 26 and print the first 3 entries to the screen. 
