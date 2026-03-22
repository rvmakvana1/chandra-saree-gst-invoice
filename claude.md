# GST Invoice Generator

## Project Overview
A single-page GST invoice generator for Indian freelancers.
Fill in details → GST auto-calculates → Download as PDF.
Built in one HTML file. No login, no database, no backend.

## Tech Stack
- Single HTML file (HTML + CSS + JS — all in one file)
- jsPDF library (CDN — no installation needed)
- Deploy: Vercel

## Features to Build
1. Seller details — Business name, Address, GSTIN
2. Client details — Name, Address, GSTIN
3. Line items — Add/remove rows (Service, Qty, Rate, Amount)
4. GST rate selector — 0%, 5%, 12%, 18%, 28%
5. Auto calculation — Subtotal, GST Amount, Grand Total
6. Invoice number — Auto-generated (INV-2025-26-001)
7. Invoice date — Auto-filled, user can change
8. PDF download — One click, professional output
9. Theme — Blue and white, clean professional look

## Indian Context
- Currency always ₹ — never $ or USD
- Number format: ₹1,00,000 — not ₹100000
- Default GST rate: 18%
- GSTIN format: 22AAAAA0000A1Z5
- Date format: DD/MM/YYYY

## Rules
- Everything in ONE HTML file — no separate CSS or JS files
- No TypeScript, no React, no backend
- Keep code simple — add comments in English
- Mobile responsive not needed — desktop only