R Markdown Output Test
================
Jonah Hamilton
2022-09-26

### First New Markdown Section

This is the first markdown section that will be added, bellow is a new
simple code block

``` r
#count to 3
nums <- c(1,2,3)

for (num in nums){
  print(num)
}
```

    ## [1] 1
    ## [1] 2
    ## [1] 3

### Second New Markdown Section

This is the second new markdown section that will be added

``` r
#simmple math

print(100/2)
```

    ## [1] 50

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document. You can embed an R code chunk like this:

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](521_lab4_RMarkdown_output_test_version-2_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
