Step 1: Add Trigger Node

Click “+”

Search Execute Workflow

Add When Clicking ‘Execute Workflow’

Step 2: Add Form Node

Click “+”

Search Form Trigger

Add On Form Submission

Connect it to the Execute Workflow node.

Step 3: Add Google Gemini Chat Model

Click “+”

Search Google Gemini Chat Model

Select your Gemini API Credentials.

Do NOT add prompt here.

Step 4: Add AI Agent Node

Click “+”

Search AI Agent

Set Goal/System Prompt

Connect Input → Form Submission

Connect Chat Model → Google Gemini Model

Step 5: Add Gmail Node

Click “+”

Search Gmail

Choose Send Email

Map AI Agent output to: Subject, Body, Recipient Email

Step 6: Connect Everything
Execute Workflow → Form Submission → AI Agent → Gmail
Gemini Model connects to the AI Agent.

Step 7: Save & Activate

Click Save

Click Activate Workflow
# screenshot
<img width="1370" height="565" alt="Screenshot 2025-11-21 115554" src="https://github.com/user-attachments/assets/047db9cd-f727-49d8-abb0-98f51b0a8ae4" />
