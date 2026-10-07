# ṢOMI — Property Services Marketplace

A mobile-first web app prototype that connects remote landlords with vetted local showing agents, property managers, and service pros (cleaning, handyman, repairs).

## Features
- **Three roles:** Landlord / Property Owner, Agent / Showing Pro, Service Pro
- **Landlords:** post showing and service requests, browse agents and property managers, review offers, boost bids
- **Agents:** live job feed, claim jobs, counter-offer
- **Service Pros:** job feed, room-by-room checklists, job progress tracking
- **In-app messaging** with offer and counter-offer cards
- Sign-up and background check onboarding flow

## Tech
A single self-contained `index.html` file: plain HTML, CSS, and vanilla JavaScript. No build step, no dependencies (fonts load from Google Fonts). All data is sample data held in memory, so nothing is saved between page loads.

## Run locally
Open `index.html` in any browser.

## Deploy with GitHub Pages
1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, pick **Deploy from a branch**, choose `main` and `/ (root)`, then save.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Status
Front-end prototype. Payments, escrow, background checks, and real accounts are mocked and would need a backend to go live.
