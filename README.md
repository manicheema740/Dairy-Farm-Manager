# Dairy Farm Manager

A responsive and installable dairy-business management application for tracking livestock, milk production, farm operations, sales, expenses, and monthly performance.

Built as a Progressive Web App (PWA), Dairy Farm Manager works on desktop and mobile and keeps day-to-day records available on the device.

## Features

- **Livestock management:** Record cows, buffaloes, calves, parent relationships, values, status, and notes.
- **Animal sales:** Save the buyer, sale date, price, and sale notes while preserving the animal’s history.
- **Milk recording:** Enter morning and evening milk separately for every lactating animal. Daily, animal-level, and farm-wide totals are calculated automatically.
- **Financial balance:** Track opening cash, income, expenses, milk sales, animal sales, feed, medicine, labour, utilities, and other costs.
- **Breeding and health:** Maintain heat, service, pregnancy, calving, treatment, vaccination, medicine-withdrawal, and follow-up records.
- **Feed inventory:** Monitor stock, suppliers, unit costs, minimum quantities, and low-stock alerts.
- **Customers and milk sales:** Store customers, delivery quantities, rates, payment status, and outstanding balances.
- **Reports and smart tools:** Review milk and herd summaries, monthly totals, reminders, QR animal tags, and downloadable reports.
- **Backup and restore:** Export complete farm data and restore it on the same or another device.
- **Mobile-first PWA:** Touch-friendly navigation, responsive screens, offline support, and home-screen installation.
- **English and Urdu:** Switch between supported interface languages.
- **Correctable records:** Delete incorrect animal, milk, balance, sales, feed, health, breeding, and customer entries.

## Technology

| Area | Technology |
| --- | --- |
| Interface | React 19, TypeScript and CSS |
| Framework | Next.js 16 with Vinext |
| Build tooling | Vite 8 |
| Device storage | Browser storage / IndexedDB |
| Hosted persistence | Cloudflare D1-compatible worker endpoint |
| PWA | Web app manifest and service worker |
| Supporting tools | QR code generation and Drizzle ORM |

## Run locally

### Requirements

- Node.js `22.13.0` or newer
- npm

### Installation

```bash
git clone https://github.com/manicheema740/Dairy-Farm-Manager.git
cd Dairy-Farm-Manager
npm install
npm run dev
```

Open the local address displayed in the terminal.

### Commands

```bash
npm run dev       # Start the development server
npm run build     # Create and validate a production build
npm test          # Build and run automated tests
npm run lint      # Run code-quality checks
npm run start     # Start the production build
```

## Install on Android

1. Deploy the application to an HTTPS website.
2. Open it in Chrome on Android.
3. Open Chrome’s menu.
4. Select **Install app** or **Add to Home screen**.
5. Launch Dairy Farm Manager from the home screen.

## Data and backups

Farm records may be stored locally on the device. Clearing browser data, resetting the browser, or uninstalling without a backup can remove those records.

Before changing devices:

1. Open **Backup** in the application.
2. Export the complete backup file.
3. Keep the backup somewhere safe.
4. Import it on the new device.

Never commit real farm backups, customer information, passwords, API keys, or other secrets to this repository.

## Project structure

```text
app/                 Interface and application logic
public/              PWA manifest, service worker, icons and static files
worker/              Cloud worker and cloud snapshot endpoint
db/                  Database access and schema definitions
drizzle/             Database migrations
scripts/              Build, installation and validation scripts
tests/                Automated tests
.openai/hosting.json  Hosting and database-binding configuration
```

## Deployment

The maintained production build is hosted through ChatGPT Sites. Access may be restricted by the site owner.

[Open Dairy Farm Manager](https://abdul-rehman-website.royyard870.chatgpt.site)

## Security and privacy

This application can contain sensitive farm, customer, animal-health, and financial information. Keep operational backups secure and never place real business data in the source repository.

See [SECURITY.md](SECURITY.md) for reporting guidance.

## Contributing

Suggestions and improvements are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting changes.

## Project status

The application is under active development. Always make a backup before testing a new release with important farm records.
