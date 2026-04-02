# 🏨 Domotica HCS — CRM Lombardia

CRM commerciale per la gestione delle trattative di domotica alberghiera in Lombardia.
Pipeline 5 stadi · Semaforo automatico · Google Sheets live · Import database Google Places

## ⚙️ Configurazione (una tantum)

1. Apri `crm.jsx`
2. Trova la riga: `const APPS_SCRIPT_URL = "";`
3. Incolla l'URL della tua Web App Google Apps Script

## 🚀 Funzionalità

- Pipeline Kanban 5 stadi (Lead → Contattato → Demo → Proposta → Chiuso)
- Semaforo automatico 🟢🟠🔴 con scadenza 15gg o data manuale
- Import .xlsx da Google Places Crawler
- Google Maps integrato (📍 Vedi su Maps · 🧭 Naviga)
- Sito web e foto struttura
- Salvataggio live su Google Sheets
- AI Report settimanale via Claude API
- Workflow n8n JSON per reminder Gmail + WhatsApp + Telegram

## 📊 Database

Importa `database_crm_pulito.xlsx` dal pulsante **Import XLSX** nel CRM.
Contiene 2.271 strutture target Lombardia: Hotel, RSA, Studentati, PA.

---
*HCS by Airvent · Baranzate (MI) · airventhcs.com*
