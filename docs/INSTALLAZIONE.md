# Installazione e Avvio del Progetto

Questa guida spiega come scaricare ed eseguire il progetto contenente la pagina `index.html`.

## 1. Scaricare il progetto

Apri il terminale e digita:

```bash
git clone https://github.com/jacopo-nesti/09-guida-ai-comandi-del-terminale.git
```

## 2. Entra dentro la cartella del progetto

```bash
cd 09-guida-ai-comandi-del-terminale
```

## 3. Avviare il server locale

```bash
python -m http.server 8000
```

### Se non funzionasse il precedente comando, prova

```bash
python3 -m http.server 8000
```

## 4. Nel browser

Apri il browser e visita:  

```text
http://localhost:8000
```

---


## Eventuali problemi con `fetch("data.json")`

Durante il caricamento dei dati tramite `fetch("data.json")` possono verificarsi dei problemi.  
Di seguito sono riportate le cause principali e le relative soluzioni.

---

### 1. File `data.json` non trovato

Se il file non si trova nella posizione corretta, il browser non riesce a caricarlo.

**Soluzione:**
- Verificare che `data.json` sia nella stessa cartella del file HTML
- Controllare che il nome del file sia scritto correttamente

---

### 2. Apertura del file HTML direttamente (`file://`)

Se il progetto viene aperto con un doppio click sul file HTML, `fetch` potrebbe non funzionare.

**Soluzione:**
Utilizzare un server locale, ad esempio:
- VS Code con estensione **Live Server**
- `python -m http.server`

---

### 3. JSON non valido

Se il file `data.json` contiene errori di sintassi, il caricamento fallisce.

**Soluzione:**
- Controllare parentesi, virgole e struttura del JSON