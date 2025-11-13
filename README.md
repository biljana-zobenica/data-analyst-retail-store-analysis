# Retail Store Analysis

## Project description:

This project includes a python-based ETL pipeline for sales data ingestion,
cleaning, transformation, and analysis, with final insights visualized in 
an interactive Power BI report.

## Project structure:

```plaintext
Retail_Store_Analysis/
│
├── retail_store_us.xlsx       # Excel file with raw sales data: orders, returns and users
├── reporting_pipeline.ipynb   # Jupyter Notebook file for analysis and transformation
├── reporting_table.csv        # Output reporting file for Power BI
├── requirements.txt           # List of required packages
└── README.md                  # Instructions and documentation
```

## Setup instructions:

### 1 - Clone the repository

```
git clone <SSH or HTTPS link of the repo>

cd repo
```

### 2 - Create and activate virtual environment

#### for macOS/Linux:
```
python3 -m venv venv

source venv/bin/activate
```

#### for Windows:
```
python3 -m venv venv

call venv\Scripts\activate.bat
```
### 3 - Install requirements.txt
```
pip install -r requirements.txt
```

### 4 - Run jupyter notebook
```
jupyter notebook
```