# Mörk Mask — World Generator

A static, browser-based generator using the 16 tables from the *Mörk Mask* manuscript by SamuRyan Games. Fifteen tables are represented as data groups because the City Name Generator is constructed separately from three d30 columns.

## Publish with GitHub Pages

1. Sign in at https://github.com and create a new **public** repository named `mork-mask-generator`.
2. Choose **Add file → Upload files** and upload `index.html`, `style.css`, `app.js`, and `tables.json` from this folder **directly into the repository root**. Commit the changes.
3. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**. Select `main`, folder `/(root)`, and click **Save**.
4. Your site should appear at `https://YOUR-USERNAME.github.io/mork-mask-generator/` once GitHub finishes deploying.

## Features

- Weighted d100 or equal-probability rolls for the six World Generation tables.
- Weighted d20 rolls for Reputation and Ambition.
- Automatic two-result Hybrid combinations with no additional Hybrid results.
- City name generation from three d30 columns, optional modifier.
- Individual rerolls and locks, variable numbers of organizations and ongoing conflicts.
- Copy and print.
- No external scripts, analytics, accounts, or paid services.

## Notes

The site uses the table result names, not the full descriptive paragraphs. It currently generates one city, one criminal enterprise, one crime boss, one relationship, and one immediate crisis per world; additional organizations and conflicts are configurable. Reputation and Ambition are shown in a separate optional character section.

This project is an initial working version; test its output against the manuscript before public launch.
