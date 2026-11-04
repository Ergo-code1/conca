# Mensa La Conca Verde – pubblicazione

## 1. Firebase
1. **Firestore Database** già creato.
2. **Authentication > Metodo di accesso > Email/Password > Attiva.** Non serve creare utenti.
3. **Firestore > Regole**: incolla `firestore.rules` così com'è e premi **Pubblica**.
4. Configurazione Firebase già inserita in `index.html`.

## 2. GitHub Pages
1. Carica nel repository (pubblico): `index.html`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`, `favicon.png`.
2. **Settings > Pages**: branch `main`, cartella `/ (root)` > **Save**.
3. In Firebase: **Authentication > Settings > Domini autorizzati** > aggiungi `TUOUTENTE.github.io`.

## 3. Primo avvio (subito dopo la pubblicazione)
1. Apri il link, **Area admin**, utente `admin`, password `123`.
2. Scegli la tua password.
3. Tab **Utenti**: aggiungi dipendenti e ristoratore (spunta *Gestore* per chi deve gestire l'app). Ognuno entra con il suo nome utente e la password `123`, poi sceglie la sua.
