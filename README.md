# CSV Toolkit Pack (Rust CLI) — QuickCSV Tools

**Quickly clean, filter, sort, and organize your marketing CSV files for faster outreach campaigns.**  
No coding required — just download and turn messy lead lists into actionable data.

Works on Windows. Input CSV must have headers.

---

## Features

- Clean and filter leads by numeric ranges or other criteria
- Remove duplicates (emails, names, etc.)
- Validate emails and remove invalid entries
- Add tags to leads for campaigns
- Sort and limit your data for targeted outreach
- Export cleaned CSVs instantly

---

## Get the Tool

- **Direct Download:** Click **Code → Download ZIP** above to get the full toolkit with binaries and example CSVs.
- **Optional Support:** If you’d like to support the project and get the official packaged version, you can download it via [Gumroad](https://rusticmind.gumroad.com/l/quickcsv).

---

## Example Usage

```cmd
# Clean leads by score range
rust_csv_cli_marketing.exe --file example.csv --column LeadScore --min 10 --max 100 --output cleaned.csv

# Remove duplicate emails
rust_csv_cli_marketing.exe --file example.csv --column LeadScore --dedupe Email

# Tag leads for a campaign
rust_csv_cli_marketing.exe --file example.csv --column LeadScore --tag Source=ad_campaign
```
For full commands and options, see the included README.txt inside the folder


 ## Why QuickCSV?
- Save hours of manual spreadsheet work
- Get your marketing campaigns ready faster
- No technical expertise needed 

## Feedback Welcome
This is an early launch — I’d love to hear how you use QuickCSV, any issues you encounter, or suggestions for new features. Feel free to open an issue on GitHub
