# Security Policy

## Reporting a problem

If you find a security issue in this project, for example a way the workflow could expose email content or credentials, please do not open a public issue. Email **osazuwamichealkelvin@gmail.com** with a short description and the steps to reproduce it. You will get a reply as soon as possible.

## What this repository contains

- An n8n workflow export with credentials, workflow IDs, Slack username and Gmail label IDs removed.
- Documentation and screenshots with personal details removed.

No API keys or tokens should ever be committed. If you spot one, please report it.

## If you run this workflow

- Create your own Gmail, Slack and Gemini credentials inside n8n. Never paste keys into the workflow file.
- Email text is sent to the Gemini API for analysis. Only run it on mailboxes you own or have consent to process.
- Keep your n8n instance updated and protected with a strong login. Do not expose it to the internet without authentication.
- Rotate your API keys if you think they were exposed.
