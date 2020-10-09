# Machine Learning Workshop

This workshop describes an experiment with machine learning to predict the life expectancy for a country.
It's explained in [this blog](https://www.rootstrap.com/blog/a-prediction-experiment-with-machine-learning/).

## Needed libraries

We recommend you to use an isolated python environment to work with this project. There are several tools such as [pipenv](https://docs.pipenv.org/), [virtualenv](https://virtualenv.pypa.io/en/latest/), [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/), etc.

If you have `virtualenv` installed, you can create an environment executing:

```
virtualenv env-ml
```

Then activate it:

```
source env-ml/bin/activate
```

After that make sure to install:

1. [jupyter notebook](https://jupyter.org/): `pip install jupyter`
2. [pandas dataframes](https://pandas.pydata.org/): `pip install pandas`
3. [scikit learn](https://scikit-learn.org/stable/): `pip install sklearn`
4. [numpy](https://numpy.org/): `pip install numpy`
5. [lightgbm](https://pypi.org/project/lightgbm/): `pip install lightgbm`
6. [matplotlib](https://matplotlib.org): `pip install matplotlib`
7. [xgboost](https://pypi.org/project/xgboost/): `pip install xgboost`

If you don't want to install package by package, you can install these packages from the requirements.txt file:

```
pip install -r requirements.txt
```

## Notebooks

Under `notebooks` folder you can see 3 jupyter notebooks:

- `0_intro`: A notebook to understand better pandas dataframes.
- `1_data_cleaning`: A notebook to see the preprocessing of the data. It shows how to load the data and solve common problems in supervised learning such as null values. After that the preprocessed data is stored.
- `2_split_normalize_fit_test`: A notebook that loads the preprocessed data, splits the dataset into train and test, and then train different models and calculates errors to see the performance.

To use these notebooks, go to this folder from the terminal and execute this command:

```
jupyter-notebook
```

After that, your browser will open a new tab that has the jupyter interface to start to work.
