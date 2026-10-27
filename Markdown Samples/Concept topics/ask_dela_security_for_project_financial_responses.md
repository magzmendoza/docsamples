---
filename: ask_dela_security_for_project_financial_responses
publish_filename: ask_dela_security_for_project_financial_responses
---

# Ask Dela Security for Project Financial Responses

Ask Dela uses data from Project Report (PR) Summary table to generate both single-project and aggregate project financial responses.

## Access Control

Access to project financial data through Ask Dela is governed by existing report security.

A user is allowed to retrieve project financial data via Ask Dela **only if they have access to at least one** of the following reports, which source data from the PR Summary table.

- Office Earning Report
- Project Earnings Report
- Project Summary Report
- Performance Management: Top-Bottom Performers - Won Projects report

## Restricted Access Behavior

If a user does not have access to at least one of the reports listed above, Ask Dela **does not return** project financial data sourced from the PR Summary table.

## Ask Dela: Labor Cost Security

Labor cost security controls how labor cost information appears in project financial data. These settings protect sensitive cost details while ensuring that project-level spent and profit calculations remain accurate.

For project financial questions related to cost, burden spent, profit, or any aggregate or summary data, Ask Dela applies the following labor cost security rules:

What you can access depends on:

- Your labor cost access level
- Whether Include Cost in Spent & Profit Calculations is enabled

These are the different labor cost security access levels:

- **No Access:** Labor cost information is restricted at project and employee level in Ask Dela responses. If Include Cost in Spent and Profit Calculations is enabled, labor cost is included in overall spent and profit metrics. If disabled, labor cost is not included in these metrics.

- **Sub Totals Only:** Labor cost is included in project-level spent and profit metrics. Employee or resource-level labor cost information is restricted.

- **Final Totals Only:** Labor cost is included in project-level spent and profit metrics. Employee or resource-level labor cost information is restricted.

- **Full Access:** Labor cost is accessible at both the project level and employee or resource level, where applicable, and is reflected in spent and profit metrics.