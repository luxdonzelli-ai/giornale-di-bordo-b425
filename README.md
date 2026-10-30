# Giornale di Bordo B425 - PWA

## Avvio rapido su PC
Questa PWA richiede un server web, non aprire index.html con doppio clic.

### Test locale
1. Aprire un terminale nella cartella.
2. Eseguire: `python -m http.server 8080`
3. Aprire `http://localhost:8080`.

## Installazione reale su smartphone
Pubblicare tutti i file su un hosting HTTPS, ad esempio SharePoint static hosting se consentito dall'IT, Azure Static Web Apps, GitHub Pages aziendale o Netlify aziendale.

- Android/Chrome: aprire il sito e scegliere **Installa app**.
- iPhone/Safari: Condividi > **Aggiungi alla schermata Home**.

## Dati e sicurezza
I dati sono salvati nel localStorage del singolo browser/dispositivo. Fare periodicamente **Backup**. Non usare questa versione per dati HR sensibili o riservati senza approvazione IT. Per sincronizzazione multi-dispositivo serve un backend autenticato, ad esempio SharePoint/Microsoft Lists tramite Power Apps o Azure.
