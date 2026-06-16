# Bonus Calculation Automation

This project automates a monthly bonus calculation process for an equipment rental business.

## Business Problem

The bonus calculation process used to be extremely manual.

Every month, the team had to open multiple equipment measurement records, check how many days each machine had been rented, identify the related customer and manually add each line to a spreadsheet.

This process could easily take hours and was prone to manual errors.

## Solution

I built a Python workflow that automatically processes operational data, reconstructs machine rental activity for the month and generates the information needed for the monthly bonus calculation.

## What the workflow does

* Reads operational data from Google Sheets
* Processes equipment movement records
* Identifies which machines were rented during the month
* Calculates rental days by machine and customer
* Applies business rules for the bonus calculation
* Generates a structured output for reporting
* Supports monthly status tracking through dashboards

## Impact

* Reduced a process that took hours to seconds
* Reduced repetitive manual work
* Improved calculation consistency
* Made the process easier to audit
* Improved monthly operational visibility

## Tech Stack

* Python
* Pandas
* Google Sheets
* Excel

## Project Status

Active project

This project is actively used and continuously improved as new business requirements emerge.
