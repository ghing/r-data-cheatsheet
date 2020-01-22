# R data cheatsheet

These are notebooks that describe tasks that I use when working with data for journalism in R but don't do often enough to remember off the top of my head.

These are mostly recipes for things that took me a bit of time to Google or for which I didn't know the right language.

## Fundamentals

- [Everything is a vector](notebooks/everything_is_a_vector.Rmd)

## Inspecting data

### Listing data variables and types

Use `str`:

```
str(mydata)
```

Source: [Quick-R: Viewing Data](https://support.rstudio.com/hc/en-us/articles/200549016-Customizing-RStudio)

## Finding data

- [Search census variables](notebooks/search_census_variables.Rmd)

## Importing data

- [Copying data from the system clipboard](notebooks/copy_from_clipboard.Rmd)

## Selecting and filtering data

- [Get dataframe value from a vector of variable names](notebooks/value_from_vector_of_variable_names.Rmd)

## Transforming data

- [Group by part of a date variable](notebooks/group_by_month_or_year_from_date.Rmd)

## Testing

- [Run testthat tests in a single file](notebooks/run_tests_in_a_single_file.Rmd)at e

## RStudio

I do most of my work with R using RStudio. These are some helpful tips I've learned about working in that environment.

### Vim keybindings

You can change the keyboard shortcuts in RStudio to mimic that of the vim editor (and a few other editors).

Source: [Customizing RStudio](https://support.rstudio.com/hc/en-us/articles/200549016-Customizing-RStudio).

## Other resources

- [How Do I? …](https://smach.github.io/R4JournalismBook/HowDoI.html): Sharon Machlis has made a searchable table of tasks in R to accompany her book [Practical R for Mass Communication and Journalism](https://www.crcpress.com/Practical-R-for-Mass-Communication-and-Journalism/Machlis/p/book/9781138726918).
- [RStudio Cheat Sheets](https://rstudio.com/resources/cheatsheets/): RStudio has a number of PDF cheatsheets about a wide range of topics and libraries including visualization using ggplot2 and data transformation using dplyr. 
