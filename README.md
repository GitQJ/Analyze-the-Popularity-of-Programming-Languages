# Analyze-the-Popularity-of-Programming-Languages
Analyzed the popularity of programming languages over time based on Stack Overflow data.

## Programming Language Popularity: Stack Overflow Question Trends 2008-2020 | R, dplyr, ggplot2

Used R and dplyr to explore which programming languages draw the most questions on Stack Overflow, how big R's share is and which tags led between 2015 and 2020.

## CONTEXT
Stack Overflow tags each question by technology, so question counts are a useful proxy for what developers are working on. The goal was to help someone decide where to focus their learning by looking at relative popularity over time.

# MY ROLE
I wrote the data manipulation and analysis in R.

# WHAT I DID
• Loaded a tag-by-year dataset (2008-2020) with the number of questions per tag and the yearly total
• Calculated R's share of all questions in 2020 as a percentage using filter and mutate, and saved a five-column results table
• Ranked tags by total questions from 2015 to 2020 with filter, group_by, summarize and arrange, and extracted the top five

# RESULTS
• R accounted for 0.02% of questions in 2020 (1089 of 5452545)
• Top five tags from 2015 to 2020: javascript, python, java, android, c#
• R has a consistent share of questions below 1% over time (from 2008 to 2020) while python witnessed the most dramatic increase (from 1.2% in 2008 to 4.7% in 2020)

# TECH STACK
R, dplyr, readr, ggplot2 (tidyverse)
