# Cluso Investor Dashboard — Portfolio Demo

A live, interactive demo of the internal & investor-facing dashboard I built for [Cluso](https://mycluso.com) during my internship.

> ⚠️ This is a portfolio piece. All numbers shown are illustrative sample data — not real Cluso financials.

## What it shows

- **Investor-facing overview** — ARR, runway, LTV:CAC, gross margin, customer growth, and other key SaaS metrics
- **Internal team views** — Targets, Key Projects, monthly / quarterly performance, year-on-year comparisons
- **Role-based access** — three distinct experiences (Admin, External Viewer, Investor)
- **Integrations** — configurable Resend-powered email digest, Slack notifications, Gemini AI chat (UI shown; real API disabled in this demo for security)

## Stack

- Single-file HTML / CSS / vanilla JavaScript
- Chart.js for visualisations
- In production: Supabase (auth + Postgres + Edge Functions) and Vercel
- This demo runs entirely client-side on hardcoded sample data — no backend, no API calls

## About

Built by Emma Trippett during her internship at Cluso.
