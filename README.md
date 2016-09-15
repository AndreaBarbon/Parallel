# Parallel
A quick introduction to ipyparallel for parallel computing with Jupyter

This tutorial covers:
  - Scattering/gathering data to/from clusters
  - Run computations in parallel and gather the results
  - Importing CSV files
  - Aggregating data using *groupby*
  - Merging two datasets
  - Running liear regressions
  - Adjust returns using the 3-factor model
  - Dropping non-business days

It does **not** explain how to start clusters on your machine. For that, refer to the [ipyparallel docs](http://ipyparallel.readthedocs.io/en/latest/process.html), or simply run

```
ipcluster start -n 8
```

on your terminal.

## Requirements

Jupyter needs to be installed, together with the following modules

  - ipyparallel
  - statsmodels
  - seaborn
  - pandas
  - numpy
