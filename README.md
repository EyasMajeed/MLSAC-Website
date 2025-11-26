## 📁 MLSAC Website Project Structure

```text
MLSAC-Website-Project
├── public/                 ← User-facing pages (HTML)
│   ├── index.html          — Homepage
│   ├── about.html          — About Us / Mission / Vision
│   ├── members.html        — Team List
│   └── events.html         — Events & Calendar
│
├── src/
│   ├── js/                 ← Vanilla JS logic
│   │   ├── main.js                 — General utilities
│   │   ├── supabase_client.js      — Supabase API initialization
│   │   ├── language.js             — English/Arabic switching logic
│   │   └── events_logic.js         — FullCalendar implementation
│   │
│   └── css/
│       └── styles.css      — Global website styling
│
├── .gitignore              — Excludes sensitive and temporary files
└── README.md               — Project documentation




