# Scelte iniziali da fare per la costruzione di una mappa  :fontawesome-solid-check-double:

![](https://raw.githubusercontent.com/opendatasicilia/guida-umap/main/docs/img/menu-destra-umap.PNG)

Dal menù di destra sul pannello di controllo di uMap possiamo intuire che abbiamo di fronte due diverse possibilità di lavoro nell'avviare la costruzione di una mappa:

  1. **inserire manualmente punti di interesse, polilinee e poligoni**;
  2. **caricare, da fonti esterne, dataset in formato <kbd>csv</kbd> , <kbd>geojson</kbd> , <kbd>kml</kbd> , <kbd>gpx</kbd>**.


## Inserire manualmente punti di interesse, polilinee e poligoni  :writing_hand:

Questa scelta è effettuata quando dobbiamo tracciare sul territorio delle informazioni di cui siamo già in possesso e che conosciamo a livello visuale.

Un esempio può essere tracciare sul territorio le fontanelle di una città, nel caso si conoscono puntualmente i siti in cui sono dislocate, o ad esempio tracciare una polilinea per indicare un persorso di trekking in un bosco, oppure tracciare un poligono per indicare un area in cui si tiene un mercato del contadino in un area urbana.

L'inserimento manuale di punti, polilinee e poligoni, quindi, è utilizzato quando si conoscono le informazioni puntualmente nel territorio.

Questo tipo di uso della mappa è molto diffuso su uMap e soddisfa tante necessità da parte degli utenti.


## Caricare, da fonti esterne, ==dataset== in formato <kbd>csv</kbd>, <kbd>geojson</kbd>, <kbd>kml</kbd>, <kbd>gpx</kbd>  :octicons-upload-16:

Il caricamento di dataset in formato aperto rappresenta un servizio di enorme utilità per tanti utenti.

Chi è in possesso di dataset in questi formati, caricandoli su uMap attraverso l'uso dello strumento a forma di freccia verso l'alto (nel menù di destra) vedrà rappresentato geograficamente un'elevata quantità di informazioni. Si pensi ai navigatori GPS che generano file in formato <kbd>gpx</kbd>, questi tipi di file possono essere caricati su uMap per visulizzare percorsi e punti di interessi precedentemente tracciati.

### Il formato <kbd>csv</kbd>  :fontawesome-solid-file-csv:

**CSV (Comma Separated Values): valori separati da virgola**

![](https://upload.wikimedia.org/wikipedia/commons/thumb/3/30/Google_Sheets_logo_%282014-2020%29.svg/49px-Google_Sheets_logo_%282014-2020%29.svg.png) Un accenno particolare va fatto per il noto formato <kbd>csv</kbd>.

Un formato molto diffuso soprattutto nei software gestionali. I formati <kbd>csv</kbd> possono essere costituiti dai file di [**Google spreadsheet**](https://spreadsheets.google.com/), che, se resi leggibili da chiunque nelle impostazioni, possono essere letti da uMap automaticamente attraverso uno specifico URL. Questo aspetto rappresenta un enorme possibilità di interazione con uMap in quanto aggiornando i dati sui fogli Google, automaticamente ed in tempo quasi reale gli aggiornamenti sono resi visibile nelle mappe uMap.

!!! tip "una utile guida di OnData su come pubblicare dataset in formato <kbd>CSV</kbd>"

    [**Guida per la pubblicazione di CSV**](https://ondata.github.io/guidaPraticaPubblicazioneCSV/). È in parte la traduzione alla guida del [Ministry of Economic Affairs and Digital Transformation](https://datos.gob.es/en/documentacion/guia-practica-para-la-publicacion-de-datos-tabulares-en-archivos-csv) di Spagna.


Chi ha redatto questa guida utilizza molto spesso uMap in collegamento con i fogli Google realizzando mappe molto utili ed efficaci in termini di restituzione di informazioni contenute in altri servizi web (per l'appunto Google spreadsheet).

!!! info "approfondimento caricamento dati da fonti esterne, nella sezione ==importa dati=="

    In questa pagina si accenna alla possibilità di caricare dati da fonti esterne per alimentare la mappa. Gli approfondimenti vengono trattati nella sezione [**importa dati**](https://opendatasicilia.github.io/guida-umap/creare/importa-dati/).
