# GRID Python Units 7 & 8 – Practical Test Set B

## Project Overview
This project contains Python practical assignments for Units 7 and 8. It covers standard Python modules, file handling, custom modules, packages, NumPy and Pandas.

## Sections Covered

### Section A – Standard Python Modules
- Date and Time using `datetime`
- Mathematical operations using `math`
- Random number generation
- UUID generation
- Performance measurement using `time`

### Section B – OS, Modules and Packages
- File and folder handling using `os`
- Moving and renaming files using `shutil`
- Creating custom Python modules
- Importing modules in different ways
- Creating packages and sub-packages

### Section C – NumPy
- Creating NumPy arrays
- Array indexing and slicing
- Boolean masking and filtering
- Array mathematical operations
- Mean, median, variance and standard deviation
- Reshaping and broadcasting
- Splitting arrays

### Section D – Pandas
- Series and DataFrame
- Reading CSV files
- Handling missing values and duplicates
- Data cleaning and conversion
- Filtering and sorting data
- Grouping and aggregation
- Pivot tables
- Merging DataFrames
- Reading and writing JSON files

## Project Structure

```text
GRID_Python_U7_U8_V2_SetB/
│
├── README.md
├── A_standard_modules.py
├── B_os_demo.py
├── scoretools.py
├── B_main_module.py
├── B_main_package.py
├── C_numpy_tasks.py
├── D_pandas_tasks.py
│
├── textkit/
│   ├── __init__.py
│   ├── clean.py
│   ├── stats.py
│   └── extra/
│       ├── __init__.py
│       └── frame.py
│
├── students.csv
├── mentors.csv
├── names.json
│
└── Screenshots/
```

## Requirements

- Python 3.x
- NumPy
- Pandas

## Installation

Install the required libraries:

```bash
python -m pip install numpy pandas
```

## How to Run the Project

Open the terminal in the project folder and run:

**Section A**
```bash
python A_standard_modules.py
```

**Section B**
```bash
python B_os_demo.py
python scoretools.py
python B_main_module.py
python B_main_package.py
```

**Section C**
```bash
python C_numpy_tasks.py
```

**Section D**
```bash
python D_pandas_tasks.py
```

## Input Files

The project uses two CSV files:

- `students.csv` – Contains student information.
- `mentors.csv` – Contains mentor information.

The Pandas section also generates a `names.json` file.

## Learning Outcomes

After completing this project, I learned:

1. How to use Python standard modules.
2. How to manage files and directories.
3. How to create and import custom modules.
4. How to work with Python packages.
5. How to perform numerical operations using NumPy.
6. How to clean and analyse data using Pandas.
7. How to work with CSV and JSON files.

## Author

**Name:** Your Name  
**GRID:** Your GRID Number

## Conclusion

This project helped me improve my Python programming skills and understand standard modules, packages, NumPy and Pandas through practical exercises.
