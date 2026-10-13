# LA BELLA NAPOLI

**Progetto scolastico TPSIT: sito web collaborativo realizzato con HTML e CSS**

La Bella Napoli è il sito di una pizzeria creato in collaborazione dalla classe. Il menu è diviso in tre sezioni: **Pizze**, **Bibite** e **Dolci**. Partendo da un template già predisposto, ogni studente contribuisce aggiungendo un prodotto alla sezione assegnata.

Il progetto utilizza esclusivamente **HTML e CSS**: non è richiesto JavaScript né l'installazione di programmi per modificare il sito. Il lavoro può essere svolto dal browser tramite GitHub.

---

## Obiettivo del progetto

Ogni studente deve realizzare **un solo prodotto** del menu, inserendo nella scheda assegnata:
- nome del prodotto;
- breve descrizione;
- prezzo;
- immagine rappresentativa.

Il sito contiene le tre categorie principali e un template con gli spazi predisposti per i prodotti. Per evitare conflitti, ogni studente deve modificare **soltanto la scheda che gli è stata assegnata**.

## Regole essenziali

1. Modifica solo il prodotto che ti è stato assegnato.
2. Lavora nella tua fork, non nella repository principale.
3. Invia una Pull Request indirizzata al Project Manager.
4. Attendi il controllo prima di considerare il contributo convalidato.
5. Rispetta il lavoro degli altri e segnala eventuali problemi in modo chiaro.

## Tutorial e info

La documentazione del progetto è organizzata in due tutorial e in questo README, che contiene le istruzioni operative.

- **Tutorial 1 — Introduzione al progetto e a GitHub:** presentazione del progetto e creazione/verifica dell'account GitHub.
- **Tutorial 2 — Accesso alla repository e fork:** come aprire la repository, creare la propria fork e usare l'editor web di GitHub.
- **Questo README — Lavoro, Pull Request e pubblicazione:** contiene i passaggi da seguire per realizzare e consegnare il prodotto.

## ISTRUZIONI!

### 1. Apri la repository principale
Apri il link della repository ufficiale condiviso dal Project Manager. Accedi a GitHub con il tuo account.

### 2. Crea la tua fork
Nella repository principale, premi **Fork** e poi **Create fork**. La fork è una copia personale del progetto nel tuo account GitHub.

Prima di modificare i file, controlla l'indirizzo della pagina: devi trovarti nella repository del **tuo account**, non in quella principale.

### 3. Apri il file del sito
Nella tua fork, apri `index.html` e premi l'icona della matita (**Edit this file**) per usare l'editor web di GitHub. Se l'editor non è disponibile, controlla di essere nella tua fork e di avere effettuato l'accesso.

### 4. Modifica il prodotto assegnato

Apri `index.html` nella tua fork e cerca la sezione della tua categoria ( Pizze, Bibite o Dolci ). Individua il **primo slot libero** e modifica soltanto quello, sostituendo:
- `Nome della bibita` con il nome del tuo prodotto;
- `€ 0,00` con il prezzo;
- il testo descrittivo con una breve descrizione del prodotto.

**Per inserire l'immagine**, hai due possibilità:

- **Usare un'immagine online:** Il link deve puntare direttamente al file immagine, non a una pagina web.
- **Caricare un'immagine su GitHub:** carica il file nella cartella `assets/images/` della tua fork e inserisci il percorso del file

Per entrambe le opzioni, sostituisci il codice:

`<div class="product-image image-placeholder" role="img" aria-label="Immagine della bibita da inserire">Immagine bibita 01</div>`

con un tag `<img>` come quelli seguenti:

`<img class="product-image" src="https://esempio.it/immagine.jpg" alt="Nome del prodotto">`
se l'immagine è presa da Internet

oppure

`<img class="product-image" src="assets/images/nome-immagine.jpg" alt="Nome del prodotto">`
se l'immagine è caricata nel progetto

Sostituisci il link o il percorso con quello corretto e aggiorna il testo `alt` con il nome del tuo prodotto.

**Non modificare le schede dei compagni, non riscrivere l'intera pagina e non cambiare il CSS generale** Se non sai COSA o DOVE  modificare, chiedi al Project Manager prima di intervenire.

### 5. Salva con un commit
Quando hai finito, premi **Commit changes**, inserisci un messaggio chiaro (ad esempio `Aggiunta pizza Margherita`) e conferma. Il commit salva le modifiche nella tua fork: non aggiorna direttamente il sito ufficiale.

