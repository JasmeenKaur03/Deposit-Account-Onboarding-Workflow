# Deposit Account Onboarding Workflow Tracker | Harwell Financial
**Tool:** Microsoft Excel | **Duration:** July 2025 | **Domain:** Banking Operations / Retail Deposits
 
---
 
## Overview
 
This project models an end-to-end deposit account onboarding workflow for a retail bank. It tracks each stage of a customer application from document submission through KYC verification, account creation, and welcome communication — measuring performance against a 48-hour SLA target and producing an operations dashboard.
 
---
 
## Business Problem
 
Retail banks process hundreds of new deposit account applications each month. Without a structured workflow tracker, processing delays, SLA breaches, and incomplete KYC checks go undetected until they escalate. This tracker was designed to give operations teams full visibility over application status, processing times, and compliance at every stage.
 
---
 
## What the File Contains
 
**Sheet 1 — Application Register**
A register of 25 deposit account applications for July 2025 across five account types: Easy Access Savings, Fixed Term Deposit, Notice Account, 95-Day Notice, and 180-Day Notice. Each application tracks:
- Document submission status (Complete / Incomplete / Pending)
- KYC verification status (Verified / Failed / In Progress)
- Account creation status (Yes / No / Pending)
- Welcome email sent (Yes / No / Pending)
- Assigned officer and overall application status
 
Colour-coded status flags across all process stages for instant visual triage.
 
**Sheet 2 — SLA Tracker**
Tracks processing time for each application against the 48-hour SLA target. Shows date received, SLA deadline, date completed, hours taken, whether SLA was met, and breach reason for any overdue applications. Enables identification of recurring bottlenecks (e.g., KYC delay, incomplete documents).
 
**Sheet 3 — Dashboard Summary**
An operations dashboard featuring:
- KPI cards: Total Applications, Completed, In Progress, On Hold / Rejected, SLA Compliance Rate, Average Processing Time (hours)
- Breakdown by account type showing application count, completions, SLA met, and completion rate
- All figures update dynamically from Sheets 1 and 2
 
---
 
## Key Formulas Used
 
- COUNTIF / COUNTIFS — application count by status and account type
- Cross-sheet referencing — Dashboard pulls live data from Application Register and SLA Tracker
- IFERROR — handles zero-division in completion rate calculations
- Conditional Formatting — green/amber/red/blue status coding across all process stages
 
---
 
## Key Findings
 
- SLA compliance rate and average processing time calculated dynamically in Dashboard
- KYC Delay and Incomplete Documents are the two most common breach reasons
- Fixed Term Deposit and Notice Account applications show the longest average processing times
- On Hold applications are concentrated where KYC status returned as Failed
 
---
 
## Skills Demonstrated
 
Workflow-based processing | SLA compliance tracking | Document validation | Account lifecycle management | Operational KPI reporting | MS Excel (COUNTIFS, cross-sheet references, Conditional Formatting)
 
---
 
## How to Use
 
1. Open the file in Microsoft Excel
2. Sheet 1 shows the full application register with status at every stage
3. Sheet 2 shows SLA performance — filter by SLA Met = No to identify breach cases
4. Sheet 3 Dashboard updates automatically and provides the operations summary
 
