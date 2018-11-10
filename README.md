                
# STAT-547M Homework 06 Repository of Rebecca Asiimwe 

## Theme: Data wrangling 
[<img align ="right" src="https://github.com/STAT545-UBC-students/hw06-rasiimwe/blob/master/plugins/Screen%20Shot%202018-11-05%20at%207.39.13%20PM.png" width="450" height="250"/>](https://github.com/STAT545-UBC-students/hw06-rasiimwe/blob/master/plugins/Screen%20Shot%202018-11-05%20at%207.39.13%20PM.png)
### Assignment overview 

This assignment covers concepts involved in working with non-numeric (character and factor) and covers the following key areas:
#### 1. Writing R functions 
In R and programming in general, functions are a powerful tool and are used to incorporate sets of instructions that we may need to use repeatedly. They can also be used when instructions are complex and are better self-contained in a sub program and called when needed. Simply put - a function is a piece of code written to carry out a specified task. To note is that functions are R objects of class "function"; they are first class objects, which means that they can be treated much like any other R object. They can also be passed as arguments to other functions, they can be nested to allow for the definition of a function inside another function. The return value of a function is the last expression in the function body to be evaluated. 

Functions are created using the function() directive using the genetal syntax below:
```r 
f <- function(<arguments>) {
        ## Do something interesting
}
```

#### 2. Working with [regular expressions](https://www.rstudio.com/wp-content/uploads/2016/09/RegExCheatsheet.pdf) and character data
Regular expressions are a concise and flexible tool for describing patterns in strings and are heavily used for string matching / replacing. Many string functions are available in base R as well as in the `stringr package`.

**Example usage** 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[<img align ="center" src="https://github.com/STAT545-UBC-students/hw06-rasiimwe/blob/master/plugins/Screen%20Shot%202018-11-05%20at%208.17.44%20PM.png" width="410" height="140"/>](https://www.rstudio.com/wp-content/uploads/2016/09/RegExCheatsheet.pdf)
```r
courses <-  c("STAT545, STAT547M, STAT540 are awesome courses")
str_detect(courses, "BIOF501")
#[1] FALSE
```


#### 3. Working with purrr, list-columns, nested data frames
Purrr is a relatively new R package that works with magrittr to allow us express complex operations by combining simple code  pieces in a standard way. It enhances R’s functional programming (FP) toolkit by providing a complete and consistent set of tools for working with functions and vectors. `map()`functions are a good example of functional programming which allow for replacement of many for-loops with code that is both more succinct and easier to read - examples will be shown herein. 


### Repo Navigation:- Please visit the following files :point_down::

|   **Homework Files**   | **Description** |
|----------------|------------|
|[Link to homework6](http://stat545.com/Classroom/assignments/hw06/hw06.html)|This file contains homework 6 tasks and their descriptions|
|[README.md](https://github.com/STAT545-UBC-students/hw06-rasiimwe/blob/master/README.md)|This readme.md file provides an overview of the ghist of this repo and provides useful pointers to key files in my homework-6 repo. Herein, are also links to past files that provide an introduction to data exploration and analysis |
|**[Link to homework-06](https://rasiimwe.github.io/html_render/hw06-rasiimwe.html)**|This is the key home work file that contains and exploration and presentation of concepts on writing R functions, working with and character data and working with purrr, list-columns, nested data frames|
|[hw06-rasiimwe.rmd](https://github.com/STAT545-UBC-students/hw06-rasiimwe/blob/master/hw06-rasiimwe.rmd)|This is the source rmd file that generates my html rendered file|

