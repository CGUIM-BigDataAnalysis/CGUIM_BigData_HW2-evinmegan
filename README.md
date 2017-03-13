長庚大學 大數據分析方法 作業二
================

數值變數運算
------------

``` r
#這是R Code Chunk
num1<-3561
num2<-5815
num1+num2
```

    ## [1] 9376

``` r
num1-num2
```

    ## [1] -2254

``` r
num1*num2
```

    ## [1] 20707215

``` r
round(num1/num2, digits = 2)
```

    ## [1] 0.61

檢查總覽資料
------------

``` r
#這是R Code Chunk
str(iris)
```

    ## 'data.frame':    150 obs. of  5 variables:
    ##  $ Sepal.Length: num  5.1 4.9 4.7 4.6 5 5.4 4.6 5 4.4 4.9 ...
    ##  $ Sepal.Width : num  3.5 3 3.2 3.1 3.6 3.9 3.4 3.4 2.9 3.1 ...
    ##  $ Petal.Length: num  1.4 1.4 1.3 1.5 1.4 1.7 1.4 1.5 1.4 1.5 ...
    ##  $ Petal.Width : num  0.2 0.2 0.2 0.2 0.2 0.4 0.3 0.2 0.2 0.1 ...
    ##  $ Species     : Factor w/ 3 levels "setosa","versicolor",..: 1 1 1 1 1 1 1 1 1 1 ...

輸出系統現在日期
----------------

``` r
#這是R Code Chunk
Sys.Date()
```

    ## [1] "2017-03-13"

字串比大小
----------

``` r
#這是R Code Chunk
"A">"a"
```

    ## [1] FALSE

``` r
"b">"A"
```

    ## [1] TRUE

運作環境資訊擷取
----------------

``` r
#這是R Code Chunk
sessionInfo()
```

    ## R version 3.3.2 (2016-10-31)
    ## Platform: x86_64-apple-darwin13.4.0 (64-bit)
    ## Running under: macOS Sierra 10.12.3
    ## 
    ## locale:
    ## [1] C
    ## 
    ## attached base packages:
    ## [1] stats     graphics  grDevices utils     datasets  methods   base     
    ## 
    ## loaded via a namespace (and not attached):
    ##  [1] backports_1.0.5 magrittr_1.5    rprojroot_1.2   tools_3.3.2    
    ##  [5] htmltools_0.3.5 yaml_2.1.14     Rcpp_0.12.9     stringi_1.1.2  
    ##  [9] rmarkdown_1.3   knitr_1.15.1    stringr_1.2.0   digest_0.6.12  
    ## [13] evaluate_0.10
