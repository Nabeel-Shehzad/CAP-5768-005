# Twitter Analysis EDA Project - Environment Setup

This directory contains the requirements files for the CAP 5768-005 Twitter conversation dataset analysis project.

## Requirements Files

### `requirements.txt` (Recommended)
Contains only the essential packages needed to run the Twitter analysis:
- pandas (data manipulation)
- numpy (numerical computing)
- scipy (statistical analysis)
- matplotlib (plotting)
- seaborn (statistical visualizations)
- jupyter (notebook environment)

### `requirements_full.txt` (Complete Environment)
Contains all packages installed in the virtual environment for exact replication.

## Installation Instructions

### Option 1: Essential packages only (Recommended)
```bash
# Create virtual environment
python -m venv twitter_analysis_env

# Activate virtual environment (Windows)
twitter_analysis_env\Scripts\Activate.ps1

# Install required packages
pip install -r requirements.txt
```

### Option 2: Full environment replication
```bash
# Create virtual environment
python -m venv twitter_analysis_env

# Activate virtual environment (Windows)
twitter_analysis_env\Scripts\Activate.ps1

# Install all packages
pip install -r requirements_full.txt
```

## Running the Analysis

After installing requirements:
```bash
# Start Jupyter notebook
jupyter notebook

# Open Twitter_Analysis_EDA_Final.ipynb
```

## Project Files

- `Twitter_Analysis_EDA_Final.ipynb` - Complete analysis with all 28 steps
- `project_data.csv` - Twitter conversation dataset
- `instructions.txt` - Original project requirements
- `project_completion_report.md` - Project summary and results

## System Requirements

- Python 3.8 or higher
- Windows OS (paths configured for Windows)
- Minimum 4GB RAM (recommended 8GB for large dataset processing)
