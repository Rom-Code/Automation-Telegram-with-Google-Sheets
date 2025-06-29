# Automation-Telegram-with-Google-Sheets
Automation project with n8n

A simple automation project using n8n.

The workflow receives text or voice from telegram chatbot, 
pulls the information from a short Titanic dataset in a google sheet. 

The workflow is able to update iny column in the dataset.

OpenAI chat model used: gpt-4-mini for text

The project contains:
1- main workflow called "My_workflow"
2- a sub workflow to lookup in a google sheet called "row_lookup"
3- a second sub workflow using MCP protocol to update the google sheet.
