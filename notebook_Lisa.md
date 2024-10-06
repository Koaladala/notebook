---
editor: visual
gfm:
  code-fold: false
  execute:
    echo: true
    output: false
  keep-md: true
title: Notebook Lisa
toc-title: Table of contents
---

## Created by Lisa Braunhofer *(3rd October 2024)*

This notebook was created to get familiar with the Quarto and RStudio environment.

Below, I will try out some codes.

### Print text code

I find *if-else statements* really fun, so I made this easy one. To create an if-else statement, I assigned values to two variables and added a condition to the if statement. Since b is in fact higher than 4, R will print the if statement and ignore the else statement.

<div>

``` r
a <- 4

b <- 11

if (b > a) {

print("Hello World! Learning R takes time but is cool.")

} else {

print("Error.")

}
```

<div>

```         
[1] "Hello World! Learning R takes time but is cool."
```

</div>

</div>

### Calculating with code

I assigned values to four variables. Then, I assigned two calculations to two new variables. Afterwards, I wanted to see whether the results were the same, which is why I *compared* them, using ==. R should render "FALSE", as the results are not the same.

<div>

``` r
c <- 5

d <- 3

e <- 1

f <- 5

g <- sum(c, d, e, f)

h <- c*d*e*f

g
```

<div>

```         
[1] 14
```

</div>

``` r
h
```

<div>

```         
[1] 75
```

</div>

``` r
g == h
```

<div>

```         
[1] FALSE
```

</div>

</div>

So far, so good!
