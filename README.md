# CIVS Machine Learning
This repo is intended to provide some instructive tasks in machine learning for the Center for Innovation through Visualization and Simulation at Purdue University Northwest.  If you are a student, please follow the guide found in the `docs/` directory.

## Problem Description
Simple combustion simulation data based on the ANSYS Fluent species combustion tutorial (Chapter 15 of the 2022 tutorial guide).  The data needs to be analyzed, cleaned up, plotted, and used in some simple ML applications.

## Setup Instructions

### 1. Create and activate virtual environment
```bash
python3 -m venv venv
source venv/bin/activate
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Set up Jupyter kernel
```bash
python -m ipykernel install --user --name=civs-ml --display-name "Python (CIVS ML)"
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook
```

### 5. Select the kernel
In Jupyter, go to **Kernel → Change Kernel → Python (CIVS ML)**

## Stucture
* `data/` Data storage directory. Comes with the raw data in hdf5 format.
* `docs/` Documentation/guide for the tasks, and any other supporting documents
* `fig/` Figures and saved plots
* `src/` Python and Jupyter notebooks, plus any other source code
