# Power BI Deployment Automation

## Overview
This script automates deployment of Power BI reports across multiple workspaces, including:
- PBIX upload
- Dataset parameter updates
- Ownership handling
- Dataset refresh

## Architecture
Databricks / ETL -> Curated Data -> Power BI Dataset -> Python (API Automation)

## Prerequisites
- Python 3.9+
- Azure CLI installed and logged in
- Power BI Service Principal access

## Setup

1. Install dependencies:
pip install -r requirements.txt

2. Configure environment variables:
Copy config.env.example to .env and update values

3. Run:
python main.py

## Notes
- Do not commit secrets
- Use environment variables for all credentials

## Contact
Reach out to Swathi for walkthrough
