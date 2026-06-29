# Correlations with Violent Crime Data Analysis Project

## Project Overview

This Data Analysis project is intended to use publicly available data to examine the correlation between different variables and the rates of violent crime. It will attempt to draw on the academic literature in Criminology to inform its analysis and approach. We are seeking participants with experience using machine learning models to expand our analysis using more advanced statistical methods.

Our goal is to understand what factors contribute to the rates of violent crime that we see in America, and understand the trends in violent crime over time. We want to suggest solutions to the problems facing Americans, affected either by violent crime, or by the consequences of policing it.

We want to better understand the historical and sociological roots of violent crime in America to explore better ways to address the problems it creates.

## Repository Structure

├── LICENSE            
│
├── README.md          <- The top-level README for developers using this project.
│
├── docs               <- TBD
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for assembling a venv using uv or pip.
│
├── uv.lock            <- Project configuration file with package metadata for assembling a venv using uv or pip.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
││
└── src                <- Source code for use in this project.
    │
    │
    ├── config.py               <- Useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling (TBD)               
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations   

## Installation

1. Clone the Repository:

```bash
git clone https://github.com/DragonBishop/{REPONAMEHERE}.git
cd {REPONAMEHERE}
```

2. Ensure the correct version of Python (3.14) is installed.

3. Instantiate the project's virtual environment (venv) and download dependencies.

```bash
# UV users can sync the venc using the provided pyproject.toml and uv.lock files.
uv sync
```

```bash
# Alternatively, activate a venv using the provided requirements.txt.
python3 -m venv env
env\Scripts\activate

#Install the necessary dependencies.
pip install -r requirements.txt
```

5. Ensure you have an IDE (VSCode, VIM, etc.) capable of running Python scripts and Jupyter notebooks. If using VSCode, recommended extensions:
    1. Python for VSCode
    2. Jupyter - Necessary to access and use Jupyter Lab notebooks.
    3. postgreSQL - If you also choose to spin up a postgreSQL server, use the official extension to interact with it.
    4. Data Wrangler - Useful for inspecting data structures in Python.

6. Download the dataset from Kaggle: 

7. OPTIONAL: Use postGIS' Docker Image to spin up a postgreSQL server with postGIS enabled, or download postgreSQL and spin up a server.

## Data Source(s)

TBD

## Usage

- Running notebooks: Launch JupyterLab or use VS Code’s Jupyter interface. Open the notebooks in the notebooks/ folder to run the analysis step by step. The Data Wrangler extension assists with manipulation of dataframes.
- Data and Results: Sample data is not included in the repository. You must import the Project datasets into your Postgres database or load CSV files as needed. You can find the datasets on Kaggle here:
- Visualizations: Use the attached scripts and notebooks to generate visualizations. (Visual outputs are not stored in this repo by default – they can be saved to files or referenced on Kaggle.)
- Citations: When writing analysis in notebooks or preparing reports, cite sources using the citation keys in references.bib. If using the JupyterLab Citation Manager, it will automatically sync with your Zotero library and format citations/bibliography.

## Contributing

Contributions and feedback are welcome! To contribute:

    Fork this repository.
    Create a new branch for your feature or bugfix.
    Commit changes with clear messages.
    Open a pull request for review.

Please use GitHub Issues to report bugs or request enhancements. Keep code and notebooks well-documented.

Code: MIT License
Data: Subject to the original data provider's terms of use.

## Contact

For questions or support, please open an issue on this GitHub repository.