### 6. Invia una Pull Request al Project Manager
Dalla tua fork, apri **Pull requests** e scegli **New pull request**. In alternativa, GitHub potrebbe mostrarti **Contribute** o **Compare & pull request**.

Inserisci un titolo che identifichi il contributo, ad esempio:

`Aggiunta pizza Margherita — Nome Cognome`

Nella descrizione indica brevemente cosa hai modificato, poi premi **Create pull request**.

### 7. Attendi il controllo
Il Project Manager controllerà la Pull Request e potrà:
- accettarla e integrarla nel progetto;
- chiederti di correggere qualcosa;
- rifiutarla se non rispetta le indicazioni.

Se vengono richieste correzioni, modifica la stessa fork e lo stesso branch: normalmente la Pull Request si aggiornerà automaticamente.

### 8. Come ottenere il check di completamento
Il check nella tabella sottostante viene assegnato **dal Project Manager**, dopo che hai inviato la Pull Request alla repository principale e il tuo contributo è stato controllato e ritenuto corretto. Creare una fork o fare un commit, da solo, non basta per ottenere il check.

### 9. Preparati alla presentazione
Al termine dovrai saper spiegare brevemente, in circa 2–3 minuti:
- quale prodotto hai realizzato;
- quali parti del codice HTML hai modificato;
- come hai gestito descrizione, prezzo e immagine.

---

## Gruppi di lavoro

> **Legenda:** `[ ]` non ancora convalidato · `[ X ]` Pull Request controllata e contributo convalidato dal Project Manager.

| N. | Nome e cognome | Gruppo | Prodotto assegnato | Pull Request inviata e convalidata |
|---:|---|---|---|:---:|
| 1 | Christian Salvatore Magarini (C, PM ) | Dolci | [Prodotto] | [ X ] |
| 2 | Igor Rosario Tsukerman | Dolci | [Prodotto] | [ ] |
| 3 | Christian Vatiero | Dolci | [Prodotto] | [ ] |
| 4 | Simone Ariante | Dolci | [Prodotto] | [ ] |
| 5 | Francesco Preziuso | Dolci | [Prodotto] | [ ] |
| 6 | Luca Carannante | Dolci | [Prodotto] | [ ] |
| 7 | Giuseppe Saccoia | Dolci | [Prodotto] | [ ] |
| 8 | Simone Tosti | Dolci | [Prodotto] | [ ] |
| 9 | Paolo Bassi | Pizze | [Prodotto] | [ ] |
| 10 | Marco Ivasyuk | Pizze | [Prodotto] | [ ] |
| 11 | Umberto Soligo | Pizze | [Prodotto] | [ ] |
| 12 | Lorenzo Menditto | Pizze | [Prodotto] | [ ] |
| 13 | Raffaele Teodonno (C) | Pizze | [Prodotto] | [ ] |
| 14 | Salvatore Buia | Pizze | [Prodotto] | [ ] |
| 15 | Antonio Primiceiro | Pizze | [Prodotto] | [ ] |
| 16 | Andrea Barone | Pizze | [Prodotto] | [ ] |
| 17 | Luca Sarnataro | Bevande | [Prodotto] | [ ] |
| 18 | Christian Ferrara (C) | Bevande | [Prodotto] | [ ] |
| 19 | Cristian Petrocco | Bevande | [Prodotto] | [ ] |
| 20 | Luca Veloce | Bevande | [Prodotto] | [ ] |
| 21 | Simone Ciotola | Bevande | [Prodotto] | [ ] |
| 22 | Lorenzo Longo | Bevande | [Prodotto] | [ ] |
| 23 | Antonio Massimo Crusco | Bevande | [Prodotto] | [ ] |
| 24 | Roberto Allegro | Bevande | [Prodotto] | [ ] |

---

## Struttura del progetto

```text
La-Bella-Napoli/
├── index.html
├── README.md
├── style.css
└── assets/
    └── images/
        └── ...
```

- `index.html`: struttura e contenuti del menu.
- `style.css`: grafica, layout, adattamento ai dispositivi ed effetti visivi.
- `assets/images/`: logo e immagini utilizzate dal sito.
- `README.md`: descrizione del progetto e istruzioni operative.

**Grazie a tutti per il contributo!**
