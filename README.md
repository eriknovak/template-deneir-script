# Template Experiment Project

This is a template repository for creating an experiment environment in Python. It intends to speed up the research process - reducing the repository structure design - and to have it clean and concise through multiple experiments.

Inspired by the [cookiecutter] folder structure.

## 📁 Project structure

The project is structured as follows:

```plaintext
.
├── data/                    # Data used in the experiments
├── models/                  # Models container folder
├── notebooks/               # Experiment notebooks
├── pipelines/               # The experiment pipelines
├── results/                 # Experiment results
├── scripts/                 # The scripts
├── src/                     # Source code
├── .gitignore               # Git ignore config
├── .pre-commit-config.yaml  # Pre-commit config
├── LICENSE                  # License
├── README.md                # Project readme
├── pyproject.toml           # The project config
└── requirements.txt         # Project dependencies
```

## ☑️ Requirements

Before starting the project make sure these requirements are available:

- [python]. For setting up the environment and Python dependencies (version 3.8 or higher).
- [git]. For versioning your code.

## 🛠️ Setup

### Create a python environment

First, create a virtual environment where all the modules will be stored.

#### Using venv

Using the `venv` command, run the following commands:

```bash
# create a new virtual environment
python -m venv venv

# activate the environment (UNIX)
source ./venv/bin/activate

# activate the environment (WINDOWS)
./venv/Scripts/activate

# deactivate the environment (UNIX & WINDOWS)
deactivate
```

### Install

Check the `requirements.txt` file. If you have any additional requirements, add them here.

#### Using pip
To install the requirements run:

```bash
# install the dependencies
pip install -e .[dev,test]
```

### Install pre-commit hooks

To install the pre-commit hooks, run the following command:

```bash
pre-commit install
```

## 🗃️ Data

TODO: Provide information about the data used in the experiments

- Where is the data found
- How is the data structured

## ⚗️ Experiments

To run the experiments, run the following commands:

```bash
TODO: Provide scripts for the experiments
```

### Results

The results folder contains the experiment

TODO: Provide a list/table of experiment results

## 📦️ Available models

This project produced the following models:

- TODO: Name and the link to the model

## 🚀 Using the trained model

When the model is trained, the following script shows how one can use the model:

```python
TODO: Provide an example of how to use the model
```

## 📣 Acknowledgments

TODO: Acknowledgements

[cookiecutter]: https://drivendata.github.io/cookiecutter-data-science/
[python]: https://www.python.org/
[git]: https://git-scm.com/
