# ActionNPA Task Manager — Case Study

**Case study — no source code.** Built while employed at actioNPA; the
codebase is proprietary and not published here. This repository documents
what I built, for a portfolio/CV audience.

## What it does

A full-stack operations system for a jewelry & repair business, covering
the full order lifecycle:

- **Orders** — SKU-tracked customer orders with status, debt tracking
  (βενέτικο / ρευστό), photos, and notes
- **Repairs** — Repair-job tracking through a Greek-language workflow:
  Εκκρεμεί → Απεστάλη → Παραλήφθηκε → Παραδόθηκε / Ακυρώθηκε
- **Supplier debt ledger** ("Λοιπά") — PIN-protected, with future-debt
  support and completion tracking
- **Customer & supplier CRM** — contacts with full order/repair history
- **Audit log** — full change history, searchable by SKU
- **Live gold price ticker** — K9/K14/K18 prices pulled daily (07:00 Athens
  time) with material-damage markup applied
- **Gold price calculator** — karat + weight + labor → final retail price
  including VAT
- **PWA** — installable as a mobile app

## My role

Sole developer, end-to-end: schema design, backend, frontend, deployment.

## Stack

- **Backend:** PHP 8.1, MySQLi
- **Frontend:** Vanilla JS, Tailwind CSS
- **Database:** MySQL / MariaDB
- **Hosting:** shared PHP hosting (Hostinger)
