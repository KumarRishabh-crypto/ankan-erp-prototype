# Aravli Crafts — Frontend Prototype

Responsive single-page frontend prototype for the Aravli Crafts integrated operations workspace.

## Run

### Option 1
Extract the ZIP and open `index.html` in a modern browser.

### Option 2 (recommended)
From this folder run:

```bash
python -m http.server 5500
```

Then open `http://localhost:5500`.

## Prototype credentials
- Username: `ANKAN`
- Password: `ANKAN@123`

## Important prototype behavior
- Sample/dummy data is included on first load so the workspace is not empty.
- On the first **real data save**, demo data is cleared and the workspace switches to live/local prototype data.
- Data entered in the prototype is persisted in browser `localStorage`.
- Use the browser's site storage controls to reset the prototype and reload the original dummy dataset.

## Current navigation
- Dashboard
- Orders
- Vendors
- Inventory
- Dyeing
- Designs
- Weaving
- Transport
- Finance (includes Purchases + Payments)
- Notifications
- Reports

Removed from navigation as requested: Services, Analytics, Approval Center, Audit Logs, Users & Roles, Master Data, Settings and the Administration section.

## New design / weaving registers
- **Designs:** Added a Design Application / Sampling Register with columns Dsg ID, Name, Size, Material, Sample Cost and Extra Details. The **Extra Details** button opens a modal containing the full material/vendor, dyeing colour, gross/net weight, sample-maker vendor, colour count, EPI/PPI, size breakdown, finishing, washing, loom type, sampling date and sampling-count fields from the provided specification.
- **Weaving:** Added a Production / Weaving Register with Order ID, Loom Memo, Dsg ID, Qty, Produced, Remaining, Start Date, End Date, Production %, Vendor ID and Status. Multiple rows can use the same Order ID for different designs.
- Both new registers have dedicated Add Entry forms containing the corresponding table fields.
