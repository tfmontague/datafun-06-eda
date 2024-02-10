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
py -m pip install jupyterlab numpy pandas matplotlib seaborn scipy pyarrow plotly bokeh scikit-learn holoviews datashader altair
```

- Add a useful .gitignore to the root project folder.

- Start Jupyter: Do both methods. Both methods must be available.
    - Method 1: Start Jupyter in VS Code: Open project folder in VS code, Install Jupyter extension in VS code (if not already installed), Open VS Code Terminal window, and run `jupyter lab` in integrated terminal.
    - Method 2: Start Jupyter in Native Terminal (without VS Code): Open machine terminal in project folder, Start Jupyter Notebook server by running: `jupyter lab`; Default brower will open to Jupyter Notebook interface.

## Project Start

1. Create the Notebook: In the VS Code Explorer, create a new file i.e., `tmontague_eda.ipynb`. Ensure it has a .ipynb extension.
2. Verify your new notebook is open for editing. If needed, view the project files in VS Code Explorer and double-click the notebook file to open it for editing.
3. Add a Markdown cell at the top of your notebook with the introduction (include the title, author, date and the purpose of the project).

## Data Analysis Workflow
The Jupyter Notebook follows a structured approach to EDA, consisting of the following steps:

1. **Data Acquisition**: Loading the Planets dataset into a pandas DataFrame.
2. **Initial Data Inspection**: Exploring the dataset's basic properties.
3. **Descriptive Statistics**: Summarizing the central tendency, dispersion, and shape of the dataset's distribution.
4. **Data Distribution Analysis**: Visualizing the distribution of data through histograms and count plots.
5. **Data Transformation and Feature Engineering**: Enhancing the dataset with additional features and transformations for better analysis.
6. **Visual Analysis**: Using various plots such as pairplots and heatmaps to visualize relationships between features.
7. **Storytelling and Presentation**: Narrating the data story based on insights derived from the visual analysis.
8. **Conclusion**: Summarizing the findings and the potential for further analysis.

## Contributing
We welcome contributions to this project. If you have suggestions to improve the analysis or encounter issues, please open an issue or submit a pull request.

## References & Acknowledgments
Special thanks to [OpenAI](https://openai.com/) for assistance with project design and coding structure. Additional references used for this project include:

 - [JUPYTER.md](https://github.com/denisecase/datafun-04-spec/blob/main/JUPYTER.md) for Jupyter Notebook keyboard shortcuts and recommendations.

 - [MARKDOWN.md](https://github.com/denisecase/datafun-04-spec/blob/main/MARKDOWN.md) for Markdown syntax and recommendations.

 - [Data Visualization using Python, Matplotlib and Seaborn](https://jovian.com/srsomnath123/data-visualization-using-matplotlib-and-seaborn) for visualization project ideas.

 - [Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html) for assistance with plotting functions.

 - [Linear Regression in Python using Jupyter Notebooks!](https://www.youtube.com/watch?v=hitCh7-ZItQ) to create forecasting projections.

 - [3D Scatter Plots in Python](https://plotly.com/python/3d-scatter-plots/) to create 3D scatter plots.