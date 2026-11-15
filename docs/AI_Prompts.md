# AI Prompts and Usage

## Purpose 

This file includes how AI tools were used during the Yelp New Orleans Restaurant Project.
AI was used to help understand R functions, discover errors, improve organization, and explain analytical methods.
I used ChatGPT for this project.

All AI-generated suggestes were reviewed and tested before being incorporated into the final project.

## Prompt 1: Understanding Yelp Data and Imports

**Prompt:** 
How do I import a large Yelp JSON dataset into R?

**Response + How it was used:**
AI helped explain how to use commands like 'jsonlite::stream_in()' and 'dplyr::filter() to import JSON files.

# Prompt 2: Restaurant Category Analysis

**Prompt:**
How can I separate the restaurant categories in R, find how frequently it shows up, and identify restaurants in these categories?

**Response + How it was used:**
It explained commands like 'separate_rows()', 'str_trim()', and 'count()' in order to organize categories.

# Prompt 3: Processing Yelp Reviews

**Prompt:**
How can I use the R package 'sf' to assign restaurant locations to New Orleans neighborhood statistical areas and Census tracts using spatial join?

**Response + How it was used:**
AI helped explain spatial joins, coordinate reference systems, and how to summarize restaurant counts by geographic area.

## Prompt 4: Debugging and Code Improvements

**Prompt:**
Explain this error to me: 
  Error in file(business_file, open = "r") : cannot open the connection
  In addition: 
  Warning message:
  In file(business_file, open = "r") :
    cannot open file 'data/raw/yelp_academic_dataset_business.json': No such file or directory

**How the response was used:**
AI explained that the file I needed was not in the folder and possibly saved somewhere else.
It showed me how to fix it by how to check if it existed, then to update the path, or move the file to the necessary spot.


## Limitations

AI-generated code and explanations were not automatically assumed to be correct. 
I did my best to understand, then apply the code and commands provided, or modify them when necessary. 
A limitation of this is that ChatGPT required a lot of background information before providing me with the proper responses I was looking for.
