Step 1: Add the trigger node “When clicking ‘Execute workflow’”.
Step 2: Add Google Sheets → “Get row(s)” and connect it to the trigger.
Step 3: Choose spreadsheet and sheet.
Step 4: Add IF node and connect it to “Get row(s)”.
Step 5: Set the IF condition (example: row exists).
Step 6: Add Append Row node for TRUE path and map fields.
Step 7: Add Append Row node for FALSE path and map fields.
Step 8: Save the workflow.
Step 9: Click Execute Workflow to run.


# screenshot

<img width="1389" height="591" alt="Screenshot 2025-11-21 115613" src="https://github.com/user-attachments/assets/2b23f2b9-6c63-40bf-8c45-d627621c754d" />
