# JOB

App per la gestione della fase commerciale: clienti e prospect, calendario di appuntamenti, contatti ed eventi, prodotti, ricerca per prodotti, task dei collaboratori e chiusura della giornata.

- Funziona da telefono e si installa come app (PWA). Funziona anche offline.
- **I dati restano solo sul telefono** (memoria del browser). Su GitHub c'è solo il programma, nessun dato.
- Il backup si fa con 💾 in home (EXPORT/IMPORT). Ogni domenica l'app chiede di scaricarlo.

## Pubblicazione su GitHub Pages
1. Crea un repository (es. `job`) e carica tutti i file di questa cartella.
2. Vai in **Settings → Pages**, scegli *Deploy from a branch*, branch `main`, cartella `/ (root)`, e salva.
3. Apri `https://<utente>.github.io/job/` da Chrome sul telefono, poi usa il menu ⋮ e **Aggiungi a schermata Home / Installa app**.

## Elenco prodotti
L'elenco è all'inizio di `index.html`, nella costante `PRODUCTS`. Per aggiungere un prodotto basta aggiungere una voce `{n:'NOME'}` nel punto giusto. Se rinomini un prodotto, gli stati già assegnati a quel prodotto si perdono.
