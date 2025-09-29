# CSV Toolkit Pack (Rust CLI) — QuickCSV Tools

Clean, filter, sort, and summarize your CSV files instantly using this toolkit.  
Works on Windows. No coding required.

Note: Input CSV must have headers

---

## Contents

- `binary/` — Windows executable (.exe)
- `sample/example.csv` — test CSV for demo  
- `README.md` — this file   

---

## Getting Started

### 1. Extract the ZIP
Unzip the `csv_toolkit` folder anywhere on your computer.

### 2. Open Terminal / Command Prompt
Navigate to the `binary/` folder:

> **Note for bash/Linux users: ** add `./` before executable e.g. `./rust_csv_cli_marketing.exe`

```cmd
cd path\to\csv_toolkit\binary

## Run the Tool:  
rust_csv_cli_marketing.exe --help 

### Basic examples:  
# Clean a CSV with min/max filter (keep LeadScore between 10 and 100)
rust_csv_cli_marketing.exe --file ../sample/example.csv --column LeadScore --min 10 --max 100 --output cleaned.csv

# Remove duplicate emails
rust_csv_cli_marketing.exe --file ../sample/example.csv --column LeadScore --dedupe Email

# Validate emails (removes rows with invalid emails in Email column)
rust_csv_cli_marketing.exe --file ../sample/example.csv --column LeadScore --invalid-email-column Email

# Drop rows where Name is empty
rust_csv_cli_marketing.exe --file ../sample/example.csv --column LeadScore --drop-empty Name

# Tag rows with a new column 'Source' labeled 'ad_campaign'
rust_csv_cli_marketing.exe --file ../sample/example.csv --column LeadScore --tag Source=ad_campaign

# Sort by Name in descending order
rust_csv_cli_marketing.exe --file ../sample/example.csv --column LeadScore --sort Name --sort-desc

# Limit output to 100 rows
rust_csv_cli_marketing.exe --file ../sample/example.csv --column LeadScore --limit 100

# Hide summary stats
rust_csv_cli_marketing.exe --file ../sample/example.csv --column LeadScore --no-summary



** Disclaimer: **
This software is provided as-is, without warranty of any kind.
The author is not liable for any damages or data loss resulting from using this tool. Use at your own risk.

** Refunds: **
As this is a brand new launch, refunds can be requested if the tool doesn’t meet your needs.



© 2025 QuickCSV Tools. All rights reserved.
This digital product may not be redistributed, resold, or modified without permission.