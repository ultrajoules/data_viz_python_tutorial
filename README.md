# Data Visualization in Python
Take data and turn it into something colorful, graphical and meaningful :)

An introduction to basic data visualizations using Pandas, Matplotlib, Seaborn, and Plotnine all combined in a single Jupyter Notebook.

## Intro
Data visualization allows data scientists to graphically represent data to extract and understand trends, outliers, patterns and further insights in the data. 

Python has many **many** graphing libraries with different features and it can be daunting to know which library to use.  This intro tutorial will focus on a few popular plotting libraries:
* **Pandas** - built on Matplotlib and easy to use with Pandas dataframes
* **Matplotlib** - massive library with lots of flexibility (stackoverflow will be your friend!)
* **Seaborn** - statistical visualization with default themes and beautiful styles
* **Plotnine** - based on gglot2 for all my R peeps!


This tutorial compares Matplotlib, Pandas, Seaborn and Plotnine for the following visualizations:
* Scatter Plots 
* Line Charts 
* Histograms 
* Bar Charts 
* Box Plots 
* Pie Charts 
* Heatmaps 
* Faceting
* Pairplots


For interactive plots and possibly a feature tutorial
* Plotly
* D3
* Bokeh

## Setup
* Clone the repo!
* Run the 1st block of code in Data_Viz_Tutorial to make sure all pacakges are installed!  

You can pip or conda install the following packages (for Python 3.7):
* `pandas` version 1.0.5
* `matplotlib` version 3.2.2
* `seaborn` version 0.10.1
* `numpy` version 1.19.0 (should install with Pandas)
* `plotnine` version 0.7.0
* `scikit-learn` version 0.23.1
* `jupyter` version 1.0.0
If you are running an older version of Python run install using `pip install -U <package name>` to update your packages just make sure you are at least using Pandas >= 1.0.0.

For the tutorial I will be using a conda environment `conda create env -n py37 python=3.7` but feel free to bypass a virtual environment.  The `requirements.txt` contains the base packages to install (`pip install requirements.txt`).

## Usage
Data_Viz_Tutorial notebook is intended to be used for live coding during the technical talk but if you get behind or run into errors, you can use Data_Viz_Tutorial_Solution to check your work.

