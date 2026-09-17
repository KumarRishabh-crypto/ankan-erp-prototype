# ANKAN — Integrated Operations & Management System
Frontend-only, responsive enterprise ERP/operations prototype.

## Run
No build step is required.

1. Extract the folder.
2. Open `index.html` in a browser.
3. For the best experience, serve the folder with a local static server:
   - Python: `python -m http.server 5500`
   - Then open `http://localhost:5500`

## Included
- Responsive desktop/tablet/mobile UI
- Login + validation state
- Executive Operations Dashboard / Business Command Center
- Orders + order detail + complete journey timeline
- Global command-palette search
- Vendors + onboarding wizard
- Inventory / warehouse + material detail
- Purchases
- Dyeing
- Design & costing
- Production / weaving
- Transport
- Finance
- Services
- Approval center
- Notifications
- Audit logs
- Reports & analytics
- Reusable tables, KPI cards, badges, timelines, charts, modals and forms
- Prototype interactions: navigation, search, filtering, modal forms, approval action, onboarding steps, order tracking
- Fictional Indian business sample data and masked sensitive fields

## Architecture
This is intentionally plain HTML/CSS/JavaScript so the UI can be translated into Flask templates, static CSS/JS and a relational database later.

Files:
- `index.html` — application entry
- `assets/styles.css` — responsive design system
- `assets/app.js` — UI state, pages, sample data and prototype interactions

## Important
This is a frontend prototype. It does not persist data or connect to a backend/database.
