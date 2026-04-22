Mock CRF Data Cleaner

A Python-based tool to simulate Clinical Data Management (CDM) workflows by cleaning and validating mock Case Report Form (CRF) data.

## Features

- Detects missing values
- Flags out-of-range clinical parameters
- Identifies logical inconsistencies (e.g., Male marked as Pregnant)
- Generates summary validation reports

## Tech Stack

- Python
- Pandas

##  Sample Use Case

This project mimics real-world clinical trial data cleaning processes aligned with:
- ICH-GCP guidelines
- eTMF documentation practices
- Data validation workflows used in CROs

##  How to Run

```bash
pip install -r requirements.txt
python crf_data_cleaner.py
