# Tuition Tracker 📊

A private, client-side web application designed to manage tutoring workflows, schedule tracking, and financial ledgers. Built entirely with vanilla web technologies, this tool operates independently of a backend server by utilizing secure local browser storage.

## Live Demo
[View the live application here](https://TechFM16.github.io/Tuition-Tracker/)

## Core Features
* **Zero-Backend Architecture:** Utilizes HTML5 `localStorage` to securely store student profiles, session logs, and financial data directly on the user's device.
* **Dynamic Weekly Matrix:** Automatically parses student time allocation data to generate a visual, responsive weekly schedule.
* **Automated Financial Ledger:** Calculates liquidations and outstanding balances instantly upon logging a new tutoring session.
* **Invoice Spooler:** Includes a mass-print module that generates and formats symmetrical, itemized fee invoices for selected time periods, optimized for paper printing.
* **Database Pipeline:** Features manual JSON export and restore capabilities to backup data or sync across multiple devices.

## Tech Stack
* **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6)
* **Storage:** Window.localStorage API
* **Deployment:** GitHub Pages

---
*Developed by Fahim Abrar*