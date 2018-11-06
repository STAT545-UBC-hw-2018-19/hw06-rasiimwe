                
# STAT-547M Homework 06 Repository of Rebecca Asiimwe 

## Theme: Data wrangling 
[<img align ="right" src="https://github.com/STAT545-UBC-students/hw06-rasiimwe/blob/master/plugins/Screen%20Shot%202018-11-05%20at%207.39.13%20PM.png" width="400" height="250"/>](https://github.com/STAT545-UBC-students/hw06-rasiimwe/blob/master/plugins/Screen%20Shot%202018-11-05%20at%207.39.13%20PM.png)
### Assignment overview 

This assignment covers concepts involved in working with non-numeric (character and factor) and covers the following key areas:
* Writing R functions 
> In R and programming in general, functions are a powerful tool and are used to incorporate sets of instructions that we may need to to use repeatedly. They can also be used when instructions are complex and are better self-contained in a sub program and called when needed. Simply put - a function is a piece of code written to carry out a specified task; it can or can not accept arguments or parameters and it can or can not return one or more values. 
Functions are R objects of class "function"; they are first class objects, which means that they can be treated much like any other R object. They can also be passed as arguments to other functions, they can be nested, so that you can define a function inside of another function
The return value of a function is the last expression in the function body to be evaluated. 

Functions are created using the function() directive using the genetal syntax below:
```r 
f <- function(<arguments>) {
        ## Do something interesting
}
```

* Working with [regular expressions](https://www.rstudio.com/wp-content/uploads/2016/09/RegExCheatsheet.pdf) and character data
> Regular expressions are a concise and flexible tool for describing patterns in strings and are heavily used for string matching / replacing. In R, many string functions in base R as well as in stringr package 
Example usage 

[<img align ="center" src="https://github.com/STAT545-UBC-students/hw06-rasiimwe/blob/master/plugins/Screen%20Shot%202018-11-05%20at%208.17.44%20PM.png" width="400" height="150"/>](https://www.rstudio.com/wp-content/uploads/2016/09/RegExCheatsheet.pdf)
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

