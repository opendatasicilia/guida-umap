# Importa dati

uMap permette l'importazione di dati da fonti esterne in più formati:  

   - **`csv`**,
   - **`geojson`**,
   - **`kml`**,
   - **`gpx`**,
   - **`osm`**,
   - **`georss`**,
   - **`umap`**. 

Questa funzione permete di realizzare mappe in breve tempo utilizzando formati già disponibili all'utente.

## Scegli file

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
Valori separati da virgola, tabulatore o punto e virgola. Il sistema di riferimento spaziale implementato è WGS84. Vengono importati solo punti. La funzione di importazione va a cercare nell'intestazione le colonne «lat» e «lon» indifferentemente se scritte in maiuscolo o minuscolo. Tutte le altre colonne sono importate come proprietà.

### uMap
Importa tutti i dati di umap compresi layer e le impostazioni.


## Seleziona su quale livello fare l'importazione

Quando importiamo un dataset dall'esterno possiamo decidere in quale layer inserirlo. Questa funzione serve allo scopo.

### Sostituisci il contenuto del layer

Se ad esempio nel "layer 1" ci sono dati già inseriti, e vogliamo importare dall'esterno un dataset nello stesso layer, se flagghiamo il campo "**Sostituisci il contenuto del layer**" cancelleremo tutto quello che c'era prima del caricamento.


## Aggiungi un URL qui

Nel caso il nostro dataset si trova in un servizio web, come ad esempio un ==**Google spreadsheet**==, possiamo importare l'URL fornito da Google su questo campo, in questo modo si creerà un collegamento tra due servizi web: Google spreadsheet e uMap. 

!!! Info "Nel caso di collegamento con **Google spreadsheet** è necessario seguire poche ma importanti procedure nelle impostazioni di Google spreadsheet"

    1. aprire il file Google spreadsheet che si vuole mettere in collegamento con uMap;
    2. cliccare su file e poi su condividi;
    3. cliccare su esporta dati in formato CSV;
    4. verrà generato un indirizzo URL di quel foglio dove sono presenti i dati in formato CSV;
    5. l'URL generato da Google spreadsheet va inserito nella sezione "**Aggiungi un URL qui**";
    6. i dati presenti nel Google spreadsheet verranno visualizzati automaticamente sulla mappa uMap;
    7. ogni aggiornamento operato nel file di Google spreadsheet verrà riportato automaticamente sulal mappa uMap.


## Importa

Una volta effettuate le operazioni sopra descritte possiamo cliccare su **importa** per dare corso al caricamento dati su uMap alternativamente con le due modalità:

   1. carica file da PC;
   2. aggiungi un URL nell'apposito campo.
