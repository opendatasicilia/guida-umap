# Condividi la mappa

L'icona che riporta il simbolo della "condivisione" posizionata in alto a sinistra ha lo scopo di fare condividere la mappa.

## Formati di dati per la condivisione della mappa

Le opzioni di condivisione sono diverse, vediamole:

  - **includi la mappa**: questa funzione permette di inglobare o incorporare (funzione di "iframe") la mappa dentro una qualsiasi pagina web-. Basta copiare il codice `HTML` e incollarlo nel codice della pagina web dove vogliamo che sia visualizzata la mappa.
  - **Link diretto**: è l'URL che si utilizza in un browser di navigazione internet per visualizzare la mappa.
  - **URL breve**: è l'URL reso corto (per comodità) che si utilizza in un browser di navigazione internet per visualizzare la mappa.
  - **Download dei dati**: con questa funzione possiamo scaricare il formato aperto del dataset che alimenta la mappa su uMap. E' possibile scaricare diversi formati aperti di dataset (open data). Questa è un importantissima funzione di uMap in quanto oltre ad essere un servizio web di visualizzazione di mappe interattive, è anche un contenitore di dataset open data, formati che possono essere riusati per fare altre cose in altri contesti. Vediamo quali tipi di dataset è possibile scaricare:
      - <kbd>mappa completa</kbd>: si tratta di un formato uMap che contiene tutti i layer, tutte le icone utilizzate con uMap, praticamente tutto quello che è stato creato con la mappa. Queso formato lo possiamo utilizzare su uMap per creare una mappa copia di quella dalla quale abbiamo scaricato il dataset.
      - <kbd>geojso</kbd>: un formato molto noto che contiene informazioni geografiche che può essere utilizzato, ad esempio, per creare progetti con il software opensource QGIS.
      - <kbd>gpx</kbd>: un formato classico per i dati geografici, utilizzato dai navigatori satellitari, che può essere utilizzato sugli stessi per riportare i dati su dispositivi mobili. Un formato che può essere utilizzato anche con Google map.
      - <kbd>kml</kbd>: il formato dati geografici utilizzato da Google nella sua piatattaforma Google map.
   
Questi formati disponibili al download sono una vera risorsa prezione di dati che si prestano a innumerevoli riusi.

!!! attention "importante"

    Nella fase di realizzazione di una mappa con uMap si può decidere se l'utente visualizzatore può visualizzare l'icona della condivisione della mappa o meno. 
    Posso realizzare una mappa interattiva con uMap da mostrare al mondo intero, ma non voglio diffondere (per vari motivi) i dati che hanno dato vita a quella mappa. 
    Questa scelta di visualizzazione o meno della funzione di condivisione dei dati è prevista.

!!! info "impostarlo in fase di creazione della mappa"

    Questo strumento può essere reso visibile a chi consulta la mappa quando il creatore della mappa lo rende visibile all'apertura della mappa.
    Per info dettagliate su come renderlo disponibile all'apertura della mappa, consultare la sezione **Creare**.
