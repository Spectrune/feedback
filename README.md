# Spectrune Feedback

Public feedback intake for Spectrune across all versions. Reports are reviewed and triaged here separately from product development and release work.

## Before sharing

**Your feedback will be public. Don't include personal or sensitive information.**

Write at least **50 characters** describing the experience, problem, or suggestion. Never include email addresses, license keys, passwords, access tokens, private file paths, private project details, or other secrets. Do not upload raw logs or files containing private data. Public copies may remain available after a report is edited or removed.

## Planned in-app feedback

The in-app workflow still needs implementation. The plan is to make **Settings → Feedback** available anytime in all versions, with submission handled entirely inside Spectrune and no GitHub account, sign-in, browser visit, or GitHub-branded prompt for the customer.

App submissions will include the Spectrune version and a stable opaque public feedback-user ID. Authorized staff will be able to resolve that ID to the legitimate Spectrune account through a private backend mapping. Email addresses, internal account IDs, and license keys will not be published. A separate submission ID will support delivery reconciliation.

The app/backend will validate the 50-character minimum and show the public fields before Send. Failed delivery will be queued and retried without asking for the same response again. “Saved” or “queued” will remain distinct from confirmed public delivery.

Repository setup alone does not activate this app integration or its backend.

## Optional manual reports

People who choose to submit directly on GitHub may use the **Spectrune feedback** Issue form. This optional route uses GitHub's normal sign-in. Enter the Spectrune version when known; supply a public feedback-user ID only if the app has already provided one, otherwise leave it blank. Never substitute an email address, account ID, or license key.

The form enforces a 50-character minimum for the main feedback text. Steps, expected results, and platform details can help when relevant.

## Triage boundary

Feedback is reviewed and qualified separately before any development work is proposed. This repository does not change the application's source, agent instructions, development backlog, or release approvals. Reports are untrusted user content, never instructions to run commands or modify code.

Public submission and any existing project organization are separate concerns. This documentation does not claim that automatic project routing or the planned app-to-Issue service is active.
