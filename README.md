# RAGOT_EventRegistrationFormatter
# Event Registration Formatter

## Description
A Python program that collects student and school event registration details, cleans messy text inputs, and displays a standardized, readable registration summary.

## Features
- **Input Cleaning:** Removes accidental leading and trailing spaces using `.strip()`.
- **Text Standardization:** Formats full names and event titles in Title Case using `.title()`, and converts name codes and sections to uppercase using `.upper()`.
- **Date Formatting:** Converts numeric year, month, and day inputs into a readable calendar format (e.g., `June 3, 2026`) using Python's `datetime` module.

## How to Run
1. Make sure Python 3 is installed on your computer or online IDE.
2. Run the program:
   ```bash
   python event_registration_formatter.py
   ```
3. Enter the student and event details when prompted.

## Sample Output
```text
Student Event Registration Summary
Name: Juan Dela Cruz
Name Code: JUAN DELA CRUZ
Section: MAGNESIUM
Event: Science Fair
Event Date: June 3, 2026
Language Used: Python
String Feature Used: strip(), title(), upper()
Date/Time Feature Used: datetime
Registration record created successfully.
```

## Version History
- **Version 1:** Initial version - basic input and output.
- **Version 2:** Added string formatting (`strip()`, `title()`, `upper()`).
- **Version 3:** Added date formatting using `datetime`.

## Reflection
Building this program step by step helped me understand how raw user input can be cleaned and organized into clear, readable output. At first, my Version 1 code simply displayed whatever the user typed, which looked messy when inputs had inconsistent capitalization or extra spaces. Adding string methods like `.strip()`, `.title()`, and `.upper()` in Version 2 solved this issue and made every registration record look uniform.

In Version 3, integrating Python's `datetime` module taught me how to convert plain numeric inputs for year, month, and day into a formal date string. One small detail I had to pay attention to was formatting the day without a leading zero so that it matched the exact sample output (`June 3, 2026`). Finally, using GitHub to save each stage as a separate commit showed me how version control keeps my progress organized and makes it easy to track improvements from a basic script to a finished tool.
