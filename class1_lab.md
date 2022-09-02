"# test1" 
{r setup, include=FALSE, tidy=TRUE}
knitr::opts_chunk$set(echo = TRUE,cache=TRUE, 
                      autodep=TRUE, cache.comments=FALSE,
                      message=FALSE, warning=FALSE)
                      {r}
income1<-data.frame("id"=c(1:20),
                          "income_usd"=rnorm(20, mean = 10000, 
                                             sd = 10000/3), 
                          "educ_yr"=rep(12,20))
head(income1)
summary(income1)
```