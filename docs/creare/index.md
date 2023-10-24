# Creare una mappa

Questa sezione è dedicata alle cose da fare per creare e arricchire una mappa con uMap.

uMap permette una serie estesa di funzioni per la personalizzazione di una mappa, conoscere nel dettaglio tutte le funzioni permette a chiunque di padroneggiare lo strumento per generare mappe ad alto effetto visivo e con ricchezza di dettagli.

## Accedere a uMap con gli account di altri servizi web

Per accedere a uMap per creare una mappa è necessario utilizzare uno dei seguenti account:

   - **GitHub**,
   - **Twitter (X)**,
   - **OpenStreetMap**
   - **Bitbucket**.

!!! tip "accedere sempre con lo stesso account"

    Quando si effettuano gli accessi a uMap, è ==utile e conveniente== utilizzare sempre lo stesso account, **GitHub** o **Twitter** o **Openstreetmap** o **Bitbucket**. Questo perchè se utilizziamo account diversi e creiamo mappe, quando accediamo con un account non avremo nel pannello di controllo generale tutte le mappe realizzate con accesso eseguito attraverso gli altri account.
    Accedendo con uno degli account si avrà la dashboard con le proprie mappe generate.

    ![](https://raw.githubusercontent.com/opendatasicilia/guida-umap/main/docs/img/umap-dashboard.PNG)

## I principali strumenti

**Modifica le proprietà della mappa** è il pannello con il quale cominciare a lavorare.

![](https://raw.githubusercontent.com/opendatasicilia/guida-umap/main/docs/img/umap-creazione.PNG)

I principali strumenti per la creazione di una mappa sono di seguito elencati:
```
├─ Nome mappa
├─ Descrizione mappa
├─ Opzioni interfaccia utente
├─ Proprietà definite della forma
├─ Proprietà preimpostate
├─ Opzioni di interazione predefinite
├─ Sfondo personalizzato
├─ Sovrapposizione personalizzata
├─ Limite di confine
├─ Presentazione
├─ Ringraziamenti
└─ Azioni avanzate
```

### Nome della mappa

Innanzitutto dobbiamo decidere il nome che apparirà nell'URL della mappa. È consigliabile dare un nome quanto più sintetico possibile.

Se decidiamo di cambiare successivamente il nome della mappa che abbiamo dato inizialemente, non c'è problema perchè anche digitando l'URL del precedente nome della mappa, uMap riporterà autimaticamente (redirect) all'ultimo URL derivante dall'ultimo nome che abbiamo dato.

### Descrizione

In questo campo possiamo editare tutto il testo che riteniamo necessario. Oltre al testo è possibile inserire link, iframe e immagini. Un editor di uMap ci guida in questa fase

!!! Info "editor per la formattazione del testo"

    Formattazione testo

    *un solo asterisco per il corsivo*  `*`

    **due asterischi per il testo marcato** `**`

    # un cancelleto per l'intestazione principale `#`

    ## due cancelletti per le intestazioni di secondo livello `##`

    ### tre cancelletti per intestazione di terzo livello  `###`

    Link semplice: [[http://example.com]]

    Link con testo: [[http://example.com|testo del link]]

    Immagini: {{http://image.url.com}}

    Immagine con larghezza personalizzata (width) (in px): {{http://image.url.com|width}}

    Iframe: {{{http://iframe.url.com}}}

    Iframe con altezza (in px) personalizzata: {{{http://iframe.url.com|height}}}

    Iframe con altezza e larghezza personalizzata (in px): {{{http://iframe.url.com|height*width}}}

    --- per una linea orizzontale


Queste due prime impostazioni rappresentano lo start per iniziare a costruire una mappa.

Nelle pagine che seguono vediamo come proseguire con le numerose impostazioni.

## Salva :material-content-save:

Salva, salva, salva.

![](https://raw.githubusercontent.com/opendatasicilia/guida-umap/main/docs/img/salva.PNG)

!!! warning "salvare sempre dopo aver compiuto azioni nel pannello di controllo"

    Quando si effettuano azioni sul pannello di controllo bisogna ricordarsi di cliccare sempre sul tasto di colore azzurro in alto **salva** altrimenti le modifiche e le azioni effettuate non saranno memorizzate.
