# Assignment 4 – Python Programming

## File Handling, Exception Handling, Modules and Packages (CO4)

**Course:** Python Programming  
**Course Code:** CSA 0812  
**Course / Section:** CSA 0812 D  
**Student Name:** SHAIK SHAHID  
**Register Number:** 1925260075  
**Department:** Artificial Intelligence and Machine Learning  
**Python Version:** Python 3.12  
**Repository:** https://github.com/shahidshaik210109-dev/ASS-4-PYTHON.git  

## About the Assignment

This assignment focuses on Python file handling, exception handling, modules, packages, and practical application development.

It contains six tasks covering file-processing design, biometric attendance management, error handling, file operations, modular programming, and a college fest registration system.

## Tasks Covered

### Task 1 – File-Processing Design Review
- Identifying errors in Python file-processing programs.
- Repairing inefficient file-handling code.
- Using `with open()` for safe file operations.
- Handling invalid records.
- Using the Decimal module for accurate monetary calculations.
- Time and space complexity analysis.

### Task 2 – Biometric Attendance File Design
- Reading attendance files.
- Processing CSV-style records.
- Using dictionaries to store attendance data.
- Generating monthly attendance reports.
- Identifying students below 75% attendance.
- Recording damaged input lines.

### Task 3 – Error Handling in the Attendance Processor
- Understanding Python exceptions.
- Using `try`, `except`, `else` and `finally`.
- Creating custom exceptions.
- Handling missing files and invalid records.
- Testing exception-handling mechanisms.
- Comparing validation approaches.

### Task 4 – File and Exception Forensics
- Identifying file-handling defects.
- Understanding file modes (`r`, `w`, `a`).
- Preventing accidental data loss.
- Using context managers.
- Maintaining error logs.
- Repairing file-processing programs.

### Task 5 – The Same Utility Organised Four Ways
- Single Python script.
- One module imported by a main script.
- Multiple modules in one folder.
- Python packages.
- Understanding import statements.
- Comparing code organization, reusability and maintainability.

### Task 6 – College Fest Registration Desk
- Processing multiple department files.
- Validating registration details.
- Email validation.
- Detecting duplicate registrations using sets.
- Handling invalid records and file errors.
- Generating master registration files.
- Creating event-wise participant lists.
- Generating summary reports and error logs.

## Technologies and Libraries Used

**Programming Language:** Python 3.12

**Python Standard Library:**
- `csv` – CSV file processing.
- `pathlib` – File and directory handling.
- `os` – Operating system operations.
- `tempfile` – Temporary file creation.
- `decimal` – Accurate monetary calculations.
- `datetime` – Date and time operations.

**Dependencies:** No third-party packages required.

## Repository Structure

```text
ASS-4-PYTHON/
│
├── README.md
├── requirements.txt
│
├── Task01/
│   └── task1.py
│
├── Task02/
│   └── task2.py
│
├── Task03/
│   └── task3.py
│
├── Task04/
│   └── task4.py
│
├── Task05/
│   ├── main.py
│   ├── attendance_utils.py
│   ├── reader.py
│   ├── stats.py
│   └── report.py
│
├── Task06/
│   ├── main.py
│   └── college_fest/
│       ├── __init__.py
│       ├── reader.py
│       ├── validation.py
│       ├── processing.py
│       └── writer.py
│
├── input/
├── output/
└── screenshots/
```

## How to Run the Programs

Make sure Python 3.12 is installed.

Run the individual tasks using:

```bash
python Task01/task1.py
python Task02/task2.py
python Task03/task3.py
python Task04/task4.py
python Task05/main.py
python Task06/main.py
```

## Results

- **Task 1:** Repairs the mess-bill processor and records rejected lines.
- **Task 2:** Designs monthly attendance summaries and damaged-line reports.
- **Task 3:** Handles invalid records and file-level exceptions.
- **Task 4:** Preserves daily return logs and records file-processing errors.
- **Task 5:** Demonstrates four different Python program organization methods.
- **Task 6:** Generates unique college fest registrations, event-wise participant lists, summaries and error logs.

## Learning Outcomes

Through this assignment, I learned how to:

- Perform file reading and writing operations.
- Handle exceptions effectively.
- Create and use custom exceptions.
- Validate input data and manage errors.
- Work with Python modules and packages.
- Organize large programs into multiple files.
- Process CSV files and generate reports.
- Use dictionaries and sets for efficient data processing.
- Build practical file-based applications.

## Conclusion

This assignment helped me develop practical knowledge of Python file handling, exception handling, modules and packages. It improved my ability to write reliable, reusable and maintainable Python programs through real-world problem-solving exercises.

---

**Submitted by:** SHAIK SHAHID  
**Register Number:** 1925260075  
**Course:** Python Programming  
**Course Outcome:** CO4
