# 🚚 Denser SCM Platform
### AI-Powered Global Logistics Comparison, Tracking & Analytics

Denser is a web-based, AI-enhanced logistics dashboard for comparing carriers, tracking shipments, drafting logistics communications, and viewing performance analytics. It uses TailwindCSS for UI, Firebase for backend services, and a generative AI API (e.g., Gemini) for recommendations and drafting.

---

## 🌟 Key Features

- Multi-carrier comparison with a weighted **Denser AI Score** (cost, speed, reliability)
- Shipment booking (stored in Firestore) with unique Denser Tracking IDs
- Universal tracking — enter a tracking ID to view status, carrier, ETA, and event timeline
- AI-driven document drafting (emails, customs descriptions, communications)
- Analytics dashboard: OTD rate, average cost, carrier scorecards, monthly trends

---

## 🛠️ Technologies

| Technology | Role |
|---|---|
| HTML5, TailwindCSS | UI & responsive layout |
| JavaScript (ES6 modules) | Client logic |
| Firebase Auth | Authentication |
| Firebase Firestore | Data storage (bookings, tracking) |
| Gemini / other AI API | Recommendations & drafting |
| Google Fonts (Inter) | Typography |

---

## 📁 Project Structure (suggested)

```
DENSER/
├─ index.html                # Main entry (static demo or SPA shell)
├─ src/
│  ├─ main.js                # App bootstrap and routing
│  ├─ api/
│  │  ├─ firebase.js         # Firebase init + helpers
│  │  └─ ai.js               # Calls to Gemini/AI API
│  ├─ components/            # UI components
│  └─ styles/                # Tailwind entry + custom CSS
├─ public/                   # Static assets
└─ README.md
```

Adjust the tree to match your repo if files differ.

---

## ⚙️ Setup & Run (local)

1. Install dependencies (if the project uses a package manager):

```powershell
# example for a Node-based build (if present)
npm install
```

2. Tailwind / build step (only if configured):

```powershell
npm run dev    # or your project's start/build command
```

3. For a quick static preview (no build system):

```powershell
# Windows: serve the folder using a simple server (Python example)
python -m http.server 5173; Start-Process http://localhost:5173
```

---

## 🔑 Environment / Secrets

This project requires credentials for Firebase and the AI API. Provide them via environment variables or a secure runtime config. Typical keys:

- `FIREBASE_API_KEY`
- `FIREBASE_AUTH_DOMAIN`
- `FIREBASE_PROJECT_ID`
- `FIREBASE_STORAGE_BUCKET`
- `GEMINI_API_KEY` (or whichever AI provider you use)

Do NOT commit secrets to the repo. Use a `.env` (excluded from git) or your CI environment secrets.

---

## 🧪 Demo / Notes

- The repo appears to contain a static `index.html` — open it locally for a visual demo, or follow the build steps above if a JS toolchain is present.
- Some features (AI recommendations, booking) require configured backend services (Firebase + AI key).

---

## 🤝 Contributing

If you'd like help improving docs, features, or tests, open an issue or a PR. Keep changes focused and add brief descriptions for reviewers.

---

## 📄 License & Contact

Include your project's license here (e.g., MIT) and contact details or a maintainer email.

---

If you'd like, I can:
- add a minimal `.env.example` and `.gitignore` for keys,
- add a short `CONTRIBUTING.md`, or
- run a quick spell/format check and commit the changes.
