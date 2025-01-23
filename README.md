# Google-Apps-Script-Automatic-Timestamp-on-Column-Edit
**Description for GitHub**: 

### Google Apps Script: Automatic Timestamp on Column Edit

This Google Apps Script adds a timestamp to column A whenever a cell in column B is edited. It is designed for Google Sheets and provides an efficient way to track updates in real time. 

**Features:**
- Automatically records the current date and time in column A when a value is entered into column B.
- Includes the day of the week, formatted as `Day, YYYY-MM-DD HH:mm` in 24-hour format.
- Ensures timestamps are only added if column A is empty, preventing overwriting existing data.

**Usage:**
1. Open your Google Sheet.
2. Navigate to `Extensions > Apps Script` and paste the code.
3. Save the script and ensure it's bound to your Google Sheet.
4. Edit any cell in column B to see the timestamp appear in column A.

**Example Use Cases:**
- Tracking the timestamp of task completions.
- Logging data entry times in collaborative sheets.
- Monitoring updates in project management or inventory sheets.

Feel free to customize the script for your specific needs!
