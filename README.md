# datafun-06-eda Repository for Project 6 EDA Notebook - Exploratory Data Analysis with Jupyter: Planets Dataset

## Overview

This repository contains a Jupyter Notebook for exploratory data analysis (EDA) of the Planets dataset. The analysis includes a series of steps to visualize, understand, and prepare the data for further statistical analysis or machine learning modeling.

## Dataset Description

This EDA will analyze the "Planets" dataset from the Seaborn library. It contains information about planets discovered around other stars, known as exoplanets, through the Kepler space telescope and other methods. The dataset can be accessed via Github: [Planets Dataset](https://github.com/mwaskom/seaborn-data/blob/master/planets.csv)

The table below provides an overview of columns and descriptions found in the Planets dataset:

| Column Name     | Description                                                                                     |
|-----------------|-------------------------------------------------------------------------------------------------|
| `method`        | The method by which the planet was discovered. Examples include radial velocity, transit, imaging, etc. |
| `number`        | The number of planets discovered in the system.                                                |
| `orbital_period`| The time the planet takes to complete one orbit around its star, typically measured in days.   |
| `mass`          | The mass of the planet, usually in Jupiter masses.                                              |
| `distance`      | The distance from the planet to Earth, measured in parsecs.                                     |
| `year`          | The year in which the planet was discovered.                                                    |


## Project Structure & Deliverables

- `README.md`: Provides an overview of the project and instructions for setting up the environment and running the notebook.
- `requirements.txt`: Lists all the Python packages required for the project.
- `tmontague_eda.ipynb`: The Jupyter Notebook containing the EDA for the Planets dataset.

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
py -m pip install jupyterlab numpy pandas matplotlib seaborn scipy pyarrow
```

- Add a useful .gitignore to the root project folder.

- Start Jupyter: Do both methods. Both methods must be available.
    - Method 1: Start Jupyter in VS Code: Open project folder in VS code, Install Jupyter extension in VS code (if not already installed), Open VS Code Terminal window, and run `jupyter lab` in integrated terminal.
    - Method 2: Start Jupyter in Native Terminal (without VS Code): Open machine terminal in project folder, Start Jupyter Notebook server by running: `jupyter lab`; Default brower will open to Jupyter Notebook interface.


## Project Start

1. Create the Notebook: In the VS Code Explorer, create a new file i.e., `tmontague_eda.ipynb`. Ensure it has a .ipynb extension.
2. Verify your new notebook is open for editing. If needed, view the project files in VS Code Explorer and double-click the notebook file to open it for editing.
3. Add a Markdown cell at the top of your notebook with the introduction (include the title, author, date and the purpose of the project).

