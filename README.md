# Bill of Quantities (BoQ) Discrepancy Detector

A Python based tool for comparing updated Bill of Quantities against original to highlight discrepancies 

## Problem 

In construction and design, BoQs can be hundreds of pages long with thousands of rows. Updates made to the files based on client feedback or design changes can often result in inconsistencies in the files which become hard to detect manually, leading to pricing, quoting quantity and item mismatches.

## Solution 

A simple tool that compares two excel files and identitfies 

- changed quantities
- added items
- removed items
- item/code discrepancies
- pricing discrepancies

### Input 

- Original BoQ excel file
- Updated BoQ excel file

### Output 

- Discrepancy Report in CSV form


#### Tech Stack
- Python
- Pandas
- OpenPyXL

