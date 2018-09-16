# Mastering Machine Learning with Python in Six Steps

This repository accompanies [*Mastering Machine Learning with Python in Six Steps*](http://www.apress.com/9781484228654) by Manohar Swamynathan (Apress, 2017).

Due to a valuable work of the author, this repository is a good starting point for anyone interested in Machine Learning, and by taking advantage of IPython, it provides an interactive way to learn Machine Learning basics. Thus, I forked the repository and made some changes to make it a standalone learning resource for everyone.

The main repository is coded in Python 2.7, so I ported it to Python 3 and made proper changes to the code in order to be compatible with the latest version of the required packages. The IPython notebooks are now sorted and easy-to-follow.

You can now start self-studying just by browsing the notebooks on GitHub, but downloading or cloning the repository to your machine provides the opportunity for you to modify the codes in Jupyter and investigate the new results.

## Content

The repository contains six chapters:

- Chapter 1: Getting Started in Python
- Chapter 2: Introduction to Base Libraries
- Chapter 3: Fundamentals of Machine Learning
- Chapter 4: Model Diagnosis and Tuning
- Chapter 5: Text Mining and Recommender Systems
- Chapter 6: Deep and Reinforcement Learning

## Requirements

The code is tested in Python 3.5 using the following versions of the required packages:

- imbalanced-learn: 0.3.3
- ipython: 6.4.0
- matplotlib: 2.2.2
- numpy: 1.14.5
- openpyxl: 2.5.4
- pandas: 0.23.3
- pydot: 1.2.4
- scikit-learn: 0.19.2
- scipy: 1.1.0
- seaborn: 0.9.0
- statsmodels: 0.9.0
- xlrd: 1.0.0


## Make It Work

The code should work in a system with the required packages installed, but I recommend to create a separate virtual environment using `virtualenv` or `conda` in which the required packages are installed. Although installing an IPython kernel inside a virtual environment takes some extra steps, it prevents your system-wide Python configurations from being affected by the installation of specific version of a package.

So first, create a virtual environment (e.g. using `$ virtualenv -p python3 [NAME]`), and then, follow the instructions [here](https://anbasile.github.io/programming/2017/06/25/jupyter-venv/) to install jupyter kernel inside your virtual environment. Then run this command to install the required packages:

`$ pip3 install -r requirements.txt`

Now you can browse the notebooks by navigating to the repository directory and running the jupyter kernel inside the virtual environment:

`$ jupyter notebook`
