# File Organizer

## Description
This Python script automatically organizes files in a specified directory into subdirectories based on their file types. It categorizes files into 'photos', 'pdfs', and 'others' folders.
works on both MacOS and WindowsOS

## Features
- Automatically creates subdirectories if they don't exist
- Moves PDF files to a 'pdfs' folder
- Moves PNG files to a 'photos' folder
- Moves TXT and XLSX files to an 'others' folder
- Leaves files with other extensions in the original directory

## Requirements
- Python 3.x
- jupyter notebook
- No external libraries required (uses only built-in `os` and `shutil` modules)

## Usage
1. Set the `path` variable in the script to the directory you want to organize.
2. Run the script:
