📌 Project Overview

This project is a News Website where users can:

See the latest news headlines (static demo, can later be connected with an API).

Navigate through different categories (Technology, Sports, Politics, Entertainment, etc.).

Search for news articles.

Responsive design (works on mobile and desktop).

⚙️ Working of the Project

HTML → Creates the structure of the website (navbar, sections, news cards).

CSS → Styles the website (colors, layout, responsive grid).

JavaScript → Handles category switching and searching through dummy articles.

Later, it can be connected to a live News API for real news.

1) Configuration (HTML/CSS/JS)

This guide gives you everything you need to build, understand, configure, test, and deploy a responsive News website using HTML, CSS, and JavaScript. It includes:

Step‑by‑step setup (no frameworks required)

Clean, responsive starter code (static demo)

How it works (data flow + UI flow)

Optional: connect to a real News API safely

Performance, accessibility, SEO, PWA notes

Testing, deployment, troubleshooting, and roadmap

2) What you’ll build

A responsive News site with:

A top navbar (logo, category filters, search bar)

Cards layout for articles (image, title, description)

Client‑side category filtering + text search

Mobile‑first design

Live data later: You can plug in a News API via a small server (for API‑key security and CORS), or keep it fully static.

3) Project structure
news-website/
├─ index.html
├─ style.css
├─ script.js
├─ assets/
│  └─ placeholder.jpg (optional images)
└─ server/               (optional — only for real API)
   ├─ server.js          (Express proxy)
   └─ .env               (API keys)

4) How it works (flow & logic)
UI & Data Flow (static)
User actions (click category / submit search)
        │
        ▼
script.js updates state: { category, query }
        │
        ▼
getFiltered() computes filtered list from newsData
        │
        ▼
renderCards() → builds article card HTML → injects into #news-container
Key functions
   
5) Prerequisites

Any modern browser (Chrome/Edge/Firefox/Safari)

A code editor (VS Code recommended)

Optional (for live API): Node.js 18+ and npm

Optional (local dev convenience): VS Code Live Server extension or npx serve

Done 

thank you...
