# AHIS RRIT — Resource Room Inventory Tracker

A web app for **Avalon Heights International School** that tracks what teachers take from the school resource room.

Built by Team Orchid for the school hackathon.

## Features
- Teacher and Admin sign-in with school email (students are blocked)
- Two stores: **Ground Floor** and **First Floor**, with a **Mixed** view
- Every item is **Issue** (keep) or **Borrow** (must return)
- Take up to 5 of an item directly; more than 5 needs admin approval
- "Borrowing accepted" / "Issuing accepted" approvals
- Return dates for borrowed items, with automatic **overdue alerts** to the admin
- Returns and damage reports (Good / Damaged / Broken)
- Admin dashboard: stock levels, low-stock alerts, notifications
- Inventory management with photos, categories, colours and sizes
- Usage history with spreadsheet (CSV) download
- Light and dark mode; works on phones and laptops

## Built with
- HTML, CSS and JavaScript (single file: `index.html`)
- Firebase Authentication and Cloud Firestore
- Hosted on Netlify

## Files
- `index.html` — the whole app
- `firestore.rules` — database security rules (Firebase → Firestore → Rules)
