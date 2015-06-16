Stat 523
--------
#### Doug Raffle (dcraffle@mix.wvu.edu)

### Assignment 2: Functions

#### Explain your code where appropriate.

1. Create a function to perform a one-way analysis of variance. The input should be a list consisting of (possibly) named components, one for each group. The output should be list containing components for the between SS, the within SS, the between degrees of freedom, and the within degrees of freedom. 

```r
oneway <- function(z) {
# Put your R code here.
}
```

2. Create a function to summarize the output in a one-way ANOVA table, including the F test. The input is the output list in the previous question. The output should be one-way ANOVA table.

```r
oneway.table <- function(x) {
# Put your R code here.
}
```

3. Your functions should be illustrated with the `coagulation` data set. The data consists of blood coagulation times for 24 animals randomly assigned to four different diets.

```r
library(faraway)
data(coagulation)
head(coagulation)
```

```
##   coag diet
## 1   62    A
## 2   60    A
## 3   63    A
## 4   59    A
## 5   63    B
## 6   67    B
```
You should provide brief explanations of the output.
