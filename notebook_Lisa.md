---
editor: visual
title: Notebook Lisa
toc-title: Table of contents
---

## Created by Lisa Braunhofer *(3rd October 2024)*

This notebook was created to get familiar with the Quarto and RStudio
environment.

Below, I will try out some codes.

### Print text code

I find *if-else statements* really fun, so I made this easy one. To
create an if-else statement, I assigned values to two variables and
added a condition to the if statement. Since b is in fact higher than 4,
R will print the if statement and ignore the else statement.

:::: cell
``` {.r .cell-code}
a <- 4

b <- 11

if (b > a) {

print("Hello World! Learning R takes time but is cool.")

} else {

print("Error.")

}
```

::: {.cell-output .cell-output-stdout}
    [1] "Hello World! Learning R takes time but is cool."
:::
::::

### Calculating with code

I assigned values to four variables. Then, I assigned two calculations
to two new variables. Afterwards, I wanted to see whether the results
were the same, which is why I *compared* them, using ==. R should render
"FALSE", as the results are not the same.

:::::: cell
``` {.r .cell-code}
c <- 5

d <- 3

e <- 1

f <- 5

g <- sum(c, d, e, f)

h <- c*d*e*f

g
```

::: {.cell-output .cell-output-stdout}
    [1] 14
:::

``` {.r .cell-code}
h
```

::: {.cell-output .cell-output-stdout}
    [1] 75
:::

``` {.r .cell-code}
g == h
```

::: {.cell-output .cell-output-stdout}
    [1] FALSE
:::
::::::

So far, so good!
