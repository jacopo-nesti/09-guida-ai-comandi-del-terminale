# API del progetto — Guida ai comandi del terminale

## Panoramica

In questo progetto non viene utilizzata una vera API remota.

I dati vengono caricati da un file locale `data.json`, che simula il comportamento di una API.

Il file viene letto tramite JavaScript usando la Fetch API:

```js
fetch("data.json")
```

Il file `data.json` contiene oggetti con questi campi principali:

```text
id
 title
 subtitle
 category
 description
 fields
```