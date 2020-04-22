# Introduction to Python
Repo for all materials for Introduction to Python

## Intended audience
This workshop is aimed at participants with little to no prior programming experience. Participants do not need to have completed any previous workshops with us. Participants should attend the Version Control workshop after completing Introduction to Python.

## Lesson objectives
By the end of the session, participants will:
- Have a high level understanding of what code is
- Recognise that there are many programming languages and that Python is a good place for beginners to start
- Broadly appreciate why we are using a Jupyter notebook as an interpreter
- Identify core programming concepts including data types, conditions, loops and lists
- Have experience of manipulating data stored in a CSV format

## Lesson outline
* Notebook 1 - Introduction 
* Notebook 2 - Data types 
* Notebook 3 - Comparisons, Loops and Lists
* Notebook 4 - Introduction to working with data  
[Lesson plan](./lesson-plan.md)  

## Materials required
* 4 Jupyter notebooks for instructor to present and participants to use as workbooks
* Dataset, question sheets for participants (printed and digital), and answer notebook (for facilitator reference), for chosen dataset:
  1. early_english_books: [English Early Books Online](https://eebo.chadwyck.com/home) taken from a [Software Carpentry community developed course](https://carpentries-incubator.github.io/python-humanities-lesson/).  
  [Questions](./question_sheets/early_english_books_questions.md).   
  [Answers](./facilitator_docs/Answers_early_english_books.ipynb).  
  2. da_vinci: metadata from [British Library](https://www.bl.uk/collection-metadata/downloads) collection.  
  [Questions](./question_sheets/da_vinci_questions.md).   
  [Answers](./facilitator_docs/Answers_da_vinci.ipynb).  
  3. flood_stations: data about flood measurement stations from the [Environment Agency](https://environment.data.gov.uk/flood-monitoring/doc/reference#stations).   
  [Questions](./question_sheets/flood_stations.md).   
  [Answers](./facilitator_docs/Answers_flood_stations.ipynb).  
  4. medical_insurance: Medical insurance cost data from user on [Kaggle](https://www.kaggle.com/mirichoi0218/insurance).  
    [Questions](./question_sheets/medical_insurance_questions.md).   
  [Answers](./facilitator_docs/Answers_medical_insurance.ipynb).  
  5. stop_search: Stop and search data from [UK Police API](https://data.police.uk/docs/).  
    [Questions](./question_sheets/stop_search_questions.md).   
  [Answers](./facilitator_docs/Answers_stop_search.ipynb).  
* [Exemplar solutions notebook](./facilitator_docs/exemplar_solutions_nbs_2+3) for notebooks 2 and 3 for facilitator reference if required. Faciliator may wish to make this availbale to participants for reference.

## Facilitator instructions
When running the notebooks to present you can either run them locally on your own machine or access them through the same link as participants through binder:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/NewcastleRSE-Training/intro-to-python.git/master)

Note: Currently, the exercise extension is not working in Binder and therefore solutions have been removed from the notebooks. 

Before the session:
1. If you have made changes to the notebooks stored in the repo, make sure you leave them in the correct state - all exercise solutions should be minimised. The cells should be left as all run but the output cleared so the answers can be revealed step-by-step. Additionally, turn off all cell toolbars and tags so you are left witha  clean view. The push your changes. Binder builds whatever is on the master branch so work on a different branch until you're happy with your changes.
2. Make sure you have clicked on the Binder link once after making any changes as the first build is slower than subsequent builds. 

RISE slideshow controls:
* Go to next slide or slide fragment using the space bar and go back using shift+space
* Toggle between slideshow view and notebook view, Alt+r or click on the bar chart icon on the menu bar
* To run a code block, click in the cell and use shift+enter

Before presenting each notebooks, run all cells, then clear cell output.

## Participant instructions
What participants need to do before attending...

## Running Jupyter notebook locally
To run locally, follow [instructions](https://docs.anaconda.com/anaconda/install/) for downloading Anaconda for your operating system and use either the Anaconda Navigator GUI or Anaconda Prompt CLI.

Install extensionsconfig viewer using `conda install -c conda-forge jupyter_contrib_nbextensions` in Anaconda Prompt. You can then browse an enable extensions using the 'Nbextensions' tab or at localhost:8889/nbextensions.

Install RISE (for presenting slides): `conda install rise`

When we can use exercise extension with Binder, install rubberband and exercise extension. 

## Running through Google Colab
This will be a backup should Binder be down. There will be a Google Colab version of the notebooks and a link for participants, plus instructions for the facilitator...
