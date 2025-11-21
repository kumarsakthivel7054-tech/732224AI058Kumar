1. Add the Trigger

Drag “When clicking ‘Execute workflow’” node.

This will manually start the workflow.

2. Add Google Sheets Read Node

Drag Google Sheets → “Get row(s) in sheet”.

Connect it to the trigger.

Select spreadsheet + sheet.

(Optional) Add filters if needed.

3. Add IF Node

Drag IF node.

Connect the “Get row(s)” output to it.

Set condition (example: check if row exists).

4. Add Append Row (TRUE path)

Drag Google Sheets → Append Row.

Connect it to IF → TRUE output.

Select sheet and map fields.

5. Add Append Row (FALSE path)

Drag another Append Row node.

Connect it to IF → FALSE output.

Select different sheet (sheet1) and map fields.

6. Save + Execute

Click Save.

Run the workflow using Execute Workflow.





# screenshot

<img width="1389" height="591" alt="Screenshot 2025-11-21 115613" src="https://github.com/user-attachments/assets/2b23f2b9-6c63-40bf-8c45-d627621c754d" />
