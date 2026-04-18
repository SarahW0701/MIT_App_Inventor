# MIT App Inventor Projects
This repository contains a collection of small applications developed with MIT App Inventor. 

---

## Overview

The repository includes multiple independent apps. Each project is provided as an `.apk` source file and directly useable on a smartphone allowing downloads. 

---

## Project List

| Name | Description | File |
|------|------------|------|
| QR Scanner | Scans QR codes and allows opening detected links directly | `QR_Scanner.apk` |
| Expense Tracker | Quickly records personal expenses | `Expense_Tracker.apk` |

---
---

## Detailed Descriptions of Projects

### QR Scanner

#### Purpose
Scan QR codes and open embedded web links.

#### Features
- QR code scanning via device camera
- Displays preview of detected link before opening
- Direct access to scanned websites

#### Inputs
- User interaction via "QR-Code scannen" button
- QR code captured through the device camera

#### Outputs
- Display of the scanned link in the app interface
- Option to open the link in a web browser

#### How to Use
1. Tap "QR-Code scannen" to activate the camera
2. Scan a QR code
3. Review the detected link shown on screen
4. Tap "Webseite öffnen" to open the link

#### Notes / Limitations
- Only supports QR codes containing URLs
- Requires camera access
- No validation of link safety before opening

---

### Expense Tracker

#### Purpose
Quickly record and review personal expenses.

#### Features
- Simple expense entry with optional marking (indented)
- Automatic or manual date assignment
- Ability to delete individual or all entries

#### Inputs
- Text input in the "Ausgaben" field
- Optional marking via checkbox (indentation)
- Optional date selection via "Datum"

#### Outputs
- Chronological list of recorded expenses
- Display of date and corresponding entry
- Indented formatting for marked entries

#### How to Use
1. Enter an expense in the "Ausgaben" field
2. Optionally mark the entry using the checkbox (creates an indented entry)
3. Adjust the date if needed via "Datum"
4. Tap "Eingeben" to save the entry
5. To delete an entry, select it, tap "Löschen", and confirm
6. To clear all entries, tap "Neu" and confirm

#### Notes / Limitations
- No categorization or aggregation of expenses
- Entries are stored locally within the app
- No data export or persistence beyond app storage
