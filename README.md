# ZetaMac-Tracker
A script that scrapes your score from [ZetaMac](https://arithmetic.zetamac.com/) creates a plot with regression line and moving average.
For fun, regression is computed form first principles - rather than from a library direcrlty - using least sum of squares, that is we want to minimize the function:

```math
S(\alpha, \beta) = \sum_{i=1}^{n} \left( y_i -\left( \alpha + \beta x_i \right) \right)^2 
```

Uses: NumPy, Pandas, Pyplot

