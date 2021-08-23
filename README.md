# Module_7_Challenge

# Fintech ETF Performance Analysis

---

## Introduction:

For this project, I will build a financial database and web application by using SQL, Python, and the Voilà library to analyze the performance of a hypothetical fintech ETF (exchange-traded fund).

I have created a Jupyter notebook with my analysis of the ETF. The analysis includes styled and formatted interactive visualizations.

---

## Technologies

This project leverages python 3.7 with the following modules:

* [numpy](https://numpy.org/doc/stable/index.html) - For scientific computing.

* [sqlalchemy](https://www.sqlalchemy.org) - For easing the communication between the Python program and the database.

* [Voilà](https://voila.readthedocs.io/en/stable/index.html) - For converting a Jupyter notebook into a live webpage.

* [hvplot](https://hvplot.holoviz.org) - For plotting in various formats working with a wide array of datatypes in the PyData ecosystem.

* [pandas](https://github.com/pandas-dev/pandas) - For reading data into a DataFrame and analyzing data via statistics and plots.

* [matplotlib](https://matplotlib.org/stable/users/index.html) - For embedding plots in the application.

---

## Installation Guide

Before running the application first install the following dependencies:

```python
  conda install -c conda-forge numpy
  conda install -c conda-forge voila
  pip install SQLAlchemy
  pip install pandas
  pip install hvplot
  pip install mkdocs
```

To install PyViz and its dependencies in your Conda dev environment, complete the following steps:

```python
  conda install -c pyviz hvplot
  conda install -c conda-forge nodejs=12
```

For your PyViz plots to render in JupyterLab, you also need to install a specific version of JupyterLab, as well as the JupyterLab extensions. To install the required JupyterLab version and the extensions for PyViz, run the following commands in the terminal:

```python
  conda install -c conda-forge jupyterlab=2
  jupyter labextension install @pyviz/jupyterlab_pyviz --no-build
```

Now that you’ve installed the extensions in your Conda dev environment, you need to apply, or build, them to the JupyterLab software. To do so, run the following code:

```python
  jupyter lab build
```

---

## Usage

To use the Fintech ETF Performance Analysis application:

Clone the Module_7_Challenge repository from GitHub:

'git clone https://github.com/jpweldon/Module_7_Challenge.git'

Run the etf_analyzer.ipynb program.

Examine the analysis of the Fintech ETF including the styled and formatted interactive visualizations.

---

## Contributors

John P Weldon

Email: johnpweldon01@gmail.com

[LinkedIn:] (www.linkedin.com/in/john-weldon-333b0695)

---

## License

MIT

---