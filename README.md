# Slack-to-Spiceworks-Automation

## Project Overview
I built a custom IT Support intake system that connects Slack to Spiceworks Cloud via the Gmail API. This automation ensures all IT requests are captured with consistent metadata (like Asset Tags) rather than being lost in chat threads.

## Technology Stack
* **Slack Workflow Builder**: To create the user-facing intake form.
* **Google OAuth2 / Gmail API**: To securely bridge Slack to our email-based ticketing system.
* **Spiceworks Cloud**: The final destination where tickets are managed.

## Features
* **Standardized Intake**: Forces users to provide an Asset Tag/Laptop ID before submitting.
* **Automated Ticket Creation**: Instantly generates a Spiceworks ticket (e.g., Ticket #3) upon form submission.
* **Zero-Code Integration**: Leveraged cloud connectors to build a reliable enterprise-grade workflow.

## Business Impact
* **Efficiency**: Reduced the time taken to log a ticket by 50% for Slack users.
* **Data Accuracy**: Guaranteed that 100% of tickets arrive with the correct hardware ID for faster troubleshooting.
