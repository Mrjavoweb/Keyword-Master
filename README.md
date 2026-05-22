# Keyword Traffic Master

Deep keyword research fast with DataForSEO.

## What It Does

Keyword Traffic Master turns one seed keyword into a research dashboard. It pulls seed metrics, keyword suggestions, and related keywords from DataForSEO, then displays sortable metrics and CSV export tools.

## Setup Instructions

You need DataForSEO API credentials from https://dataforseo.com. Open the app, click the gear icon, enter your DataForSEO login email and API password, choose a default country if desired, then save.

## How to Run Locally

Open `index.html` in a browser. If browser file URL restrictions block API requests, run a simple static server from this folder.

## How to Deploy on Netlify

Drag this folder into Netlify, or connect this GitHub repo and publish from the repo root. No build command is required.

## Key Files

- `index.html` loads Tailwind, React, ReactDOM, Babel, and the root element.
- `App.jsx` contains the dashboard UI, DataForSEO Basic Auth calls, sorting, CSV export, settings, and partial-error handling.

## Customisation

Edit `App.jsx` to change supported countries, default location, table columns, result limits, colors, or CSV formatting.
