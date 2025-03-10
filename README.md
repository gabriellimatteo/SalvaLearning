# Learning - Sito Web di Formazione

Questo progetto è una landing page responsive per un sito di formazione e sviluppo personale, ispirato al design di Canva.

## Struttura del Progetto

Il progetto è organizzato nelle seguenti cartelle e file:

```
├── index.html           # File HTML principale
├── css/
│   └── styles.css       # Stili CSS
├── js/
│   └── script.js        # Script JavaScript
└── assets/              # Cartella per immagini e altri media
```

## Sezioni della Landing Page

La landing page include le seguenti sezioni:

1. **Home/Hero** - Sezione principale con titolo e call-to-action
2. **Chi Siamo** - Informazioni sull'azienda e la sua missione
3. **Corsi** - Presentazione dei corsi offerti
4. **Testimonianze** - Feedback degli studenti
5. **Call to Action** - Invito all'azione
6. **Contatti** - Informazioni di contatto e form

## Caratteristiche del Design

- Design responsivo che si adatta a tutti i dispositivi
- Animazioni e transizioni fluide
- Navigazione con smooth scrolling
- Menu hamburger per dispositivi mobili
- Compatibilità cross-browser

## Come Modificare il Contenuto

### Modificare il Testo

Per modificare il testo, apri il file `index.html` e cerca la sezione che desideri modificare. Il testo è organizzato in modo logico secondo la struttura del documento.

### Aggiungere Immagini

1. Aggiungi le tue immagini nella cartella `assets/`
2. Nel file HTML, sostituisci i div `placeholder-image` con tag `<img>` che puntano alle tue immagini:

```html
<img src="assets/nome-immagine.jpg" alt="Descrizione immagine">
```

### Modificare i Colori

I colori principali sono definiti come variabili CSS nel file `styles.css`. Puoi modificarli cambiando i valori nelle variabili:

```css
:root {
    --primary-color: #5846f6;
    --secondary-color: #7d5fff;
    --accent-color: #00c2cb;
    /* ... altre variabili ... */
}
```

## Funzionalità JavaScript

Il file `script.js` include le seguenti funzionalità:

- Navigazione con smooth scrolling
- Menu mobile responsive
- Animazioni al caricamento della pagina
- Validazione del form di contatto

## Come Personalizzare Ulteriormente

1. **Font** - Puoi cambiare il font modificando il link Google Fonts nell'head dell'HTML
2. **Icone** - Il sito utilizza Font Awesome per le icone, puoi scegliere altre icone dal loro sito
3. **Effetti** - Puoi aggiungere altri effetti o animazioni modificando il CSS e il JavaScript

## Browser Supportati

- Google Chrome (ultime 2 versioni)
- Mozilla Firefox (ultime 2 versioni)
- Safari (ultime 2 versioni)
- Microsoft Edge (ultime 2 versioni)

## Prossimi Passi

Per completare il sito:

1. Sostituire i placeholder con immagini reali
2. Aggiungere contenuti reali specifici per la tua attività
3. Collegare il form di contatto a un backend per la gestione delle richieste
4. Implementare una galleria per mostrare foto dei corsi
5. Aggiungere una sezione FAQ

---

Creato con ❤️ per il tuo progetto di formazione online. 