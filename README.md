# Daily-Operations-Automation
Automated operations reporting workflow 
INPUT
Employee sends daily operational message
        ↓
PROCESS
n8n receives and processes the message
        ↓
EXTRACT
AI identifies relevant operational fields
        ↓
STRUCTURE
Information is converted into structured data
        ↓
VALIDATE
Data is checked and prepared for recording
        ↓
OUTPUT
Google Sheets is automatically updated

                ┌─────────────────────┐
                │ Employee            │
                │ WhatsApp Message    │
                └──────────┬──────────┘
                           ↓
                ┌─────────────────────┐
                │       n8n            │
                │ Workflow Automation  │
                └──────────┬──────────┘
                           ↓
                ┌─────────────────────┐
                │ AI / LLM Processing  │
                │ Data Extraction      │
                └──────────┬──────────┘
                           ↓
                ┌─────────────────────┐
                │ Structured Data      │
                │ & Validation         │
                └──────────┬──────────┘
                           ↓
                ┌─────────────────────┐
                │   Google Sheets      │
                │ Daily Operations     │
                └─────────────────────┘
