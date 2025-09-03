🛒 Smart POS Inventory

Smart POS Inventory is a monorepo built with Nx
 and Angular 20
.
It is designed as a price and inventory management module for point-of-sale (POS) systems.

🚀 Main Technologies

Nx — Monorepo toolchain

Angular 20 — Frontend framework

TypeScript — Main language

SCSS — Stylesheets

Jest — Unit testing

Playwright — End-to-end testing

GitHub Actions — CI/CD

📂 Monorepo Structure

smart-pos-inventory/
├─ apps/
│  └─ frontend/     → Main Angular application
├─ libs/            → Shared libraries (future)
├─ tools/           → Nx scripts
└─ .github/         → CI/CD workflows

⚡ How to Run the Project
Clone the repository and navigate to the directory:
git clone https://github.com/AnHernandezOlvera/smart-pos-inventory.git
cd smart-pos-inventory

Install dependencies:
npm install

Start the frontend:
npx nx serve frontend

Then open your browser at: http://localhost:4200

🌟 Project Status

🔹 Initial setup completed.
🔹 Next steps: add backend (Node/AWS Lambda) and shared libraries.

✨ Author

Created by Anahí Hernández Olvera
📌 Part of AWS re/Start program and personal portfolio.