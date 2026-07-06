# ClearCycle AI

**Decision Intelligence Platform for Solid & Agricultural Waste Management in Tier-2/3 Karnataka**

Built for Google GenAI Exchange — Cohort 2 Hackathon.

## Live Prototype
See GitHub Pages link in repo settings / submission.

## Problem
Bengaluru's waste crisis gets all the attention and funding. Tier-2/3 cities (Hubli-Dharwad, Belagavi, Davangere, Ballari, Tumakuru) and the agricultural belts around them have almost no AI-driven waste analytics — despite rapid growth and significant crop-residue burning. Municipal staff currently manage collection routes, dumping-site load, segregation compliance, and agri-waste handling manually, with no real-time visibility — leading to overflowing collection points, poor segregation tracking, and crop residue being burned instead of processed.

## Solution
ClearCycle AI is a decision intelligence layer that gives municipal officers a live, AI-powered dashboard to act faster and smarter on waste data — instead of reacting after problems (overflow, illegal dumping, crop burning) have already happened.

## How It Solves the Problem
1. **Ingest** — Pulls in multi-source civic and agricultural data: IoT bin-fill sensors, satellite/FIRMS crop-burn signals, ULB (Urban Local Body) records, and citizen-reported complaints.
2. **Understand** — Gemini-powered natural language assistant (English + Kannada) lets non-technical municipal staff query the data directly ("Which wards have overflowing bins today?") instead of needing a data analyst.
3. **Predict** — Forecasts waste generation spikes (festivals, harvest season) and recommends optimized collection routes ahead of time, not after complaints pile up.
4. **Detect** — Flags anomalies automatically: illegal dumping hotspots and crop-residue burning events, using satellite burn data + civic reports.
5. **Decide** — Surfaces all of this as next-best-actions on a single dashboard, so a municipal commissioner can make a faster, better-informed decision instead of relying on guesswork or delayed manual reports.

## Core Features
- Multi-source data ingestion (IoT bins, satellite/FIRMS burn data, ULB records, citizen reports)
- Gemini-powered natural language assistant (English + Kannada)
- Waste generation forecasting & route optimization recommendations
- Illegal dumping & crop-burning anomaly detection
- Decision-support dashboard for municipal commissioners

## Tech Stack (Production)
Google Cloud: Vertex AI (Gemini API), BigQuery, Cloud Storage, Pub/Sub, Cloud Run, Firebase, Looker Studio

## This Repo
`index.html` — standalone prototype dashboard (KPIs, forecast chart, city hotspot status, AI assistant demo). Deployed via GitHub Pages.

## Author
Vishal Patil — [github.com/Vishal5977](https://github.com/Vishal5977)
