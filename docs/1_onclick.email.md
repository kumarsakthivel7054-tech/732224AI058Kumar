Step 1: Add Trigger Node

Click +

Search When chat message received

Add the node
(This starts the chat)

Step 2: Add AI Agent Node

Click +

Search AI Agent

Add the node

Connect Trigger → AI Agent

Step 3: Add Google Gemini Model Node

Click +

Search Google Gemini Chat Model

Select your Gemini API credentials

Do NOT add a prompt here

Connect Gemini → AI Agent in the “Chat Model” input

Step 4: Configure AI Agent
Inside the AI Agent:

Add Goal / System Prompt

Set chat flow options

Enable memory if needed

Tools if needed
Inputs should be:

Input → Trigger

Chat Model → Gemini Model

Step 5: Add Output Node

Click +

Search Send Message OR Respond to Chat

Add it

Connect AI Agent → Output Node

Step 6: Test the Workflow

Click Open Chat

Send a message

Check if AI responds correctly

Step 7: Save & Activate

Click Save

Turn workflow ON

#Screenshort
<img width="1246" height="587" alt="Screenshot 2025-11-21 115542" src="https://github.com/user-attachments/assets/72ca346a-1fc6-4258-a8bb-53a655009488" />



