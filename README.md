# Slack-to-Spiceworks-Automation

## Project Overview
As it is impractical for users to log into a ticketing system every time they have an issue I therefore built a IT helpdesk request form on Slack in which the users fills out and that automatically creates a ticket to Spiceworks Cloud via the Gmail API. This automation ensures all IT requests are captured with consistent metadata (like Asset Tags) rather than being lost in chat threads.

## Technology Stack
* **Slack Workflow Builder**: To create the user-facing intake form.
* **Google OAuth2 / Gmail API**: To securely bridge Slack to our email-based ticketing system.
* **Spiceworks Cloud**: The final destination where tickets are managed.

## Features
* **Standardized Intake**: Forces users to provide an Asset Tag/Laptop ID before submitting.
* **Automated Ticket Creation**: Instantly generates a Spiceworks ticket (e.g., Ticket #3) upon form submission.
* **Zero-Code Integration**: Leveraged cloud connectors to build a reliable enterprise-grade workflow.


![Slack Request Form](https://github.com/shazi1997/Slack-to-Spiceworks-automation/raw/main/slack%20request%20form.jpg)

## Filling out the form
After the user fills out this form, on spiceworks under ticket rules, I ensured that certain key phrases automatically set the ticket to high priority. These phrases include: emergency, critical, down or urgent.

![Spiceworks Ticket Rules](spiceworks%20ticket%20rules.jpeg)
