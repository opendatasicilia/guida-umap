# Opzioni di interazione predefinite

**`Forma del Popup`**, è la forma della finsetra quando clicchiamo nel punto, polilinea o poligono della mappa. Possiamo decidere di far aprire una finestra popup piccola, grande, oppure un pannello laterale, nel caso in cui il contenuto del testo sia molto esteso, oppure contenga sia testo che immagini o video, e quindi è più conveniente visualizzare il tutto in un pannello laterale dello schermo anzichè nel centro dello schermo a coperatura della mappa.

**`Stile del contenuto del Popup`**, si tratta dello stile del contenuto della finestra che si apre al clic sul punto/polilinea/poligono della mappa. Può essere dei seguenti tipi: **predefinito**, **tabella**, **GeoRSS (titolo + immagine)**, **GeoRSS (solo link)**. Il creatore della mappa decide lo strile del contenuto del popup in base alle esigenze di rappresentazione grafica sulla mappa.

**`Modello del contenuto del popup`**, specificando le proprietà dell'oggetto attraverso le parentesi graffe - es. `{name}` - queste saranno automaticamente sostituite con i valori corrispondenti. Il testo può essere formattato con la seguente sintassi: 

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


**`Mostra etichetta`**, è possibile stabilire di mostrare, o meno, le etichette dei punti/polilinee/poligoni al clic del mouse. Le scelte operabili su questo comando sono: 

   - **sempre**,
   - **mai**,
   - **in sovripmressione**.

Se si sceglie ==sempre== e i punti o le polilinee o i poligono sono numerosi nella mappa, si può generare un eccesso di elementi sulla mappa che possono disturbare l'utente. La scelta ==in sovrimpressione== può essere quella migliore, in questo caso solo passando il mouse sul punto/polilinea/poligono, apparirà l'etichetta con il titolo dato al punto/polilinea/poligono.

**`Direzione dell'etichetta`**, questa funzione permette di posizionare l'etichetta **a destra**, **a sinistra**, **in alto**, o **in basso** rispetto al punto/polilinea/poligono. E' buona prassi stabilire lo stesso verso di direzione per tutti gli elementi presenti nella mappa.

**`Etichette cliccabili`**, si può stabilire di fare diventare le etichette cliccabili con il mouse, oppure no.

**`Apri link in…`**, se nel campo descrizione del punto/polilinea/poligono sono presenti dei link, con questo comando si può decidere se aprire il link in: 

   - **nuova finestra**, si aprirà una nuova finestra del browser accanto a quella della mappa;
   - come **iframe** cioè incorporato dentro la stessa mappa dentro una nuova piccola finestra che viene aperta;
   - oppure nella **finestra di origine**, in quest'ultimo caso la  mappa sparirà per dare posto al nuovo link (non appare conveniente settare questa opzione in quanto si perde la visualizzazione della mappa).

