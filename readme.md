# GSCNSSAT ID Logging System

QR-based learner ID logging system for General Santos City National Secondary School of Arts and Trades (GSCNSSAT).

## Features

* QR code scanning using a laptop webcam
* Learner LRN verification
* Automatic date and time logging
* Section identification
* Google Sheets database
* Daily unique learner reports
* Weekly reports
* Monthly reports

## System Components

### Frontend

Hosted using GitHub Pages.

### Backend

Google Apps Script Web App.

### Database

Google Sheets.

### Reports

Separate Google Apps Script project for generating and emailing reports.

## QR Format

Example:

`408818180002,SHION VENZY TAKEO J.,June 23, 2013`

The system extracts the LRN and uses it to identify the learner from the masterlist.

## Author

GSCNSSAT
