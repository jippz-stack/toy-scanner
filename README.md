# Toy Drive phone pages

Served by GitHub Pages from `main`. Merging a pull request here publishes the pages (about a minute).

- `signup.html` – Wonder Box Outreach sign-ups. Pick a location (Haslet, Argyle), then:
  - **Wonder Box Inventory**: a leader types the location's passcode once to sign the phone in.
  - **Toy Inventory**: the toy passcode opens the toy scanner.
  - **Admin login**: the admin passcode shows the Wonder Box KPIs.
- `index.html` – the toy scanner (Quick add, Batch scan, Inventory). Open it from Toy Inventory on the sign-up page.

Both pages talk to each location's Google Sheet through its Apps Script web app link (`LOCATIONS` in each
page). The passcodes and API keys live only in each Sheet's **App Settings** tab and the private app code,
never in this public repo.
