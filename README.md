# Cookiecutter Data Science

_A logical, reasonably standardized, but flexible project structure for doing and sharing data science work._


### Requirements to use the cookiecutter template:
-----------
 - Python 2.7 or 3.5
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
$ pip install cookiecutter
```

or

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```


### To start a new project, run:
------------

    cookiecutter https://github.com/Quantyca/refarch-ateam-cookiecutter-base


### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```

├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- Project documentation
│
├── metrics            <- All tracking info related to a specific experiment (i.e. lossfunction value and hyper-parameters used)
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is ...
│
├── pipeines           <- Dvc pipelines 
│
├── src                <- Source code for use in this project.
│
│
├── LICENSE
├── README.md          <- The top-level README for developers using this project.
├── environment.yml    <- The requirements file for reproducing the analysis environment, e.g.
                          generated with `conda env export > environment.yml`. Include the following libs: 
                          jupyter numpy=1.15.2 pandas=0.23.4 matplotlib=2.2.3 seaborn=0.9.0 
                          scikit-learn=0.20.0, xgboost=0.80, pytorch, fastai

```


