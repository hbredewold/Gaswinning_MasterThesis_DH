This is the repository for the Thesis project 'Uncovering bots in the Groningen #gaswinning debate' by Harm Bredewold. This Thesis was written to complete the Masters Program Digital Humanities at the University of Groningen.

** Typically, data needs to be uploaded to GitHub so that supervisors or professors can run the notebooks. However, due to GDPR privacy laws governing Twitter data, the actual data cannot be shared. Instead, notebooks and their outputs have been uploaded to demonstrate functionality and allow for code verification. Of course, there is no personal data shown in any of the output, only showing metadata or derived data such as visualisations **

This repository consists of 5 different Jupyter Notebooks containing Python code: 

| Notebook name | Notebook content |
| --------------- | --------------- |
| BOT_IDENTITY_ANALYSIS_notebook.ipynb   | This notebook contains the code that has been used to filter the most-active bot descriptions and generate the top 50 most frequent words used by bots in their description  |
| BOT_IMPORTING_notebook.ipynb  | This notebook contains the code that has been used to extract the bots with a score higher than 0.5 from the original Botometer .txt a while also filtering out accounts manually identified as non-bot  |
| JSON_IMPORTING_notebook.ipynb | This notebooks contains the code that shows how the twitter data has been extracted from the 10 different JSON files and combined into one .feather file   |
| SORTING_AND_EXPLORATION_notebook.ipynb   | This notebooks contains the code that shows how the Twitter data has been explored, sorted, cleaned and visualised.   |
| TOPIC_MODELING_notebook.ipynb  | This notebook contains the code that shows how topic modeling has been done, what steps have been taken, what parameters have been used and how the different topic visualisatiions have been created.    |

Furthermore, this repository contains all figures and tables that do not contain personal data, and are in the thesis. These can be found in the folder Figures and tables. 
