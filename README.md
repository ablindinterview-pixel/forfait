# Forfait

Il calcetto del martedì. Pagina statica (`index.html`) con Firebase (Firestore + accesso con Google).

## Pubblicazione
1. Carica i file di questa cartella nella radice del repository (`index.html`, `icona.png`, `firestore.rules`, `README.md`).
2. GitHub: Settings → Pages → Branch `main`, cartella `/ (root)` → Save.
3. Firebase: Authentication → Impostazioni → Domini autorizzati → aggiungi `<utente>.github.io`.
4. Firebase: Firestore Database → Regole → incolla il contenuto di `firestore.rules` → Pubblica.

## Primo admin
1. Apri il sito, accedi con Google e crea il profilo. In fondo alla pagina Profilo c'è l'**ID account**.
2. Firebase: Firestore Database → Dati → Avvia raccolta → ID raccolta `admins` → ID documento = il tuo ID account → aggiungi un campo qualsiasi (es. `ok` = `true`) → Salva.
3. Ricarica il sito: ora sei admin.
