# Deploy su GitHub Pages

## File da caricare (tutti e 2 obbligatori)
- index.html
- app.js

## Passi

1. Vai sul tuo repository GitHub (hcs-crm)
2. Clicca "Add file" → "Upload files"
3. ELIMINA i vecchi file se presenti (index.html, crm.jsx)
4. Carica index.html e app.js
5. Commit changes
6. Settings → Pages → Branch: main → / (root) → Save
7. Aspetta 2 minuti → il CRM è live

## Dopo il deploy — collega Google Sheets

1. Importa hotel_crm_template.xlsx in Google Drive
2. Estensioni → Apps Script → incolla codice dal foglio setup
3. Distribuisci → App web → copia URL
4. Torna su GitHub → apri app.js → cerca APPS_SCRIPT_URL
5. Sostituisci "" con il tuo URL → Commit
