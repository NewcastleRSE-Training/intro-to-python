# Introduction to Python
Repo for all materials for Introduction to Python

## Intended audience
This workshop is aimed at participants with little to no prior programming experience. Participants do not need to have completed any previous workshops with us. Participants should attend the Version Control workshop after completing Introduction to Python.

## Lesson objectives
By the end of the session, participants will:
- Have a high level understanding of what code is
- Recognise that there are many programming languages and that Python is a good place for beginners to start
- Broadly appreciate why we are using a Jupyter notebook as an interpretor
- Identify core programming concepts including data types, conditions, loops and lists
- Have experience of manipulating data stored in a CSV format

## Lesson plan
### Notebook 1 - Introduction 20 mins
Predominantly facilitator led. Participants can run and write their first lines of code.
* Session structure
* RSE team
* What to expect
* Introduction to programming
* Setup

### Notebook 2 - Data types 20 mins
Facilitator to deliver core concepts with some opportunities for participants to complete exercises. During delivery there are opportunities for discussion and for participants to be invited to guess before code blocks are run.
* floats/ integers
* strings
* boolean

### Notebook 3 - Comparisons, Loops and Lists 40 mins
There is still a core of facilitator delivery in this notebook, but there are more frequent opportunities for participants to complete short exercises to apply concepts as they are introduced. Again, the facilitator should make opportunities for discussion around the content.

### Notebook 4 - Introduction to working with data 40 mins (could be extended by adding content and extending question sheets)
This notebook is intended to give participants an introduction to some basic data manipulation using the pandas library. The first sections should be done as a group with each participant attempting to write the code themselves before the facilitator reveals the correct answers. Hidden code blocks contain template code for the facilitator to do this, although note that filenames will need to be added depending on the dataset chosen.

The exercises in this section are intended to be self directed with participants working through a question sheet using information in their notebooks. The facilitator should be on hand to address queries during this section.
* CSV
* Packages
* DataFrame
* First steps in pandas
* Exercises

## Materials required
* 4 Jupyter notebooks for instructor to present and participants to use as workbooks
* Dataset in CSV format chosen to be relevant to group from this selection (note datat has been edited to make it suitable for the exercises):
  1. early_english_books: [English Early Books Online](https://eebo.chadwyck.com/home) taken from a [Software Carpentry community developed course](https://carpentries-incubator.github.io/python-humanities-lesson/). [Questions](./question_sheets/early_english_books_questions.md). Answers.
  2. da_vinci: metadata from [British Library](https://www.bl.uk/collection-metadata/downloads) collection
  3. flood_stations: data about flood measurement stations from the [Environment Agency](https://environment.data.gov.uk/flood-monitoring/doc/reference#stations)
  4. medical_insurance: Medical insurance cost data from user on [Kaggle](https://www.kaggle.com/mirichoi0218/insurance)
  5. stop_search: Stop and search data from [UK Police API](https://data.police.uk/docs/)
* 'Answers' Jupyter notebook for chosen dataset for facilitator's reference (facilitator may want to print for reference during session)
* Question sheet for chosen dataset printed for participants


## Participant instructions
What participants need to do before attending...

## Running Jupyter notebook locally
To run locally, follow [instructions](https://docs.anaconda.com/anaconda/install/) for downloading Anaconda for your operating system and use either the Anaconda Navigator GUI or Anaconda Prompt CLI.

Install extensionsconfig viewer using `conda install -c conda-forge jupyter_contrib_nbextensions` in Anaconda Prompt. You can then browse an enable extensions using the 'Nbextensions' tab or at localhost:8889/nbextensions.

Install RISE (for presenting slides): `conda install rise`

Extensions currently in use: 'Exercise', RISE

