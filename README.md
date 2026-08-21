# ERPNext Reports and Print Formats

> Overview

This project contains custom ERPNext reports and print formats designed to improve data analysis, document presentation, and business workflows in ERPNext.

## Features

## Reports

The project includes custom ERPNext reports that provide structured views of business data for operational and management purposes.

Typical features include:

- Custom filters
- Date-range filtering
- Company, Project and departement filtering
- Item and warehouse filtering
- Calculated fields
- Grouping and summaries


## Print Formats

Custom print formats provide professionally formatted documents for ERPNext transactions.

Print formats can use:

- Jinja templates
- HTML
- CSS
- ERPNext document fields
- Custom business logic


### Project Structure

├── README.md 
├── reports/ 
    │ ├── report_name/ │ 
    │ ├── report_name.json 
    │ │ └── report_name.py 
├── print_formats/ 
    │ ├── print_format_name/ 
    │ │ └── print_format_name.json 