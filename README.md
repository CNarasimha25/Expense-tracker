# MERN Expense Tracker

This is a simple expense tracker built with MongoDB, Express, React (Vite), and Node.

## Quick start

1. Make sure you have Node.js (v18+) and MongoDB running locally or a MongoDB Atlas URI.
2. In `server/` create a `.env` from `.env.example` and set `MONGO_URI`.
3. Install and run server:
   ```bash
   cd server
   npm install
   npm run dev
   ```
4. Install and run client:
   ```bash
   cd ../client
   npm install
   npm run dev
   ```
5. Open http://localhost:3000

## Features
- Add / edit / delete expenses
- Categories and notes
- Summary totals by category
- Filter by date range (back-end supports `?from=YYYY-MM-DD&to=YYYY-MM-DD`)

## Extensions you might add
- Authentication (JWT + users)
- CSV export / import
- Charts (Chart.js / Recharts)
- Monthly budgeting & recurring expenses
