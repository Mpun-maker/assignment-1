# Assignment 1 — Git, NumPy, and Pandas

## Project Overview

This repository contains my Assignment 1 work covering Git fundamentals, NumPy operations, and data manipulation using pandas.

The assignment demonstrates practical skills in version control, numerical computing, data cleaning, data transformation, and generating summary reports from a raw dataset.

## Project Structure

```text
assignment-1/
├── answers/
│   ├── 01_git_theory.md
│   ├── 02_numpy.py
│   └── 03_pandas.ipynb
├── data/
│   ├── make_data.py
│   └── scores_raw.csv
├── outputs/
│   └── summary.csv
├── .gitignore
├── requirements.txt
└── README.md
```

## Requirements

* Python 3.10 or later
* Git
* pip

## Setup Instructions

### 1. Clone the repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd assignment-1
```

### 2. Create a virtual environment

Windows:

```bash
python -m venv venv
```

macOS/Linux:

```bash
python3 -m venv venv
```

### 3. Activate the virtual environment

Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

Windows Command Prompt:

```cmd
venv\Scripts\activate.bat
```

macOS/Linux:

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

## Running the Assignment

### Part A — Git Theory

Open:

```text
answers/01_git_theory.md
```

This file contains explanations of Git fundamentals, branching, merging, remote repositories, Issues, project environments, and everyday Git workflows.

### Part B — NumPy

For the Python script:

```bash
python answers/02_numpy.py
```

If using a Jupyter notebook instead:

```bash
jupyter notebook answers/02_numpy.ipynb
```

### Part C — Pandas

Launch Jupyter:

```bash
jupyter notebook answers/03_pandas.ipynb
```

Run the notebook cells from top to bottom.

### Generate the Dataset

From the project root directory:

```bash
python data/make_data.py
```

This generates the raw dataset at:

```text
data/scores_raw.csv
```

### Generate the Summary Output

Run the pandas notebook from top to bottom. The notebook performs the cleaning and summarization tasks and generates:

```text
outputs/summary.csv
```

## Reproducibility

The project uses a virtual environment and `requirements.txt` to document its Python dependencies.

The raw dataset generator is included so the dataset can be recreated. The notebooks are committed with their outputs saved to demonstrate that the code has been executed.

## Author

Milan Pun

## Assignment

Assignment 1 — Git, NumPy, and Pandas
