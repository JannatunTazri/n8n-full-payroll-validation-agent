Full Payroll Validation Agent

An n8n workflow that compares worktime, absence, and payroll Excel files to automatically detect inconsistencies before payroll is finalized.

How it works

Send an email with [PAYROLL] in the subject and three Excel files attached. The workflow extracts the data, runs 16 Python validation rules across all three files, and renders an HTML report inside n8n showing every issue found with its severity and a correction suggestion.

All validation logic is deterministic Python. Google Gemini is used only for the human-readable summary.

Tech stack

n8n · Python · Google Gemini · Google Sheets · Gmail


Kimberton Oy AI Automation Internship — 2026
