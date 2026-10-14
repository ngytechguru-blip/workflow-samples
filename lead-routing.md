# Lead Capture & Routing Workflow (Sample Structure)

A structure for getting new leads out of forms and inboxes and into the right person's hands quickly, with nothing left unchecked.

## The problem it solves
Leads arrive from forms, emails, and messages. Without a system, someone has to copy details into a tracker, check for duplicates, and decide who follows up. That manual add-and-check step is slow, and leads go cold while it waits. In one previous role, automating this step cut a lead add/check process from about an hour to about a minute.

## Workflow overview

| Step | Trigger | Automated action |
|------|---------|------------------|
| 1. Capture | Lead submits a form | Record created in Airtable or the CRM |
| 2. Duplicate check | New record created | Existing contacts searched; duplicates flagged |
| 3. Routing | Lead details complete | Lead assigned by service type or source |
| 4. Notification | Lead assigned | Owner alerted by email or internal message |
| 5. Follow-up task | Lead assigned | Follow-up task created with a due date |
| 6. Reminder | No activity after set time | Reminder sent to the owner |
| 7. Reporting | Weekly | Summary of new leads, status, and sources |

## Tools used
- Airtable or GoHighLevel: lead records and pipeline stages
- Make (or Zapier): routing and notification logic
- Google Forms / Sheets: capture and reporting
- Email notifications: alerts and reminders

## Design principles
- Every lead has one owner and a visible next step.
- Duplicates are caught before they create confusion.
- Follow-up reminders replace anyone having to remember.
- Each routing rule is tested with sample leads before going live.

## About
Built by Quinette, Executive Assistant & Business Operations Specialist.
[Upwork profile](https://www.upwork.com/freelancers/~01af2754fdab33ae10)
