# Document-Management-Reporting-Automation-Solution

## Overview

This project automates engineering document reporting using Power BI and Power Query.

The solution extracts structured information from document naming conventions and SharePoint folder paths, applies revision control logic, and generates automated operational reports and PDF-ready outputs.

The project was designed to reduce manual reporting effort, improve document visibility, and standardize document tracking processes.

---

## Business Problem

The original process relied on manually generated Excel reports based on SharePoint exports.

Main challenges included:

- Repetitive manual reporting
- Duplicated document revisions
- Difficulty identifying the latest approved documents
- Inconsistent document tracking
- Time-consuming PDF generation
- Manual filtering and data cleanup

---

## Solution

The Power BI solution automates:

- Metadata extraction from document names
- Folder path interpretation
- Revision control logic
- Delivery date logic
- Document classification
- Interactive filtering
- PDF-ready reporting layout

The project was also structured to support future SharePoint integration for automated refresh workflows.

---

## Features

- Dynamic Power Query transformations
- Naming convention parsing
- Automatic extraction of document metadata
- Latest revision filtering logic
- Automated delivery date calculation
- Interactive dashboard filters
- Dedicated PDF export page
- Offline testing workflow
- SharePoint-ready architecture

---

## Technologies Used

- Power BI
- Power Query
- DAX
- Excel
- SharePoint (planned integration)

---

## Workflow

```text
Excel / SharePoint Export
        ↓
Power Query ETL
        ↓
Business Logic Processing
        ↓
Revision & Delivery Rules
        ↓
Power BI Dashboard
        ↓
PDF Export
