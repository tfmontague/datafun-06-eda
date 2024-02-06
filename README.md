# datafun-06-eda Repository for Project 6 EDA Notebook - Exploratory Data Analysis with Jupyter: Planets Dataset

## Overview

This repository contains a Jupyter Notebook for exploratory data analysis (EDA) of the Planets dataset. The analysis includes a series of steps to visualize, understand, and prepare the data for further statistical analysis or machine learning modeling.

## Project Structure & Deliverables

- `README.md`: Provides an overview of the project and instructions for setting up the environment and running the notebook.
- `requirements.txt`: Lists all the Python packages required for the project.

## Environment Setup and How to Install and Run the Project

- Create a new GitHub repository named `datafun-06-eda`.
- Clone the repository to your local machine.
```console
git clone https://www.your-repository.com
```
- Create a Project Virtual Environment in the .venv folder.
- Activate the Project Virtual Environment.
- Freeze your requirements to requirements.txt.  (We can always install more packages and re-freeze to requirements.txt as we go.)

```console
py -m venv .venv
.\.venv\Scripts\Activate.ps1
py -m pip install requests
py -m pip freeze > requirements.txt
```
- Install dependencies

```console
py -m pip install jupyterlab numpy pandas matplotlib seaborn scipy
```

- Add a useful .gitignore to the root project folder.


