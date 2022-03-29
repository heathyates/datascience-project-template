# datascience-project-template
Template for data science project 

## Introduction 

This is is a data science template proposed to be used for python based data science projects. 


## Project Structure 

The following is the structure of the project for a data science project. 

- data
- workbench 
- visualizations 
- modeling 
- references 

In brief, the data is the collection of raw and processed data. The workbench is a collection of notebooks were were used for: data extraction/transformation/loading, exploratory data analysis, visualization scripts, and preliminary training/testing. In other words, it is an area that consists of potentially unpolished notebooks that comprise the data modeling work. The visualizations is the polished scripts and visualizations of the data science project. THe modeling is likewise the more refined testing, training, validation of models. Last, there is the references which could be supporting materials to assist the project. 

In addition to the above, there could be a section for report for a report or presentation materials. However, it is left out in case it is outside the scope of the project. 

## venv 

This project template uses venv, a python virtual environment tool. In order to establish a python virtual environment, you can do the following: `python3 -m venv env`. This creates the virtual environment in the env directory. You then run `source ./env/bin/activate` to load the virtual environment. This allows the developer to install dependencies with `pip install -r requirements.txt`. 


## Python 

The following basic python modules are used: 

- pandas 
- numpy
- matplotlib 
- scikit-learn 

## References 

- [How to Structure a Python-Based Data Science Project](https://medium.com/swlh/how-to-structure-a-python-based-data-science-project-a-short-tutorial-for-beginners-7e00bff14f56)
- [Cookie Cutter Data Science] https://drivendata.github.io/cookiecutter-data-science/#data-is-immutable
- [Reproducible Research](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3383002/)