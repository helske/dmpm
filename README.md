# dmpm
Codes for reproducing the figures in the paper "Estimating Causal Effects from Panel Data with Dynamic Multivariate Panel Models" by Jouni Helske and Santtu Tikka.

See the the Rmarkdown files for details. You need to also install the `dynamite` package which is provided as source (`tar.gz`) format, and which can be installed in R as `install.packages("dynamite_1.4.4.tar.gz")`.

If on a Windows platform you may also need to update your `rstan` and `StanHeaders` installation by running

```
remove.packages(c("rstan", "StanHeaders"))
install.packages("rstan", repos = c("https://mc-stan.org/r-packages/", getOption("repos")))
```
