# FAQ - Domande Frequenti

## Il sito funziona senza internet?

No. Il sito necessita di una connessione internet attiva perché utilizza il caricamento dei dati tramite `fetch("data.json")`.

---

## Perché la pagina non si vede correttamente?
Controlla che `style.css` sia collegato correttamente in `index.html`.

---

## Perché i dati non compaiono?

I dati potrebbero non comparire per diversi motivi:
- Il file `data.json` non si trova nel percorso corretto
- Il file contiene errori di sintassi JSON
- Il sito è stato aperto senza un server locale

---

## Come modifico i contenuti del sito?

I contenuti si modificano direttamente nel file `data.json` oppure nelle pagine HTML (struttura) e CSS (estetica).
Dopo aver salvato le modifiche, è necessario ricaricare la pagina.

---

## Dove si trova il file dei dati?

Il file dei dati si trova nella cartella principale del progetto ed è chiamato: `data.json`
Se non viene trovato, controllare che il percorso indicato nel codice JavaScript sia corretto.

---

## A cosa serve il file `script.js`?

Il file `script.js` contiene la logica del sito.  
Si occupa di:
- Caricare i dati da `data.json` tramite `fetch`
- Gestire la visualizzazione dei contenuti nella pagina
- Eventuali interazioni con l’utente