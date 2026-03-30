# Data Visualization - Assignment 1: Python

## Environment set up

Below is a detailed explanation of how to set up the project for proper execution.

### Project structure

All the files must be at root directory for propper function.

```sh
project-root/
├── data                          # Folder with local data files
│   └── activities.csv            # Local CSV with activity data
├── data_viz_notebook.ipynb       # Jupyter Notebook with Markdown and Python code
├── docs                          # Folder with local documentation files
│   ├── assignment.pdf            # Assignment instructions
│   └── report.pdf                # TODO: To be added
├── environment.yml               # Conda environment declaration
├── README.md                     # This file
└── video.md                      # TODO: To be added
```

### Pthon environment

Python dependencies are managed through conda, install conda following the official documentation:

- https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html

After installing conda, activate the environment with the following command:

```sh
conda env create --name dv_itziar -- file=environment.yml
```
