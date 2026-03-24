# CSFC SQL Editor

A fully-featured, browser-based SQL editor that runs entirely client-side — no server, no installation, no login. Just open the HTML file and start writing SQL.

Built on [SQL.js](https://github.com/sql-js/sql.js/) (SQLite compiled to WebAssembly), so it works with real SQLite databases right in the browser.

## Features

### File Operations
- **New Database** — create a fresh empty SQLite database
- **Open .db** — load any existing SQLite `.db` file from your machine
- **Load .sql** — import and run a `.sql` script to build a database
- **Import CSV** — upload a CSV file and it becomes a queryable table instantly
- **Save .db** — download your current database as a `.db` file to keep or share
- **Export CSV** — download the current query results as a CSV

### Editor
- Full SQL editor with syntax-aware placeholder and `Ctrl+Enter` to run
- Clear editor button
- **Query History** — last 100 queries tracked per session, click any to reload it
- Execution time shown for every query

### Schema Viewer
- Live sidebar showing all tables and their columns
- Refresh button to update after schema changes

### UI
- **Dark / Light theme toggle** — smooth animated switch
- Responsive layout that fills the browser window
- Success / error / warning notifications
- Sample database to explore straight away

## How to Use

1. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari)
2. Click **Sample DB** to load an example and explore, or click **Open .db** to load your own
3. Write SQL in the editor and press **Ctrl+Enter** (or click **Run Query**)
4. Use **Save .db** at any time to download your work

## Use Cases

- Teaching SQL without any server or software setup
- Students writing and testing queries on their own machine
- Quick ad-hoc querying of any SQLite database
- Importing CSVs and exploring data with SQL

## Tech

- Pure HTML/CSS/JavaScript — zero dependencies beyond SQL.js loaded from CDN
- SQL.js 1.11.0 (SQLite via WebAssembly)
- JetBrains Mono + DM Sans (Google Fonts)
- No build step, no framework, no backend

---

## License

Copyright © Neil Southin. Free for personal use. Schools, colleges, and organisations wishing to use this in classrooms or on a VLE must get in touch first — see [LICENSE.md](LICENSE.md) for full details or email **southinn@colchsfc.ac.uk**.
