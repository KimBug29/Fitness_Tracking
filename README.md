# Fitness_Tracking_Project

REQUIREMENTS:


Project Plan for Final Project. 
A project plan defines all work in a project and identifies who will do it.

Project Plan should list the items from the “Features List” you plan to include.

Project Plan could include: 
Project Brief explaining the project and the features you plan to include.

The project is uploaded to your GitHub repository and shows at minimum 5 separate commits.
Must upload via Git Gitignore should be used to keep any secrets/passwords used to access APIs / data sources out of the Github repository.

The project includes a README file that explains the following:
A one-paragraph or longer description of what your project is about.
Relevant packages that need to be installed to run the project.
Which 5+ features you have included from the below lists to meet the requirements.
Any special instructions that are required for the reviewer to run your project. (For example: “run python main.py” from the command line).

Guide to using markdown for README.md files (https://guides.github.com/features/mastering-markdown/).

The project implements a data analysis program that uses pandas, matplotlib, and/or numpy to perform an analysis project of 2 or more pieces of data and implement a rich data visualization in Tableau / Jupyter/Plotly/Matplotlib, or something similar. 

At a minimum, the program should ingest, analyze, and display data. Any needed data cleaning should be clearly documented and repeatable.

Choose at least 1 item from each category on the Features List below and implement them in your project
We recommend you pick a 4th item (or more!) to add, just in case something goes wrong with one of your other items - 3 is only the minimum requirement.


FEATURES

In Data 2, we want to build off the skills you learned in data 1. If you just pulled in data with a csv, try using an API instead or building your own database. If you just visualized data with a couple matplotlib plots, try using different techniques with those plots and fine tuning them with optional arguments. Or, you can make a Tableau dashboard with your prepared data. We want you to be creative with how you think about working with data, outside of the box thinking for the requirements is encouraged. 

We also want this to be a project you’re proud to show off to your employer. You should actually come to some conclusions and have clear descriptions of what your code does and why you’re doing it!

Choose one item from each of the tables below to meet the project requirements. These are somewhat similar in structure and flow to Data 1, but remember, explore the data analysis tools you have further.

Loading data. All of the below features should be somewhat familiar to you at this point. However, the challenge with this project is going to be using two separate sources. In feature 2, you’re going to be challenged to combine the datasets using a merge / join, or make a new dataset with different attributes / columns from the separate sets. 

FEATURE 
DIFFICULTY 
RESOURCES
Read TWO data files (JSON, CSV, Excel, etc.). 
Easy 

Read in TWO text data sources (in any format). For example, email chains or different pages from a book. 
Intermediate 

Read TWO data sets in with an API (or use two different APIs that have data you can combine to answer new questions). 
Intermediate 
A Cool list of Public APIs 
Scrape TWO pieces of data from anywhere on the internet and utilize it in your project. 
Intermediate 
RealPython article on webscraping 
Set up a local database and read data in with SQLite or SQLAlchemy
Hard 
SQLite docs 


Clean and operate on the data while combining them. The heart of data science is data wrangling and cleaning, so these features test that. You may have trouble joining the sets if one has the names of countries in lower case and another has the first letter capitalized. This is where you would need to clean the set in order to merge them. 

FEATURE 
DIFFICULTY
RESOURCES 
Clean your data and perform a pandas merge with your two data sets, then calculate some new values based on the new data set.  
Intermediate 
Merge and join  
Clean your data and perform a SQL join with your data sets using either plain sql or the pandasql Python library.
Intermediate 
SQL Join resource 

pandasql docs 
If you’re using text data, get some information from your separate documents and summarize them in a DataFrame. This isn’t literally a join but accomplishes a similar idea. For example, getting the most frequent word distributions from both documents and then summarizing them in a table. 
Intermediate 
Natural Language Processing 



Visualize / Present your data. In addition to matplotlib and seaborn, you might use Tableau or a pandas pivot table to summarize your data. Imagine you have to present your data to your future manager or in an interview. They should be able to understand what you’re trying to present relatively quickly without having knowledge of  how you programmed it. 


FEATURE 
DIFFICULTY
RESOURCES 
Make 3 matplotlib or seaborn (or another plotting library) visualizations to display your data.
Easy 
Matplotlib basics 

Seaborn basics 
Make a Tableau dashboard to display your data
Intermediate 
Tableau Basics 
Make at least 1 Pandas pivot table and 1 matplotlib/seaborn plot. Pivot tables are a way to summarize your data and present it easily in a way that isn’t just a graph. They can be useful when combined with graphs.
Intermediate 
Pandas pivot tables 
Make a visualization with Bokeh. You can create interactive online visualizations with this, but it is more involved than the other plotting libraries! Very cool though. 
Intermediate / Hard 
Bokeh Gallery 



Best practices: these are concepts or ideas that aren’t just writing code, but enhance your project to a higher tier that will impress employers and help other programmers understand your project. These (probably) won’t affect whether or not your project runs, but can help people understand your goals and intent with the project as well as make it more maintainable. 

FEATURE 
DIFFICULTY
RESOURCES 
Utilize a virtual environment and include instructions in your README on how the user should set one up
Intermediate 
conda virtual environments (note: you can do this with a few different modules, so either venv or virtualenv are fine as well) 
Write 3 unit tests and include instructions on how the user can run them. This will mostly only apply if you’re building custom functions and classes.
Intermediate 
 Pytest docs 
Build a custom data dictionary and include it either in your README or as a separate document. This will only apply if your data set does not already have a data dictionary or if you’re building a custom data set. For an example, see the resources to the right.
Easy 
Data Dictionary example (look under the 6th row on this Louisville Metro Data data set) 
Any other “best practices” your mentor can think of: this is open to interpretation, but if your mentor has a particular idea for a best practice about your specific project, that will meet the requirement for this table.
n/a
Discuss w/ mentor

Interpretation of your data. This requires no code but is VERY important. You’re going to be practicing your written skills here, which is an essential job skill. You can just say “clear communication skills” on a resume, you have to prove it to them. We want few grammatical errors, good markdown formatting where relevant, and explanations of why you’re coding what you’re coding. When you read through the class work-through project HERE you can see what I’m thinking because of how I have things written in the markdown cells above and below the code. Obviously, you will have grammatical and formatting errors, that’s human. But if someone that’s not super familiar with Python or your project picks it up, they should be able to make sense of it relatively quickly. This last box is a “polishing” step to make sure everything is tidy and ready to present to an employer. 

Also, notice that your README uses the file extension .md. This is just markdown, and it’s the same “markup language” used in Jupyter Notebook markdown cells.

REQUIREMENT
DIFFICULTY
RESOURCES
Annotate your code with markdown cells in Jupyter Notebook, write clear code comments, and have a well-written README.md. Tidy up your notebook, and make sure you don’t have any empty cells or incomplete cells that don’t do anything. Make sure it’s all functional before your final github commit.
Intermediate 
A Guide to Good Comments 

A Guide to Markdown 
Annotate your .py files with well-written comments and a clear README.md (only applicable if you’re not using a jupyter notebook).
Intermediate 
A Guide to Good Comments 

A Guide to Markdown