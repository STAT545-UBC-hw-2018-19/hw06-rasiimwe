                
# STAT-547M Homework 06 Repository of Rebecca Asiimwe 

## Theme: Data wrangling 
[<img align ="right" src="https://github.com/STAT545-UBC-students/hw06-rasiimwe/blob/master/plugins/Screen%20Shot%202018-11-05%20at%207.39.13%20PM.png" width="400" height="250"/>](https://github.com/STAT545-UBC-students/hw06-rasiimwe/blob/master/plugins/Screen%20Shot%202018-11-05%20at%207.39.13%20PM.png)
### Assignment overview 

This assignment covers concepts involved in working with non-numeric (character and factor) and covers the following key areas:
* Writing R functions 
* Working with [regular expressions](https://www.rstudio.com/wp-content/uploads/2016/09/RegExCheatsheet.pdf) and character data
> Regular expressions are a concise and flexible tool for describing patterns in strings and are heavily used for string matching / replacing. In R, many string functions in base R as well as in stringr package 
Example usage 

```r
courses <-  c("STAT545, STAT547M, STAT540 are awesome courses")
str_detect(courses, "BIOF501")
#[1] FALSE
```


* Working with purrr, list-columns, nested data frames
> Purrr is a relatively new package that works with magrittr to allow us express complex operations by combining simple pieces in a standard way. It enhances R’s functional programming (FP) toolkit by providing a complete and consistent set of tools for working with functions and vectors. map()functions are good example of functional programming which allow for replacement of  many for loops with code that is both more succinct and easier to read - examples will be shown herein. 


### For this assignment, please visit the following files :point_down::

|   **Homework Files**   | **Description** |
|----------------|------------|
|[Link to homework6](http://stat545.com/Classroom/assignments/hw06/hw06.html)|This file contains homework 6 tasks and their descriptions|
|[README.md](https://github.com/STAT545-UBC-students/hw05-rasiimwe/blob/master/README.md)|This readme.md file provides an overview of the ghist of this repo and provides useful pointers to key files in my homework-5 repo. Herein, are also links to past files that provide an introduction to data exploration and analysis |
|**[Link to homework-06](https://github.com/STAT545-UBC-students/hw06-rasiimwe/blob/master/hw06-rasiimwe.md)**|This file contains |

