Stat 523
--------

### Assignment 1: Data Structures and Subsetting

#### Explain your code where appropriate.
#### Doug Raffle (dcraffle@mix.wvu.edu)

1. Create vectors of each of the different primitive types. i.e., integer, double, logical, and character. Create matrices by attaching `dim` attributes to those vectors. Look up the help for `dimnames` and attach `dimnames` to these resulting matrices.


```r
# Put your R code here.
```

2. Create a list of length 4 and then add a `dim` attribute to it. What happens?


```r
# Put your R code here.
```

3. Look up the help page for `data.frame` and use the example code to create a small data frame containing numeric variables and factors.


```r
# Put your R code here.
```

4. Use the `seq` function to generate a subscript vector that selects those elements of a vector that have even-numbered subscripts.


```r
# Put your R code here.
```

5. Verify that vectors can have duplicated names and that if a subscript matches a duplicated name, only the first value is returned. What happens with `x[NA]`?


```r
# Put your R code here.
```

6. Use logical subscripts to extract the even-numbered elements of the `letters` vector.


```r
# Put your R code here.
```

7. Let `x` be a vector of length 10 generated by `1:10` and suppose it has a dimension attribute so that it is a matrix with 2 columns and 5 rows. What is the matrix location of the 7th element of `x`? That is, which row and column is it in? Alternatively, which element of `x` is in the second row, first column?


```r
# Put your R code here.
```

8. What does `as.matrix()` do when applied to a data frame with columns of different types?


```r
# Put your R code here.
```

9. Fix each of the following common data frame subsetting errors:

```
mtcars[mtcars$cyl = 4, ]
mtcars[-1:4, ]
mtcars[mtcars$cyl <= 5]
mtcars[mtcars$cyl == 4 | 6, ]
```

10. Consider the linear model: `mod <- lm(mpg ~ wt, data = mtcars)`. Describe the data structure of `mod`, including its componets. Extract the coefficients, residuals, and the residual degrees of freedom. Extract the R squared from the model summary, i.e., from `summary(mod)`.


```r
# Put your R code here.
```
