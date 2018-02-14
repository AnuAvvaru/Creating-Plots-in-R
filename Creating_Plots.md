R Markdown
----------

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document. You can embed an R code chunk like this:

    summary(cars)

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

Including Plots
---------------

You can also embed plots, for example:

![](.pressure-1.png)

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.

Decalaration for Histogram
==========================

    product_sales <- c(10,30,30,40,50,50,50,60,60,60,60,70,80,80,90,100,100,100,110,110,130,130,190)
    product_sales

    ##  [1]  10  30  30  40  50  50  50  60  60  60  60  70  80  80  90 100 100
    ## [18] 100 110 110 130 130 190

Creating Histogram plot
=======================

    hist(product_sales,breaks=10)

![](.unnamed-chunk-2-1.png)

Creating Boxplot
================

    boxplot(product_sales)

![](.unnamed-chunk-3-1.png)

Creating Scatter plot
=====================

    scatter.smooth(product_sales)

![](.unnamed-chunk-4-1.png)
