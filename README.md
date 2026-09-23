# n8n Workflow Automation Portfolio

A collection of working n8n automation workflows demonstrating webhook integration, AI-assisted workflow orchestration, Google Sheets, Gmail, Jira, Google Gemini, Ollama, and Playwright test integration.

## Workflows

### 1. Playwright Webhook + Gemini

[My Workflow](workflows/My_workflow.json)

- Webhook trigger
- Basic LLM Chain
- Google Gemini Chat Model
- Demonstrates webhook-driven workflow processing

### 2. Google Sheets + Gmail + Jira AI Agent

[Google Sheets Workflow](workflows/google_sheet_worklow.json)

- Chat Trigger
- AI Agent
- Simple Memory
- Google Sheets
- Gmail
- Jira
- Google Gemini Chat Model
- Demonstrates AI-assisted orchestration across business tools

### 3. AI-QA Automated Bug Triage

[AI-QA Automated Bug Triage](workflows/AI-QA-Automated-Bug-Triage.json)

- Chat Trigger
- AI Agent
- Ollama Chat Model
- Simple Memory
- Google Sheets
- Jira
- Demonstrates AI-assisted QA defect triage and Jira issue creation

## Playwright + n8n Integration

The portfolio includes evidence of Playwright E2E test execution sending execution data to an n8n webhook and triggering downstream workflow processing.

## Screenshots

### Playwright + n8n

- [Test workflow executed](screenshots/test_E2EScenario%20workflow%20executed.png)
- [Webhook workflow executed](screenshots/webhook%20executed%20workflow.png)
- [n8n pipeline](screenshots/n8n%20pipeline.png)
- [Workflow executed](screenshots/workflow%20executed.png)

### AI-QA Bug Triage

- [AI-QA Automated Bug Triage](screenshots/AI-QA-Automated-Bug-Triage.png)
- [Jira bug created by n8n](screenshots/jira%20bug%20created%20by%20n8n.png)
- [Google Sheets output](screenshots/sheet3.png)
- [Missing user exception test](screenshots/missing%20user%20exception%20test.png)

### Email Automation

- [Email workflow](screenshots/my%20workflow.png)
- [Multiple emails sent](screenshots/multiple%20emails%20sent.png)
- [Delivered email](screenshots/delivered%20email.png)
- [Email sent successfully](screenshots/email%20sent%20successfully.png)

## Import Workflows

1. Open the local n8n instance at `http://localhost:5678`.
2. Import the required JSON workflow from the `workflows/` directory.
3. Recreate required OAuth/API credentials in the target n8n environment.
4. Execute the workflow and verify its nodes and outputs.

## Security

- Credentials and API secrets are not stored in the repository.
- n8n runtime data and SQLite databases are not committed.
- Imported workflows may require credentials to be recreated in the target environment.

## Technology

- n8n
- Python
- Playwright
- Webhooks
- Google Gemini
- Ollama
- Google Sheets
- Gmail
- Jira
