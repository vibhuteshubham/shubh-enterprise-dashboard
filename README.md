# Shubh Pvt Ltd — Sales & Employee Management (frontend demo, core build)

Run: open the folder in VS Code, right-click `login.html` → Open with Live Server (ES modules need http://, not file://).
Tests: `npm test` (Node 20+). Manual checklist: `tests/shubh-test-checklist.html`.

## Demo accounts (DEMONSTRATION ONLY — mock auth, NOT secure)
admin@shubh.demo / Admin@123 · manager@shubh.demo / Manager@123 · hr@shubh.demo / Hr@12345 · sales@shubh.demo / Sales@123 · viewer@shubh.demo / Viewer@123

## Included
Login, sessions with expiry, 5 roles with role-based nav and permission checks, dashboard KPIs (calculated from data), sales CRUD + search + CSV export,
employees (add/deactivate), attendance (duplicate prevention, working hours, attendance %), monthly targets, localStorage data layer with reset, dark mode, responsive layout.

## Not included yet
Chart.js charts, SheetJS Excel import/export, leave-request workflow, pagination, advanced filters, global search, salary field, audit logs, date-range selector.

## Production notes
localStorage is per-browser and not secure. Production needs a backend API, hashed passwords, server-managed sessions, server-side authorization and a PostgreSQL/MySQL database.

