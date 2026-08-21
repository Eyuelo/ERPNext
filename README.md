ERPNext Reports and Print Formats
Overview

This project contains custom ERPNext reports and print formats designed to improve data analysis, document presentation, and business workflows in ERPNext.

Features
Reports

The project includes custom ERPNext reports that provide structured views of business data for operational and management purposes.

Typical features include:

Custom filters
Date-range filtering
Company and branch filtering
Customer and supplier filtering
Item and warehouse filtering
Calculated fields
Grouping and summaries
Exportable report data

Reports can be implemented as:

Query Reports
Script Reports
Custom report filters
Business-specific calculations and data presentation
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
Quotation
Other ERPNext DocTypes

Print formats can use:

Jinja templates
HTML
CSS
ERPNext document fields
Custom business logic
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

Requirements

The project requires:

Frappe Framework
ERPNext
A configured ERPNext site
Appropriate user permissions for reports and print formats