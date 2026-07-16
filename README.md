# FallMortgage v1.0.0 - mortgage case management 2026

> **FallMortgage is a browser-based mortgage case management tool delivered as one HTML file. It works offline with IndexedDB and gives brokers a local way to manage case records, audit history, and compliance tasks in version 1.0.0.**

[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/kevincole39/fallmortgage-record-hub?style=flat-square)](https://github.com/kevincole39/fallmortgage-record-hub)

---

<p align="center">
  <a href="https://kevincole39.github.io/fallmortgage-record-hub/">
    <img src="https://img.shields.io/badge/Download-FallMortgage%20Latest-brightgreen?style=for-the-badge" alt="Download FallMortgage">
  </a>
</p>

> **[Direct Download - FallMortgage v1.0.0](https://kevincole39.github.io/fallmortgage-record-hub/)**

---

[Download Latest Build](https://kevincole39.github.io/fallmortgage-record-hub/)

---

## Overview

FallMortgage is aimed at mortgage brokers and case managers who want a straightforward way to organize files without relying on a backend service. Everything runs in the browser, and the app keeps its data on the local device, which makes it a good fit for lightweight, self-contained workflows.

Its focus is everyday mortgage file handling: case records, supporting evidence, fee tracking, and compliance notes. It also provides structured audit history, built-in rule support, and browser-to-browser tab synchronization so teams can keep working against the same local data store while staying in the browser.

---

## Features

- Single-file HTML app with no server dependency
- Runs fully in the browser
- Offline-first storage powered by IndexedDB
- Local case record management for mortgage workflows
- ESIS snapshot generation for case documentation
- Suitability evidence signing support
- Procuration fee tracking
- Audit chain for recording changes over time
- BroadcastChannel sync for tab-to-tab updates
- Built-in compliance rules for CFPB, TRID, and MCD context
- BYOK AI Q&A support for guided assistance
- No telemetry included

---

## Installation

1. Download or clone the repository.
2. Open the main HTML file directly in a modern browser.
3. Allow the page to create local browser storage when prompted.

Example:

`git clone https://github.com/kevincole39/fallmortgage-record-hub.git

Then open the single HTML file in Chrome, Edge, or another browser with IndexedDB support.

---

## Usage

A common workflow looks like this:

1. Create a new mortgage case.
2. Add borrower, broker, and file details.
3. Record suitability evidence, fee information, and compliance notes.
4. Generate an ESIS snapshot when needed.
5. Review the audit chain to see what changed and when.
6. Keep the tab open for local sync across browser windows if you are working on the same device.

If you use the built-in AI Q&A, supply your own API key and follow that provider's usage policy.

---

## Configuration

Most configuration is stored in the browser and persisted through IndexedDB, so there is no server-side setup.

Common local settings can cover:

- case data and audit history
- compliance rule settings
- AI provider key entry for BYOK use
- browser sync state via BroadcastChannel

To reset the app, clear the site data in your browser settings and then reopen the HTML file.

---

## Requirements

- A modern browser with JavaScript enabled
- IndexedDB support
- Sufficient local storage for case records and history
- A device capable of opening a single HTML file locally
- Optional: an API key if you enable BYOK AI Q&A features

---

## FAQ

**Does FallMortgage need a backend?**  
No. It is meant to run locally in the browser without a server.

**Can I use it offline?**  
Yes. The app is offline-first and stores data locally through IndexedDB.

**Where is my data saved?**  
Data lives in the browser on the device where you use the app.

**How do updates work?**  
Download the latest build from the project page and replace the current file with the newer version.

**Why is my data missing after clearing the browser?**  
Because the app stores information locally, clearing site data will remove saved records.

**What if I need to customize compliance or AI features?**  
Check the local settings inside the app and configure the available options there.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
