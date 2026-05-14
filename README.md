# TataConnect — Verified Housekeeper & Nanny Platform

A web-based job-matching platform connecting verified housekeepers and nannies with families in Cameroon.

## Project Structure

```
tataconnect/
├── index.html          ← Main application file
├── css/
│   └── style.css       ← All styles
├── js/
│   └── app.js          ← All interactivity
└── README.md
```

## How to Run

Simply open `index.html` in any modern web browser - no server or installation required.

> Double-click `index.html` → opens in Chrome, Firefox, Edge, or Safari

## Features

| Page | Description |
|------|-------------|
| Dashboard | KPI stats, recent workers, activity feed, city chart |
| Browse Workers | Search & filter workers by city, role, rating |
| Job Postings | Tabbed job listings with status management |
| Worker Profile | Full profile with skills, history, reviews |
| Verifications | Admin panel to approve/reject worker documents |
| Reports | Platform analytics and insights |

## Key Interactions

- **Sidebar navigation** — click any item to switch pages
- **Post Job button** — opens a modal form to create a job listing
- **Approve / Reject** — live verification queue updates
- **Search & Filter** — filter workers by name, city, or role in real time
- **Responsive** — works on mobile; hamburger menu on small screens

## Technology Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Fonts | Sora (headings), DM Sans (body) via Google Fonts |
| Icons | Unicode symbols (no external icon library) |
| Framework | None — pure HTML/CSS/JS, no build step required |

## Color Palette

| Name | Hex | Usage |
|------|-----|-------|
| Navy | `#1a2e4a` | Sidebar, hero background |
| Teal | `#1D9E75` | Primary buttons, verified badges, accent |
| Teal Light | `#E1F5EE` | Badge backgrounds, skill tags |
| Gold | `#e8a820` | Star ratings, secondary highlights |
| Red | `#e24b4a` | Notifications, error states |

## Next Steps (for full implementation)

1. **Backend** — Django or Node.js REST API
2. **Database** — PostgreSQL (users, workers, jobs, reviews)
3. **Authentication** — JWT-based login system
4. **Document Upload** — Cloud storage for ID verification
5. **SMS Notifications** — Twilio or Africa's Talking API
6. **Mobile App** — Flutter (Android-first for Cameroon)
7. **Mobile Money** — MTN MoMo / Orange Money payment integration

---

Built for the TataConnect capstone project — Cameroon, 2025.
