# Customer-Report-Cobol-project-
a cobol project for its original use in business. A project made alongside taking Abhishek Rathi's mainframe course class. 


# Customer Report (Sequential File Processing)

Simple COBOL program that reads a sequential customer file and produces a formatted balance report.

## Concepts Demonstrated
- Sequential file handling (LINE SEQUENTIAL)
- FILE STATUS checking
- Data definition with PIC clauses
- Arithmetic (totals)
- Formatted report output
- Free-format COBOL

## Requirements
- GnuCOBOL 3.2


## How to Compile and Run

### Prerequisites
- GnuCOBOL installed
- You have already run `set_env.cmd` (or set the environment variables permanently)

### Steps

1. Open PowerShell and go to the project folder:
```powershell
cd path\to\customer-report
.\customer-report

cobc -x -free -o customer-report src/customer-report.cbl
.\customer-report
