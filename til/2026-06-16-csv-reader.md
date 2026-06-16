# TIL — June 16, 2026

## What I did today
- Fixed Git repo setup issues
- Successfully cloned all 3 repos
- Built first Python script: read_csv.py
- Learned how to read CSV files using Pandas

## Commands I learned
```powershell
Remove-Item -Recurse -Force <folder>  # delete a folder
git clone <url> <foldername>          # clone with custom name
Invoke-WebRequest -Uri <url> -OutFile <path>  # download a file
```

## What the script does
- Loads a CSV file using pandas
- Shows rows, columns, first 5 rows
- Counts null values per column

## What confused me
i made a new folder by a mistake which already exsisted so it was a mess i put all the data in that before and had to move it again 

## Tomorrow's goal
Build csv_cleaner.py — remove duplicates and handle null values