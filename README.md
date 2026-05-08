# Food Mohalla POS

Backend-powered local POS for Food Mohalla with:

- same single-page POS interface
- Node.js backend
- file-based persistence
- KOT and bill printing
- day-wise reports
- discount support

## Files

- `index.html`: frontend POS interface
- `server.js`: local backend server
- `package.json`: start script
- `pos-data.sample.json`: sample database structure
- `pos-data.json`: live local POS data, ignored from Git

## Run locally

```powershell
npm start
```

Then open:

```text
http://localhost:3000
```

## GitHub upload

Upload these files to GitHub:

- `index.html`
- `server.js`
- `package.json`
- `.gitignore`
- `README.md`
- `pos-data.sample.json`

Do not upload:

- `pos-data.json`
- `node_modules`

## First setup on another PC

1. Install Node.js
2. Copy `pos-data.sample.json` to `pos-data.json`
3. Run `npm start`
4. Open `http://localhost:3000`
