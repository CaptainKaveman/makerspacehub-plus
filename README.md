# MakerSpaceHub+

A campus makerspace equipment reservation and management prototype, built for **IT499: Bachelor's Capstone in Information Technology** at Purdue University Global.

## About

MakerSpaceHub+ replaces a manual whiteboard-and-sticky-note reservation system with a digital equipment reservation workflow for a university makerspace. This prototype demonstrates the core reservation cycle — a student browses available equipment, selects a time slot, and receives confirmation — while enforcing basic data validation along the way.

**This is a course prototype and is not intended for production use.** Authentication, database storage, and security controls are simulated for demonstration purposes only.

## Tech Stack

- HTML / CSS / JavaScript
- Browser `localStorage` for data persistence (no backend or real database)

## Core Workflow

1. **Login** (`index.html`) — placeholder login screen (no real authentication)
2. **Equipment Catalog** — browse available equipment and select an item to reserve
3. **Reservation Form** — enter a date and time slot; required fields are validated before submission
4. **Confirmation** — reservation details are saved to `localStorage` and displayed back to the user

## Pages

| File | Purpose |
|---|---|
| `index.html` | Placeholder login screen |
| `catalog.html` | Equipment catalog with search and equipment selection |
| `reservation.html` | Reservation form with date/time validation |
| `confirmation.html` | Displays the saved reservation, read back from `localStorage` |

## Running Locally

Clone the repository and open `index.html` in a browser — no build step or server required.

```bash
git clone https://github.com/<your-username>/makerspacehub-plus.git
cd makerspacehub-plus
```

Then open `index.html` directly in your browser.

## Project Status

Currently in the Prototype 2 stage: static UI, client-side validation, and localStorage persistence for a single end-to-end reservation workflow.

## Changelog

Dated entries below track major updates as the project evolves. Add a new entry above the previous one each time you make a significant change (new feature, styling pass, refactor, etc.).

- **2026-07-27** — Prototype 2 complete: added date/time validation, localStorage persistence for reservations, cross-page equipment selection, and formatted date/time display on the confirmation page.
- **2026-07-25** — Prototype 1 complete: static clickable HTML pages for Login, Catalog, Reservation, and Confirmation with fake navigation.
