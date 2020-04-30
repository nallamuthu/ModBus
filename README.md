#  ModBus 

Script take IP as input and brute force against all the registers. Identified valid registered will be exported to excel file

## Pre-requisite:
* pip install -r requirements.txt


## Scanners:
* NMAP - Top ports Scan
* SSLYZE - SSL Vulnerability Scan
* TESTSSL - Weak Ciphers Scan
* HEADER - HTTP Security Headers Scan
* CERTIFICATE - Certificate Scan


## Execution:
* python main.py -i ip_file.txt

## Output
* Sqlite DB File
* Excel File
* Zip File (Contains - DB, Excel and all the tool output)
