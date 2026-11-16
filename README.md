# Sentinel — Fraud Detection Frontend

A frontend-only React dashboard prototype for a fraud detection system. It includes six screens: Dashboard, Transactions, Analyse Transaction, Transaction Details, Model Performance, and Dataset Management.

## Run locally

Requirements: Node.js 18+ and npm.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (usually http://localhost:5173).

## Stack

- React + Vite
- Tailwind CSS
- Recharts
- React Router
- Lucide React icons

## Frontend-only scope

- Uses illustrative sample transactions and model metrics from `src/data.js`.
- The Analyse Transaction page applies simple browser-side demo rules. It is **not** an ML model and does not call FastAPI.
- Transaction details and SHAP-style feature bars are illustrative placeholders, not actual SHAP output.
- Dataset Management reads a selected CSV locally in the browser, checks its extension and counts rows. It does not upload or store the file.
- Export and notification actions are demo placeholders.

No Node/Express API, FastAPI service, database, authentication, model training, or deployment configuration is included. Replace the mock data and demo functions when your backend is ready.
