# Scraping EDGAR Short Python Course

This course was designed off the top of my head for a class of 3 students that met once a week for three weeks (i.e. all design decisions were made accordingly).
Each week's meeting was 45 minutes, mostly explaning the intent of the next week's lesson.
Students were expected to go through the notebook on their own time, get familiar with the concepts, and execute the 'homework' on their own.

# Lessons

## 1: [Installation](notebooks/1_Installation.ipynb)

Walk through installing Python on your computer, with optional software/packages to install.

Outline:
  1. Installing python
  1. Installing git
  1. Installing VSCode
  1. Installing pyEDGAR


## 2: [Python](notebooks/2_Python.ipynb)

Walk through the basics of Python, and end with extracting simple count data from text with regular expressions.

Outline:
  1. Syntax basics (strings, variables, lists, dicts, etc.)
  1. Program control logic (if statements, for loops, etc.)
  1. Functions
  1. Reading files
  1. Regular expressions
  1. Homework on analysing text data ([answers](notebooks/2a_Python-answers.ipynb))
  
  

## 3: [Scraping](notebooks/3_Scraping.ipynb)

Introduce EDGAR, and the library to download/analyze EDGAR filings ([pyEDGAR](https://github.com/gaulinmp/pyedgar)).
View the data, introduce the basics of HTML ([BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)), typical filing format, and extracting data from the [DOM](https://www.w3schools.com/js/js_htmldom.asp).

Outline:
  1. EDGAR (and pyEDGAR to interact with it)
  1. Filing formats
     1. Plaintext
     1. HTML
  1. Homework on analysing HTML documents ([answers](notebooks/3a_Scraping-answers.ipynb))
  

## 3: [Bulk Scraping](notebooks/4_Bulk_Scraping.ipynb)

Introduce [DataFrames](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html), and looping over them.
Provide simple scraping loop structure for convenience.
Close with example of parallelization using [ipyparallel](https://ipyparallel.readthedocs.io/en/latest/direct.html).

Outline:
  1. DataFrames
  1. Looping thereover
  1. Scraping loop framework
  1. Result aggregation and saving to disk
  1. Parallelization example
