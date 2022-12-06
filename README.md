# hd1codeplug
This is an excel worksheet and associated Python script that is used to create the neccassary files for an HD1 Code PLug

## Installation 
The code itself relies on the open 'openpyxl' Python library. To install use pip

pip install openpyxl

The copy the scipt into the folder that contains you excel spreasheet

## Create an Excel spreadsheet
python3 codeplug.py input.xlsx xlsx output.xlsx

## Create associated CSV Files
python3 codeplug.py input.xlsx csv

This will create the following files that can be loaded into your HD1 software

- HD1 Channel Information.csv
- HD1 Priority Contacts.csv
- HD1 Address Book Contacts.csv

## Template Excel Sheet


