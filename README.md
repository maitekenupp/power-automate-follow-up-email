# Scheduled Follow-Up Email Automation

This repository contains a sanitized Power Automate cloud-flow export for a scheduled follow-up process.

## What the flow does

1. Runs on a recurring schedule.
2. Reads follow-up records from an Excel table stored in SharePoint.
3. Checks each row to determine whether a follow-up is needed.
4. Creates Outlook draft emails for qualifying records.
5. Posts an adaptive card in Microsoft Teams for review and approval.
6. Sends the approved drafts and posts a summary to Teams.

## Connectors

- Excel Online (Business)
- Microsoft 365 Outlook
- Microsoft Teams

## Public portfolio version

This copy has been sanitized for public sharing. Personal and company information, email addresses, phone numbers, branding, SharePoint identifiers, file identifiers, table identifiers, and environment metadata were replaced with sample values.

Before importing or rebuilding the flow, configure your own:

- Power Automate connections
- SharePoint site and document library
- Excel workbook and table
- Email recipients and message content
- Teams recipient or channel
- Schedule and approval settings

The original private export should be retained separately because this public copy contains placeholders.

## Repository structure

- `manifest.json` — exported package metadata
- `Microsoft.Flow/flows/` — flow definition and connector mappings

