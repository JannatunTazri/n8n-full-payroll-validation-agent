Project 2 — Full Payroll Validation Agent
A rule-based payroll reconciliation system that compares worktime, absence, and payroll data to detect inconsistencies before payroll is finalized. Python handles all validation logic. The LLM only writes human-readable summaries.
Checks include: missing hours, overtime mismatches, duplicate entries, negative hours, inactive employees with payroll rows, absence conflicts, invalid dates, missing cost centers, and more.
Output: HTML report saved to Google Drive + Google Sheets audit log.
Tech: n8n, Google Gemini, Google Drive API, Gmail API, Python

Setup

n8n instance (cloud or self-hosted)
Google account with Gmail, Drive, Docs, and Sheets APIs enabled
Google Gemini API key
OAuth2 credentials configured in n8n

Emails must have [PAYROLL] in the subject and .xlsx or .csv attachments to trigger the workflow.

Built during AI automation internship — May 2026
