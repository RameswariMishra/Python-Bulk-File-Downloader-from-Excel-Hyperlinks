# Python-Bulk-File-Downloader-from-Excel-Hyperlinks
This project automates bulk file downloads from Excel sheets where download links are stored as embedded hyperlinks rather than visible URLs.
The workflow extracts hyperlinks directly from Excel cells using openpyxl and downloads files efficiently using Python.

## Features
 - Read hyperlinks from Excel .xlsx files
 - Automatically extract hidden URLs
 - Download files using HTTP requests
 - Save files into local folders
 - Skip missing hyperlinks gracefully
 - Error handling for failed downloads
 - Object-Oriented Programming (OOP) implementation
 - Scalable structure for larger data ingestion workflows
   
## Technologies Used
- Python
- openpyxl
- requests
- pathlib

## Project Structure
```
project/
│
├── file_links.xlsx
├── downloader.py
├── oop_downloader.py
├── Resume (As a sample hyperlink file, that can be downloaded)
```
## Use Case
This project is useful for:
- Research dataset collection
- AI/ML data ingestion pipelines
- Automation workflows
- Bulk multimedia downloads
- Data engineering practice

## Learning Outcomes
- Working with Excel hyperlinks programmatically
- HTTP file downloading in Python
- Exception handling
- File system operations
- Writing reusable OOP-based automation code

## Future Improvements
- Multithreaded downloads
- Retry logic
- Progress bars
- Logging system
- Cloud storage integration
- Database tracking
- Checksum validation

## Installation
pip install openpyxl requests

## Run
python downloader.py

## Author
Rameswari Mishra
