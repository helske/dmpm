# dmpm
Codes for reproducing the results in the paper "Estimating Causal Effects from Panel Data with Dynamic Multivariate Panel Models" by Jouni Helske and Santtu Tikka.

The `.pdf` files contain the analysis of the examples and the appendices, see the corresponding Rmarkdown (`.Rmd`) files for details. Some of result files are also available without rerunning the analysis (some are too large for Github). These `.rds` files should be loaded to `R` using `readRDS` function.

You need to also install the `dynamite` package which is provided as source (`tar.gz`) format, and which can be installed in R as `install.packages("dynamite_1.4.7.tar.gz")`.

If on a Windows platform you may also need to update your `rstan` and `StanHeaders` installation by running

```
remove.packages(c("rstan", "StanHeaders"))
install.packages("rstan", repos = c("https://mc-stan.org/r-packages/", getOption("repos")))
```

You can also install `cmdstanr` package (alternative way to use `Stan`, used in the partnership example for faster sampling) by running
```
install.packages("cmdstanr", repos = c("https://mc-stan.org/r-packages/", getOption("repos")))
```


