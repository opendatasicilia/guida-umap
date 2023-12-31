# Importa dati :material-upload:

uMap permette l'importazione di dati da fonti esterne in più formati:  

   - <kbd>csv</kbd>
   - <kbd>geojson</kbd>
   - <kbd>kml</kbd>
   - <kbd>gpx</kbd>
   - <kbd>osm</kbd>
   - <kbd>georss</kbd>
   - <kbd>umap</kbd> 

Questa funzione permete di realizzare mappe in breve tempo utilizzando formati già disponibili all'utente.

## Scegli file  :file_folder:

In questa parte del pannello di controllo di "importa dati" possiamo caricare un file nei formati sopra elencati, selezionandolo dal PC.

Una volta selezionato il file, nel menù "**scegli il foramto dati**" comparirà automaticamente il formato in quanto la piattaforma uMap riconosce l'estenzione del file.

Di seguito si riportanto le proprietà di ogni formato che è possibile importare su uMap attraverso questa apposita funzionalità.

### GeojSON 
Tutte le proprietà sono state importate.

### GPX
Proprietà importate:name, desc.

### KML
Proprietà importate:name, description.

### CSV
Valori separati da virgola, tabulatore o punto e virgola. Il sistema di riferimento spaziale implementato è <kbd>WGS84</kbd>. Vengono importati solo punti. La funzione di importazione va a cercare nell'intestazione le colonne <kbd>lat</kbd> e <kbd>lon</kbd> indifferentemente se scritte in maiuscolo o minuscolo. Tutte le altre colonne sono importate come "proprietà".

### uMap
Importa tutti i dati di uMap compresi layer e le impostazioni.


## Seleziona su quale livello fare l'importazione  :fontawesome-solid-layer-group:

Quando importiamo un dataset dall'esterno possiamo decidere in quale layer inserirlo. Questa funzione serve allo scopo.

### Sostituisci il contenuto del layer  :arrows_clockwise:

Se ad esempio nel "layer 1" ci sono dati già inseriti, e vogliamo importare dall'esterno un dataset nello stesso layer, se selezioniamo il campo "**Sostituisci il contenuto del layer**" cancelleremo tutto quello che c'era prima del caricamento.


## Aggiungi un URL qui  :material-web:

Nel caso il nostro dataset si trova in un servizio web, come ad esempio un ==**Google spreadsheet**==, possiamo importare l'URL fornito da Google su questo campo, in questo modo si creerà un collegamento tra due servizi web: Google spreadsheet e uMap. 

!!! Info "Nel caso di collegamento con ==Google spreadsheet== è necessario seguire poche ma importanti procedure nelle impostazioni di Google spreadsheet"

    1. aprire il file Google spreadsheet che si vuole mettere in collegamento con uMap;
    2. cliccare su file e poi su condividi;
    3. cliccare su esporta dati in formato <kbd>CSV</kbd> ;
    4. verrà generato un indirizzo URL di quel foglio dove sono presenti i dati in formato <kbd>CSV</kbd> ;
    5. l'URL generato da Google spreadsheet va inserito nella sezione "**Aggiungi un URL qui**";
    6. i dati presenti nel Google spreadsheet verranno visualizzati automaticamente sulla mappa uMap;
    7. ogni aggiornamento operato nel file di Google spreadsheet verrà riportato automaticamente sulla visualizzazione della mappa uMap.


## Importa  :material-import:

Una volta effettuate le operazioni sopra descritte possiamo cliccare su **importa** per dare corso al caricamento dati su uMap alternativamente con le due modalità:

   1. carica file da PC;
   2. aggiungi un URL nell'apposito campo.
