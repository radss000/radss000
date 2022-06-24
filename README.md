# Scraping CCI with Selenium

I - Introduction:

The intention of this documentation is to give the reader a step-by-step guide to write a script to scrape the CCI webpage with python.

 

II - Scope:

 Through this documentation, it shows how to setup our chrome driver to use Selenium, how to install it on your machine, how to locate a specific element on a webpage, and how to extract it thanks to Xpath expressions. In fact, we had to choose between Selenium and BeautifulSoup for the following script, Selenium was a better choice because BeautifulSoup does not support Xpath. In this doc, it will also describe how to print the Data in a CSV file, and all the configurations that you need to do before start coding. the informations we need are:

-The business name

-The attestations/ Activity declarations

-The city and postal code

-The region

-The issuing body

-The function

-The number of the professionnal card

-The adress

-Informations about land guarantee and about the insurance

Then we’ll need to setup the pagination loop and export our scraping to a CSV file.

 

III - Assumptions: 

The user must have some experience with Python and the command line

A command-line-interface to interact with your computer

A text editor to work with plain text files

Version 2.7 of the Python programming language

The pip package manager for Python

 

IV - Definitions, acronyms & abreviations:

Scraping: is a technique where a computer program extracts data from human-readable output coming from another program.

Selenium: Selenium is a powerful tool for controlling web browsers through programs and performing browser automation.

CSV: Comma-separated values (csv file format)

