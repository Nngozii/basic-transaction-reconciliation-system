

# Basic Transaction Reconciliation System

An automated backend system for tracking transaction lifecycles and generating daily financial reconciliation reports.

## Overview
This service monitors transaction states (Pending, Success, Failed) and produces aggregated reports used for auditing and financial analysis.

## Key Features
- Transaction status tracking
- Automated daily reconciliation reports
- Scheduled background processing
- Efficient aggregation of large datasets

## Technical Highlights
- **Cron Jobs** for automated daily processing
- **Mongoose aggregation pipelines** for reporting and summaries
- Optimized queries for large transaction volumes

## Tech Stack
- Node.js
- Express.js
- MongoDB
- Mongoose
- Cron Jobs

## Getting Started
```bash
git clone 
cd transaction-reconciliation-shttps://github.com/Nngozii/basic-transaction-reconciliation-system.gitystem
npm install
npm run dev
