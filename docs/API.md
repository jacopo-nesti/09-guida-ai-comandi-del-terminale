# API del progetto — Guida ai comandi del terminale

## Panoramica

In questo progetto non viene utilizzata una vera API remota.

I dati vengono caricati da un file locale `data.json`, che simula il comportamento di una API.

Il file viene letto tramite JavaScript usando la Fetch API:

```js
fetch("data.json")
```

---

## Contenuto JSON

Il file `data.json` contiene oggetti con questi campi principali:

{  
  "id": 1,  
  "title": "Titolo esempio",  
  "subtitle": "Sottotitolo esempio",  
  "category": "Categoria",  
  "description": "Descrizione del contenuto",  
  "fields": []  
  }

### Descrizione dei campi

- id → identificatore univoco dell’elemento
- title → titolo principale
- subtitle → eventuale sottotitolo
- category → categoria del dato
- description → descrizione
- fields → array con dati aggiuntivi