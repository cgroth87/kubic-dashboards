# kubic-dashboards
Kubic Transport Interstate &amp; Linehaul Dashboards

## Tools

- `kubic-fuel-levy.html` — fuel levy generator (data in `fuel-levy-data.json`, encrypted).
- `kubic-load-sheets.html` — carrier load order and proof of delivery generator. It has its own logins, separate from every other Kubic tool. Its logins, address book and history live encrypted in `load-sheets-data.json`, which the tool creates on first-time setup. PDFs are built in the browser with `vendor/pdf-lib.min.js`.
