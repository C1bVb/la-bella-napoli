# La Bella Napoli — Template TPSIT

Sito statico realizzato soltanto con **HTML e CSS**. Non usa JavaScript.

## File principali
- `index.html`: contenuto del sito e 24 schede prodotto segnaposto.
- `style.css`: colori, disposizione, versione per cellulari e piccole animazioni.
- `assets/images/`: logo e immagini dei prodotti.

## Anteprima
Apri `index.html` in un browser.

## Lavoro degli studenti
Il sito è diviso in tre sezioni: **Pizze**, **Bibite** e **Dolci**.
Ogni studente modifica soltanto lo slot assegnato dal Project Manager.

Per ogni prodotto inserire:
1. nome;
2. breve descrizione;
3. prezzo;
4. immagine.

Per inserire un'immagine, caricala in `assets/images/` e sostituisci il riquadro segnaposto con:

```html
<img class="product-image" src="assets/images/nome-file.jpg" alt="Descrizione del prodotto">
```

Non modificare gli ID delle sezioni o le classi CSS senza accordarsi con il Project Manager.

## Nota per il Project Manager
Tutti gli slot sono in `index.html` per mantenere il progetto semplice e modificabile dal browser. Assegna a ogni studente uno slot preciso per ridurre i conflitti nelle Pull Request.
