# Changelog

## 1.1.0 — 2026-11-04
- Nome utente automatico: prime tre lettere del nome + prime tre del cognome (es. Mario Rossi → marros), con numero se già usato. Password iniziale 123.
- Gestori: «Reimposta password» riporta la password a 123 (al primo accesso va cambiata) e «Togli accesso» nella scheda Utenti, senza passare dalla console Firebase.
- Richiede le nuove regole Firestore (raccolta logins).

## 1.0.1 — 2026-11-04
- Installazione: identità, ambito e service worker propri (id/scope /conca/) per non confondersi con Ergo Plan.
- Pulsante «Installa l'app sul telefono» (Android/Chrome) e istruzioni per iPhone in «Il mio account».

## 1.0.0 — 2026-11-04
Prima versione pubblicata.
- Accesso con nome utente e password (123 al primo accesso, poi cambio obbligatorio); l'accesso resta attivo sul dispositivo.
- Prenotazione dei piatti per giorno, in azienda o al ristorante; nome collegato all'utente; scelte salvate e modificabili fino alla chiusura.
- Presenza/assenza: assenza segnabile fino a fine giornata; ritorno a presente solo entro la chiusura prenotazioni.
- Gestori: modificano tutto in qualsiasi momento, prenotano per conto di chiunque, danno i permessi di gestore ad altri.
- Settimane: preparazione anticipata, pubblicazione/ritiro del menù, scadenza a giorni prima o giorno fisso.
- Portate modificabili (rinomina, ordine, aggiunta, eliminazione); piatti modificabili (nome e portata); nuovo piatto per tutti i giorni o nessuno.
- Riassunti per giorno raggruppati in azienda, ristorante e disdetti.
- Riepilogo giorno/settimana/mese in PDF o Excel, con invio tramite WhatsApp, Mail o download.
- Grafica ottimizzata per smartphone, logo e icona La Conca Verde, installabile sulla schermata Home.
