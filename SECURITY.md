# Security Policy

## Supported version

Security updates are applied to the latest version on the `main` branch.

## Sensitive data

Dairy Farm Manager may process livestock, customer, animal-health, sales, and financial records. Do not include real operational data in public issues, pull requests, screenshots, test fixtures, or repository files.

Never commit:

- Farm backup files
- Customer names, phone numbers, or addresses
- Passwords, access tokens, API keys, or private URLs
- Production database exports
- Private financial or animal-health records

## Reporting a vulnerability

Do not open a public issue for a vulnerability that could expose data or allow unauthorized access.

Instead, contact the repository owner privately through their GitHub profile and include:

- A clear description of the issue
- Steps to reproduce it
- The possible impact
- A suggested fix, if available

Do not access, modify, or download data belonging to another person while testing.

## Device-storage warning

Some application records are stored on the device. Users should export regular backups and protect those files. Clearing browser storage or uninstalling the PWA without a backup may remove local records.
