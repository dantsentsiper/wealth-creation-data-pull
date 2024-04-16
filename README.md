
# Wealth Creation Data Pull 

This suite consists of three primary tools designed to streamline the data pull process, including attendee tracking, data pulling for events, and HR data processing. Below you'll find details on each tool, including their functionality and setup instructions.

## Prerequisites

Before running these tools, ensure you have the following installed:
- Python 3.8 or higher
- pandas library
- tkinter library for GUI operations
- openpyxl library for Excel operations

You can install the required Python packages using pip:

```bash
pip install pandas 
pip install openpyxl
```

Tkinter typically comes pre-installed with Python. If not, you can install it using your package manager. For example, on Ubuntu:

```bash
sudo apt-get install python3-tk
```

## Tools

### 1. Attendee-Tracker

**Functionality:** This tool processes multiple CSV files to track event attendees and updates a central database with unique attendee information.

**How to Run:**
1. Execute the script.
2. Use the file dialog to select one or more CSV files containing attendee data.
3. The tool will process these files and update the attendee database accordingly.

### 2. Data-Pull

**Functionality:** Extracts data based on event type and date, allowing users to filter event data and save the results in an Excel file.

**How to Run:**
1. Launch the script.
2. A file dialog will appear for selecting the event database (CSV format).
3. Choose the event type and specify the date range through the GUI.
4. Filtered data will be saved to an Excel file.

### 3. HR-Tool

**Functionality:** Processes personnel data from multiple Excel files, merges data based on specific criteria, and outputs combined data.

**How to Run:**
1. Start the script.
2. Follow on-screen prompts to upload required Excel files (Personnel numbers file, Pre Event, and Post Event contribution files).
3. The tool processes these files and outputs a combined Excel spreadsheet.

## Important Notes

- Ensure that all Excel and CSV files are closed before running these tools to prevent read/write errors.
- Adjust file paths and settings in the code if necessary to match your local environment.



