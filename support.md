# Support

**App:** Customer & Organization Import for Jira Service Management · **Publisher:** Atesen Software
**Email:** sametatesen2@gmail.com · **First response target:** 2 business days (Monday–Friday, Istanbul time, UTC+3)

## Before you write

1. Open **Job history** in the app and note the **job ID**.
2. Download the **results CSV**. You may delete the email column before sending it — job ID, status and error code are what we need.
3. Note whether the run was a dry run or a real run, and roughly how many rows it had.

## What to include

- Your site URL (`yoursite.atlassian.net`)
- Job ID and the error code shown (for example `API_403_ADMIN_REQUIRED`)
- What you expected to happen and what happened instead

## Severity and response

| Severity | Example | Target |
|---|---|---|
| S1 | The app wrote wrong data, or emails went out that you did not ask for | Same day acknowledgement, fix or in-app warning within 2 business days |
| S2 | Imports do not run at all | 3 business days |
| S3 | Question, or a feature request | Answered in the next weekly pass |

## Known limits

- Creating customers requires the **Jira Administrators** global permission. This is an Atlassian requirement, not an app setting.
- Up to **10,000 rows** per job. Split larger files.
- Atlassian rate limits can slow very large imports. The app waits and continues automatically.
- Job data, including result files, is deleted **30 days** after the job was created.
- The app works with Jira Service Management. It does not manage Customer Service Management (CSM) profiles.

## Updates

Releases are published through the Atlassian Marketplace with release notes. Minor updates install automatically; an update that requires new permissions needs a Jira administrator to approve it.

## Security reports

Email sametatesen2@gmail.com with the subject line **SECURITY**. We acknowledge within 2 business days and will tell you when a fix ships.
