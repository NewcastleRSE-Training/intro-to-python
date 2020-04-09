# Notebook 4: Introduction to Working with Data

The filename for your data is ```da_vinci```.

This data came from a British Library dataset describing their DaVinci collection, although it has been edited for the purposes of this exercise. You can view more here: https://www.bl.uk/collection-metadata/downloads

## Exercises
These exercises tie in with the notes in your notebook. Make sure you read the information in the notebook for each section of questions before attempting them. There are code blocks already created telling you where to write the code for each question.

### 1. Unique values
a. Create a list of the unique values that are in one of the columns and print the results.  
b. How many unique values are there in this column? You can look back at the previous notebook if you need a reminder how to do this.  

### 2. Basic statistics
a. See what happens when you run the ```.describe()``` command with a numerical and non-numerical column.
b. How many pages does the longest book in the data have?


### 3. Grouping and aggregating
a. What is the mean page count for books by Alibizzi? Hint: begin by creating data that is grouped by author (the 'Name' column). 
b. What is the mean page count for books grouped by publishing location and date?   

### 4. Conditional selections
a.View only entries that were published in England.
b. Save the results in a variable called `new_df` (new DataFrame) and view summary information to see how many entries there are.
c. Out of the entries in your new DataFrame, now narrow the selection to those that have a page count that is greater than or equal to 46 and print the first 3 entries to the screen. 
