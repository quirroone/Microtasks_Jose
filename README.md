# Microtasks from the Implementing CHAOSS Metrics with Perceval idea for the Google Summer of Code 2019

The GMD Working group is proposing some metrics
that are computed with information obtained from software development repositories.
One of the goals of the working group is to provide reference implementations of
those metrics, based on the output produced by Perceval. For being able to participate in this project, every interested student should perform at least 3 microtasks in order to show his/her experience with the necessary tools for accomplishing the required tasks in the Google Summer of Code

The easiest way to run the Jupyter Notebooks created for this activity is online with this [My binder link](https://mybinder.org/v2/gh/quirroone/Microtasks_Jose/master) or with the button below

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/quirroone/Microtasks_Jose/master)

# Running the notebooks locally

First, you'll need to download this repository and then open each notebook inside the different microtasks directories.

Tools necessary to run the Notebooks:

The easiest way to run notebooks locally is by installing [Anaconda](https://www.anaconda.com/distribution/), it installs most of the libraries used in these notebooks.

You will also need to install Perceval manually, to do so, run this command from your command line ```pip3 install perceval```

Instructions on how to run a Jupyter Notebook can be found in this [link](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html)

# Microtasks explanation

## Microtask 0
Produce one notebook per data source (git, GitHub/GitLab issues, GitHub pull requests / GitLab merge requests) showing a summary of the contents of that file (number of items in it, and number of different identities in it counting authors/committers for git, submitters for issues and pull/merge requests). This microtask is mandatory, to show that you can retrieve data and produce a notebook showing it. In each notebook, include also the list of repositories retrieved, and the date of retrieval, using data available in the JSON file.

## Microtask 2
Produce a notebook showing (and producing) a list with the activity per quarter: number of new committers, submitters of issues, and submitters of pull/merge requests, number of items (commits, issues, pull/merge requests), number of repositories with new items (all of this per quarter) as a table and as a CSV file. Pandas can be used

## Microtask 3
Produce a notebook with charts showing the distribution of time-to-close for issues already closed, and opened during the last year, for each of the repositories analyzed, and for all of them together. Use Pandas for this, and the Python charting library of your choice (as long as it is a FOSS module).

## Microtask 5
Produce a listing of repositories, as a table and as CSV file, with the number of commits authored, issues opened, and pull/merge requests opened, during the last three months, ordered by the total number (commits plus issues plus pull requests). Pandas can be used

# Who am I
My name is José Alberto Marcial Sánchez and I´m a computer science student at Monterrey Institute of Technology and Higher Education. I'm passionate for technology
