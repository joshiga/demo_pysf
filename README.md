

![pysf](https://github.com/alan-turing-institute/pysf/raw/master/docs/_static/logo.png)

Supervised forecasting of sequential data in Python.

# Key features

* Store and safely manipulate multi-series data in a custom data container.
* Define your own machine learning prediction strategies to operate on multi-series data. Make use of tuning and pipelining objects to build composite prediction strategies.
* Plug in existing single-curve predictors into a framework that adapts them to the multi-series setting. Interface with popular single-series machine learning & forecasting frameworks, such as [scikit-learn](https://scikit-learn.org/stable/), [keras](https://keras.io/) and [statsmodels](https://www.statsmodels.org/stable/index.html). 
* Empirically estimate and compare predictors' generalisation performance using nested resampling schemes, in a statistically sound manner.


# Getting started

## Documentation

* Have a look at the [demonstration Jupyter notebook](examples/Walkthrough.ipynb) for a tutorial.
* API documentation is [hosted on GitHub Pages](https://alan-turing-institute.github.io/pysf).

## Installation

You can install pysf using the [pip](https://pypi.org/project/pysf/) package management system. If you have pip installed, simply run
```
pip install pysf
```
to install the latest release of pysf.

In addition to the package, you will need the following prerequisites to take advantage of pysf's full functionality.

## Prerequisites:

* [pandas](https://pandas.pydata.org/pandas-docs/stable/install.html) 0.20 or higher
* [keras](https://keras.io/#installation) 2.0 or higher
* [scikit-learn](https://scikit-learn.org/stable/install.html)
* [xarray](http://xarray.pydata.org/en/stable/installing.html)
* [scipy](https://scipy.org/install.html)
* [numpy](https://scipy.org/install.html)
* [matplotlib](https://matplotlib.org/users/installing.html)

These are also required, but should be part of your Python distribution:
* abc
* logging

To use keras for deep learning:
* Make sure you [install](https://keras.io/#installation) keras and at least one backend engine. pysf has been tested against TensorFlow and Theano as backends. 
* If using TensorFlow as a backend, you will typically need to install [dask](http://docs.dask.org/en/latest/install.html) 0.15 or higher.

# Credit

## How to cite

Coming soon!

## Copyright and license

Code and documentation copyright 2018 [Ahmed Guecioueur](https://www.ahmedgc.com). Code released under the BSD-3-Clause License. 