ERPNext Reports and Print Formats
Overview

This project contains custom ERPNext reports and print formats designed to improve data analysis, document presentation, and business workflows in ERPNext.

The customization may include:

Custom ERPNext reports
Query Reports
Script Reports
Report filters and parameters
Custom print formats
Jinja-based print templates
PDF/document layouts
Business-specific calculations and data presentation
Features
Reports

The reports provide structured views of ERPNext data for operational and management purposes.

Typical features include:

Custom filters
Date-range filtering
Company and branch filtering
Customer and supplier filtering
Item and warehouse filtering
Calculated fields
Grouping and summaries
Exportable report data
Print Formats

Custom print formats provide professionally formatted documents for ERPNext transactions.

They can be used for documents such as:

Sales Invoice
Purchase Invoice
Sales Order
Purchase Order
Delivery Note
Purchase Receipt
Payment Entry
Quotations
Other ERPNext DocTypes

Print formats may use Jinja templates, HTML, and CSS to control the document layout.

Project Structure
.
├── README.md
├── reports/
│   ├── report_name/
│   │   ├── report_name.json
│   │   └── report_name.py
│   └── ...
├── print_formats/
│   ├── print_format_name/
│   │   └── print_format_name.json
│   └── ...
└── ...

The actual directory structure may vary depending on whether the customizations are maintained in an ERPNext/Frappe custom app or exported as fixtures.