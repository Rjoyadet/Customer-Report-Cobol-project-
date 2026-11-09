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
- GnuCOBOL 3.x

## How to Compile and Run

```powershell
# Make sure you have run set_env.cmd first
cobc -x -free -o customer-report src/customer-report.cbl
.\customer-report
