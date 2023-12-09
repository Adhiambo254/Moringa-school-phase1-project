# Phase 1 Project Description
## Project Overview

For this project, you will use exploratory data analysis to generate insights for a business stakeholder.

## Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

## The Data

In the folder zippedData are movie datasets from:

Box Office MojoLinks to an external site.
IMDBLinks to an external site.
Rotten TomatoesLinks to an external site.
TheMovieDBLinks to an external site.
The NumbersLinks to an external site.
Because it was collected from various locations, the different files have different formats. Some are compressed CSV (comma-separated values) or TSV (tab-separated values) files that can be opened using spreadsheet software or pd.read_csv, while the data from IMDB is located in a SQLite database.
It is up to you to decide what data from this to use and how to use it. If you want to make this more challenging, you can scrape websites or make API calls to get additional data. If you are feeling overwhelmed or behind, we recommend you use only the following data files:

im.db.zip
Zipped SQLite database (you will need to unzip then query using SQLite)
movie_basics and movie_ratings tables are most relevant
bom.movie_gross.csv.gz
Compressed CSV file (you can open without expanding the file using pd.read_csv)
Key Points
Your analysis should yield three concrete business recommendations. The ultimate purpose of exploratory analysis is not just to learn about the data, but to help an organization perform better. Explicitly relate your findings to business needs by recommending actions that you think the business (Microsoft) should take.

Communicating about your work well is extremely important. Your ability to provide value to an organization - or to land a job there - is directly reliant on your ability to communicate with them about what you have done and why it is valuable. Create a storyline your audience (the head of Microsoft's new movie studio) can follow by walking them through the steps of your process, highlighting the most important points and skipping over the rest.

Use plenty of visualizations. Visualizations are invaluable for exploring your data and making your findings accessible to a non-technical audience. Spotlight visuals in your presentation, but only ones that relate directly to your recommendations. Simple visuals are usually best (e.g. bar charts and line graphs), and don't forget to format them well (e.g. labels, titles).

## Deliverables

There are three deliverables for this project:

A non-technical presentation
A Jupyter Notebook
A GitHub repository
Non-Technical Presentation
The non-technical presentation is a slide deck presenting your analysis to business stakeholders.

Non-technical does not mean that you should avoid mentioning the technologies or techniques that you used, it means that you should explain any mentions of these technologies and avoid assuming that your audience is already familiar with them.
Business stakeholders means that the audience for your presentation is Microsoft, not the class or teacher. Do not assume that they are already familiar with the specific business problem, but also do not explain to them what Microsoft is.
The presentation describes the project goals, data, methods, and results. It must include at least three visualizations which correspond to three business recommendations.

We recommend that you follow this structure, although the slide titles should be specific to your project:

### Beginning
Overview
Business Understanding
### Middle
Data Understanding
Data Analysis
### End
Recommendations
Next Steps
Thank You
This slide should include a prompt for questions as well as your contact information (name and LinkedIn profile)
You will give a live presentation of your slides and submit them in PDF format on Canvas. The slides should also be present in the GitHub repository you submit with a file name of presentation.pdf.

## The graded elements of the presentation are:

Presentation Content
Slide Style
Presentation Delivery and Answers to Questions
See the Grading section for further explanation of these elements.

For further reading on creating professional presentations, check out:

Presentation ContentLinks to an external site.
Slide StyleLinks to an external site.
Jupyter Notebook
The Jupyter Notebook is a notebook that uses Python and Markdown to present your analysis to a data science audience.

Python and Markdown means that you need to construct an integrated .ipynb file with Markdown (headings, paragraphs, links, lists, etc.) and Python code to create a well-organized, skim-able document.
The notebook kernel should be restarted and all cells run before submission, to ensure that all code is runnable in order.
Markdown should be used to frame the project with a clear introduction and conclusion, as well as introducing each of the required elements.
Data science audience means that you can assume basic data science proficiency in the person reading your notebook. This differs from the non-technical presentation.
Along with the presentation, the notebook also describes the project goals, data, methods, and results. It must include at least three visualizations which correspond to three business recommendations.

You will submit the notebook in PDF format on Canvas as well as in .ipynb format in your GitHub repository.

## The graded elements for the Jupyter Notebook are:

Business Understanding
Data Understanding
Data Preparation
Data Analysis
Visualization
Code Quality
See the Grading section for further explanation of these elements.

## GitHub Repository
The GitHub repository is the cloud-hosted directory containing all of your project files as well as their version history.

This repository link will be the project link that you include on your resume, LinkedIn, etc. for prospective employers to view your work. Note that we typically recommend that 3 links are highlighted (out of 5 projects) so don't stress too much about getting this one to be perfect! There will also be time after graduation for cosmetic touch-ups.

### A professional GitHub repository has:

README.md
A file called README.md at the root of the repository directory, written in Markdown; this is what is rendered when someone visits the link to your repository in the browser
This file contains these sections:
Overview
Business Understanding
Include stakeholder and key business questions
Data Understanding and Analysis
Source of data
Description of data
Three visualizations (the same visualizations presented in the slides and notebook)
Conclusion
Summary of conclusions including three relevant findings
Commit history
Progression of updates throughout the project time period, not just immediately before the deadline
Clear commit messages
Commits from all team members (if a group project)
Organization
Clear folder structure
Clear names of files and folders
Easily-located notebook and presentation linked in the README
Notebook(s)
Clearly-indicated final notebook that runs without errors
Exploratory/working notebooks (can contain errors, redundant code, etc.) from all team members (if a group project)
.gitignore
A file called .gitignore at the root of the repository directory instructs Git to ignore large, unnecessary, or private files
Because it starts with a ., you will need to type ls -a in the terminal in order to see that it is there
GitHub maintains a Python .gitignoreLinks to an external site. that may be a useful starting point for your version of this file
To tell Git to ignore more files, just add a new line to .gitignore for each new file name
Consider adding .DS_Store if you are using a Mac computer, as well as project-specific file names
If you are running into an error message because you forgot to add something to .gitignore and it is too large to be pushed to GitHub this blog postLinks to an external site.(friend link) should help you address this
You wil submit a link to the GitHub repository on Canvas.