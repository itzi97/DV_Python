# Data Visualization - Assignment 1: Python

## Environment set up

Below is a detailed explanation of how to set up the project for proper execution.

### Project structure

All the files must be at root directory for propper function.

```sh
project-root/
├── Visualization.ipynb          # Jupyter Notebook with Python and Markdown
├── activities.csv               # Local CSV
├── Assignment.pdf               # Assignment instructions
├── environment.yml              # Conda environment declaration
└── README.md                    # This file
```

### Pthon environment

Python dependencies are managed through conda, install conda following the official documentation:

- https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html

After installing conda, activate the environment with the following command:

```sh
conda env create --name dv_itziar -- file=environment.yml
```
