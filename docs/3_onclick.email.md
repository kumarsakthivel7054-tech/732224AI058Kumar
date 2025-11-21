1. Add Trigger Node

Click “+”

Search Execute Workflow

Add node → When Clicking ‘Execute Workflow’

2. Add Form Node

Click “+”

Search Form Trigger

Add On Form Submission

Connect it to the Execute Workflow node.

3. Add Google Gemini Chat Model

Click “+”

Search Google Gemini Chat Model

Select your Gemini API Credentials.

No prompt here, just add the model.

4. Add AI Agent Node

Click “+”

Search AI Agent

Inside:

Set Goal / system prompt (what the agent should do)

Connect:

Input ← From Form Submission

Chat Model ← Google Gemini Model

5. Add Gmail Node

Click “+”

Search Gmail

Select Send Email

Map the AI Agent’s output to:

Subject

Body

Recipient email

6. Connect Everything

Final flow should look like:

Execute Workflow → Form Submission → AI Agent → Gmail (Send Message)
                     ↘ Google Gemini Model ↙

7. Save & Activate

Click Save

Click Activate Workflow


# screenshot
<img width="1370" height="565" alt="Screenshot 2025-11-21 115554" src="https://github.com/user-attachments/assets/047db9cd-f727-49d8-abb0-98f51b0a8ae4" />
