# Instructions for Notebook 4: Introduction to Working with Data

The filename for your data is ```early_english_books```.

todo - say where data is from

## Exercises
These exercises tie in with the notes in your notebook. Make sure you read the information in the notebook for each section of questions before attempting them. There are code blocks already created telling you where to write the code for each question.

### 1. Unique values
a. Create a list of the unique values that are in one of the columns.  
b. How many unique values are there in this column? You can look back at the previous notebook if you need a reminder how to do this.  

### 2. Basic statistics
a. See what happens when you run the ```.describe()``` command with a numerical and non-numerical column.
b. How many pages does the longest book in the data have?

### 3. Grouping and aggregating
a. What is the mean page count for books published in Amsterdam? Hint: begin by creating data that is grouped into publishing location. 
b. What is the mean page count for books grouped by publishing location and date?   

### 4. Conditional selections
a.View only entries that were published in London. If you need to remind yourself of the data, you can print the first few lines to the   screen again.  
b. Save the results in a variable called `new_df` (new DataFrame) and view summary information to see how many entries there are for London.  
c. Out of the entries in your new DataFrame, now narrow the selection to those that have a page count equal to or over 46 and print the first 3 entries to the screen using the method ```.head(3)```.    
