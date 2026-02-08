Create a new workflow in n8n and save it
Add the trigger node "When clicking 'Execute workflow'" for manual testing
Add Get row(s) in sheet (Google Sheets - Read) to fetch data from the source sheet
Configure the sheet, worksheet, and row range to read the data you need
Add an IF node to check a specific condition from the sheet data
Example: If column value is "Yes" or number > 10 or status = "Approved"
Connect Get row(s) in sheet → IF node
Configure the IF condition based on your logic (string, number, boolean, value match, etc.)
Add Append row in sheet (Google Sheet 1) for the TRUE condition
Add Append row in sheet1 (Google Sheet 2) for the FALSE condition
Connect:
IF → TRUE → Append row in sheet
IF → FALSE → Append row in sheet1
Map the required fields from the input data to each sheet's columns
Test the entire workflow with Execute workflow
Once validated, activate the workflow for automated conditional sheet routing

#screenshot

![WhatsApp Image 2026-02-08 at 12 20 21 PM](https://github.com/user-attachments/assets/c4f96054-f974-41cc-84d1-f6a0835d6d75)
