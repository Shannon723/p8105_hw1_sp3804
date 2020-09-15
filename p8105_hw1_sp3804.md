p8105\_hw1\_sp3804
================
Shannon Park (sp3804)
9/15/2020

This is my solution to HW1

## Problem 1

Creat a data frame with the specified elements.

``` r
prob1_df = 
  tibble(
  samp = rnorm(10),
  samp_gt_0 = samp > 0,
  char_vec = c("a","b","c","d","e","f","g","h","i","j"),
  factor_vec = factor(c("low","low","low","mod","mod","mod","high","high","high","high"))
)
```
