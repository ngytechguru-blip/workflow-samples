# Client Onboarding Workflow (Sample Structure)

A reusable structure for taking a new client from first form submission to a completed onboarding, with automated handoffs and notifications at each step. It reflects how I set up onboarding systems with Airtable, Make, and Google Workspace.

## The problem it solves
Onboarding often depends on someone remembering to send the welcome email, update the tracker, and nudge the client for missing information. This workflow replaces that memory with a clear, automated sequence.

## Workflow overview

| Step | Trigger | Automated action |
|------|---------|------------------|
| 1. Intake | Client submits an onboarding form | Record created in Airtable |
| 2. Confirmation | New record created | Welcome email sent to the client |
| 3. Internal alert | New record created | Team notified with client details |
| 4. Task setup | New record created | Onboarding checklist generated |
| 5. Follow-up | Items still missing after set time | Reminder sent to the client |
| 6. Status update | Checklist items marked complete | Client record status updated |
| 7. Completion | All checklist items done | Final confirmation sent, record closed |

## Tools used
- Airtable: client records, checklist, and status tracking
- Make (or Zapier): automation between steps
- Google Forms / Sheets: intake and reporting
- Email notifications: client and internal messages

## Airtable structure (example)
- Clients table: name, contact details, service type, onboarding status, start date
- Checklist table: task, owner, due date, status, linked client
- Dashboard view: clients by onboarding stage, overdue tasks

## Design principles
- Every step has a clear owner and a visible next action.
- Information moves automatically, not through manual copying.
- Clients are never left waiting without a status update.
- Each automation is tested before it goes live.

## About
Built by Quinette, Executive Assistant & Business Operations Specialist.
Open to work: [Upwork profile](https://www.upwork.com/freelancers/~01af2754fdab33ae10)# Client Onboarding Workflow (Sample Structure)

A reusable structure for taking a new client from first form submission to a completed onboarding, with automated handoffs and notifications at each step. It reflects how I set up onboarding systems with Airtable, Make, and Google Workspace.

## The problem it solves
Onboarding often depends on someone remembering to send the welcome email, update the tracker, and nudge the client for missing information. This workflow replaces that memory with a clear, automated sequence.

## Workflow overview

| Step | Trigger | Automated action |
|------|---------|------------------|
| 1. Intake | Client submits an onboarding form | Record created in Airtable |
| 2. Confirmation | New record created | Welcome email sent to the client |
| 3. Internal alert | New record created | Team notified with client details |
| 4. Task setup | New record created | Onboarding checklist generated |
| 5. Follow-up | Items still missing after set time | Reminder sent to the client |
| 6. Status update | Checklist items marked complete | Client record status updated |
| 7. Completion | All checklist items done | Final confirmation sent, record closed |

## Tools used
- Airtable: client records, checklist, and status tracking
- Make (or Zapier): automation between steps
- Google Forms / Sheets: intake and reporting
- Email notifications: client and internal messages

## Airtable structure (example)
- Clients table: name, contact details, service type, onboarding status, start date
- Checklist table: task, owner, due date, status, linked client
- Dashboard view: clients by onboarding stage, overdue tasks

## Design principles
- Every step has a clear owner and a visible next action.
- Information moves automatically, not through manual copying.
- Clients are never left waiting without a status update.
- Each automation is tested before it goes live.

## About
Built by Quinette, Executive Assistant & Business Operations Specialist.
Open to work: [Upwork profile](https://www.upwork.com/freelancers/~01af2754fdab33ae10)
