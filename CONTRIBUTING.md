# Contributing to Dairy Farm Manager

Thank you for helping improve Dairy Farm Manager.

## Before starting

- Check existing issues before opening a new one.
- Keep changes focused on one feature or fix.
- Never include real farm records, customer information, backups, credentials, or API keys.
- Preserve mobile usability, offline behavior, and existing data compatibility.

## Development setup

```bash
git clone https://github.com/manicheema740/Dairy-Farm-Manager.git
cd Dairy-Farm-Manager
npm install
npm run dev
```

## Quality checks

Before submitting a change, run:

```bash
npm run lint
npm test
```

Also test the affected screens on both desktop and a narrow mobile viewport. For changes involving stored data, confirm that existing records still load and that backup export/restore continues to work.

## Pull requests

A good pull request should:

1. Explain what changed and why.
2. Stay limited to one logical improvement.
3. Include screenshots for visible interface changes.
4. Describe the checks performed.
5. Mention any effect on locally stored or cloud-synced data.

Use clear commit messages such as:

```text
feat: add animal weight history
fix: correct evening milk totals
docs: improve mobile installation guide
```

## Reporting bugs

Include:

- Device and browser
- Steps to reproduce the problem
- Expected and actual results
- Screenshot or screen recording when useful
- Whether the app was installed as a PWA

Remove all private farm and customer information before sharing screenshots or backup samples.
