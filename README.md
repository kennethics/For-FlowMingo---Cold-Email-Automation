# Flowmingo AI Cold Email Automation

Automated cold email outreach system built with n8n, Google Sheets, Gmail, and dynamic email templates.

## Business Problem

Manually sending cold emails is time-consuming and difficult to scale.

Teams often struggle with:

* Tracking outreach status
* Managing email templates
* Personalizing messages
* Monitoring sent emails

This workflow automates the entire cold outreach process while maintaining personalization.

---

## Workflow Architecture

```text
Schedule Trigger
        │
        ▼
Google Sheets (Lead List)
        │
        ▼
Filter Unsent Leads
        │
        ▼
Select Random Template
        │
        ▼
Personalize Subject & Body
        │
        ▼
Send Email via Gmail
        │
        ▼
Update Google Sheet
        │
        ▼
Wait & Continue
```

---

## Integrations Used

* Google Sheets
* Gmail
* JavaScript Code Nodes
* n8n Scheduler

---

## Expected Outcomes

✅ Automated cold email campaigns

✅ Dynamic template rotation

✅ Personalized messaging

✅ Outreach tracking

✅ Reduced manual work

✅ Consistent lead engagement

---

## Setup Instructions

1. Import workflow into n8n
2. Connect Google Sheets credentials
3. Connect Gmail credentials
4. Populate lead sheet
5. Create email templates
6. Activate workflow

---

## Download

[Flowmingo AI Cold Email Automation.json](./Flowmingo%20AI%20Cold%20Email%20Automation.json)

---

## Author

Kenneth Soriano

