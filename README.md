# Substitution_Analysis

This is a project I originally started in March 2022 with the goal of writing a blog post for my blog www.ds-fussball.de that I did not get around to actually write, while familiarizing myself with **web scraping** and the use of **groupby**.

Topic of the blog post would have been an analysis of the substitution habits of Bundesliga coaches. The data source is the match reporst on www.kicker.de, especially the timetable containing the major events of a match.

## File scrape.ipynb ##

Running this notebook creates two csv files for each match in the chosen match day range, one containing only the substitutions, the other every major event (goals, red and yellow cards, substitutions). In the end it combines those files into two, containing all subs/events in the match day range.

## File subs.ipynb ##

This notebook currently (as of February 2023) creates a dataframe, containing several substitution statistics calculated out of the event data created by the **scrape.ipynb** file, and two plots visualizing a few of those statistics.
