# Python Projects

A collection of Python projects covering automation, data handling, and small
engineering-focused tools. Most of these were written to solve a specific problem —
repetitive tasks, spreadsheets that needed automating, and small utilities that make
day-to-day work faster.

## What is in this repository

Each project is a self-contained folder with its own source code, a `README.md`
explaining what it does, and any example files or sample data needed to run it.

## Projects

### 1. Excel Automation System

A Python tool for automating routine work in Excel — cleaning sheets, filling in
formulas, running calculations across many files, and producing a consolidated output
without manual copy-paste.

**What it does**

- Reads one or more Excel workbooks
- Cleans and standardises data
- Applies formulas and calculations across sheets
- Writes results to a new workbook or updates existing ones
- Handles common formatting tasks (headers, column widths, number formats)

**Requirements**

- Python 3.9 or newer
- `openpyxl` (see `requirements.txt`)

**How to run**
cd excel-automation-system
pip install -r requirements.txt
python main.py --input path/to/workbook.xlsx --output path/to/result.xlsx


Adjust arguments as noted in the project README.

**Status**

Working. Used on real spreadsheets.

**Folder contents**

- `main.py`
- `requirements.txt`
- `sample_data/`
- `README.md` — Project-specific write-up

---

### 2. Freelance Tracker Desktop App

A desktop application for tracking freelance work — clients, projects, hours, and
invoices. Built with PySide6 for the interface and SQLite (or the storage you chose)
underneath.

**What it does**

- Add and manage clients
- Track projects and hours per client
- Record completed work and amounts
- View summaries by client or by date range
- Store everything locally so no internet connection is required

**Requirements**

- Python 3.9 or newer
- `PySide6` (see `requirements.txt`)

**How to run**
cd freelance-tracker-desktop
pip install -r requirements.txt
python main.py

**Status**

Working desktop application. Add notes here about which features are finished and which
are still planned.

**Folder contents**

- `main.py` — Application entry point
- `ui/` — PySide6 interface files
- `data/` — Database and models
- `requirements.txt`
- `README.md` — Project-specific write-up

---

## Requirements

Most projects require Python 3.9 or newer. Where additional packages are needed
(for example, `openpyxl`, `PySide6`, `pandas`), a `requirements.txt` is included in the
project folder.

To install dependencies for a specific project:
cd project-name
pip install -r requirements.txt

## How to run a project

Each project folder contains its own `README.md` with the exact command, required
inputs, and expected output. In most cases, it is as simple as:
python main.py
or, where arguments are used:
python main.py --input data.xlsx --output report.xlsx


## Notes

- Scripts and applications are written with clarity in mind — readable code, sensible
  names, and comments where the logic is not obvious.
- Where a script depends on a specific file format or package version, that is stated
  in the project's README.
- Error handling is kept practical: enough to catch obvious problems and give a clear
  message, without over-engineering small tools.

## About

Maintained by Henry Oyoto — Electronics and Computer Engineer working in PCB design,
Python programming and technical documentation.

- GitHub: https://github.com/HenryOyoto
- LinkedIn: https://www.linkedin.com/in/henryoyoto
- Email: oyotohenry2021@gmail.com

## License

Unless stated otherwise in a project folder, the code in this repository is released
under the MIT License. You are free to use, modify and share it, with attribution.
