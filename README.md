# Machine Learning Workshop

This workshop describes an experiment with machine learning to predict the life expectancy for a country.
It's explained in [this blog](https://www.rootstrap.com/blog/a-prediction-experiment-with-machine-learning/).

## Needed libraries

To use work with this project, you need to install:

1. [jupyter notebook](https://jupyter.org/): `pip install jupyter`
2. [pandas dataframes](https://pandas.pydata.org/): `pip install pandas`
3. [scikit learn](https://scikit-learn.org/stable/): `pip install sklearn`
4. [numpy](https://numpy.org/): `pip install numpy`

## Notebooks

Under `notebooks` folder you can see 3 jupyter notebooks:

- `0_intro`: A notebook to understand better pandas dataframes.
- `1_data_cleaning`: A notebook to see the preprocessing of the data. It shows how to load the data and solve common problems in supervised learning such as null values. After that the preprocessed data is stored.
- `2_split_normalize_fit_test`: A notebook that loads the preprocessed data, splits the dataset into train and test, and then train different models and calculates errors to see the performance.
