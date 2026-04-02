# 🚀 Deploy su GitHub Pages — 3 passi

## PASSO 1 — Crea repository su GitHub

1. Vai su https://github.com/new
2. Nome repository: `hcs-crm`
3. Visibilità: **Private** (consigliato) o Public
4. Clicca **Create repository**

## PASSO 2 — Carica i file

Nella pagina del repository appena creato:
1. Clicca **"uploading an existing file"**
2. Trascina questi 3 file:
   - `index.html`
   - `crm.jsx`
   - `README.md`
3. Clicca **Commit changes**

## PASSO 3 — Attiva GitHub Pages

1. Vai su **Settings** (in alto nel repository)
2. Clicca **Pages** nel menu a sinistra
3. Source: **Deploy from a branch**
4. Branch: **main** · Folder: **/ (root)**
5. Clicca **Save**

Dopo 2-3 minuti il CRM sarà live su:
👉 `https://TUO_USERNAME.github.io/hcs-crm/`

---

## ✅ Poi configura Google Sheets

1. Importa `hotel_crm_template.xlsx` in Google Drive
2. Apri come Google Sheet
3. Estensioni → Apps Script → incolla il codice dal foglio "⚙️ Setup Apps Script"
4. Distribuisci → Nuova distribuzione → App web → Copia URL
5. Apri `crm.jsx` su GitHub → matita (edit) → sostituisci `const APPS_SCRIPT_URL = ""`
   con `const APPS_SCRIPT_URL = "https://script.google.com/macros/s/TUO_ID/exec"`
6. Commit changes → il CRM si aggiorna automaticamente in 1 minuto

