# Opzioni interfaccia utente

In alto nel menù di destra abbiamo il menù ==**Opzioni interfaccia utente**==.

In questa sezione del pannello di controllo vengono definiti alcuni dei parametri che servono per personalizzare la visualizzazione della mappa nella fase di consultazione.

Andiamo con ordine e analizziamo ogni parametro previsto dal menù.

![](https://raw.githubusercontent.com/opendatasicilia/guida-umap/main/docs/img/opzioni-interfaccia-utente.png)


## Visualizza il controllo di zoom

Possiamo decidere di far visualizzare i segni **+** e **-** della mappa in fase di caricamento.

!!! tip "decidere come viene compiuta la funzione"

    Decidiamo se questa azione si realizza ==**sempre**==, ==**mai**==, o è una funzione ==**nascosta**== (cioè i segni di + e - compaiono in alto a sinistra solo se scorriamo i loghi a sinistra fino a quello della freccia in basso). 

    
## Visualizza il controllo di ricerca

Possiamo decidere di far visualizzare la funzione di controllo di ricerca di un sito sulla mappa in fase di caricamento.


!!! tip "decidere come viene compiuta la funzione"

    Decidiamo se questa azione si realizza ==**sempre**==, ==**mai**==, o è una funzione ==**nascosta**== (cioè l'icona di controllo di ricerca compare in alto a sinistra solo se scorriamo i loghi a sinistra fino a quello della freccia in basso). 


## Visualizza il controllo di schermo intero

Possiamo decidere di far visualizzare la funzione di visualizzazione della mappa a schermo intero. Questa funzione può tornare utile se vogliamo concentrarci nella visualizzazione dei contenuti della mappa, senza farci infastidire da altri elementi nello schermo.

!!! tip "decidere come viene compiuta la funzione"

    Decidiamo se questa azione si realizza ==**sempre**==, ==**mai**==, o è una funzione ==**nascosta**== (cioè l'icona di controllo di schermo intero compare in alto a sinistra solo se scorriamo i loghi a sinistra fino a quello della freccia in basso). 


## Visualizza il controllo per l'incorporamento

Questa è una funzione importante. Possiamo decidere di far visualizzare la funzione di condivisione della mappa, non solo come indirisso URL, ma anche come azione di scaricamento dei dati della mappa nei formati:

   - **`mappa completa`**: si tratta di un formato uMap che contiene tutti i layer, tutte le icone utilizzate con uMap, praticamente tutto quello che è stato creato con la mappa. Queso formato lo possiamo utilizzare su uMap per creare una mappa copia di quella dalla quale abbiamo scaricato il dataset.
   - **`geojson`**: un formato molto noto che contiene informazioni geografiche che può essere utilizzato, ad esempio, per creare progetti con il software opensource QGIS.
   - **`gpx`**: un formato classico per i dati geografici, utilizzato dai navigatori satellitari, che può essere utilizzato sugli stessi per riportare i dati su dispositivi mobili. Un formato che può essere utilizzato anche con Google map.
   - **`kml`**: il formato dati geografici utilizzato da Google nella sua piatattaforma Google map.
   
Questi formati disponibili al download sono una vera risorsa prezione di dati che si prestano a innumerevoli riusi. Può capitare, tuttavia, che il creatore della mappa intende solo far visualizzare la mappa attraverso l'indirizzo URL, ma per vari ragioni non vuole condividere i formati dei dati che alimentano la mappa.

!!! tip "decidere come viene compiuta la funzione"

    Decidiamo se questa azione si realizza ==**sempre**==, ==**mai**==, o è una funzione ==**nascosta**== (cioè l'icona di controllo per l'incorporamento - condivisione - compare in alto a sinistra solo se scorriamo i loghi a sinistra fino a quello della freccia in basso). 


## Visualizza il controllo di localizzazione

Possiamo decidere di far visualizzare la funzione di controllo della mia localizzazione sulla mappa, attivando servizi di georeferenziazione (gps sullo smartphone ad esempio). 

!!! tip "decidere come viene compiuta la funzione"

    Decidiamo se questa azione si realizza ==**sempre**==, ==**mai**==, o è una funzione ==**nascosta**== (cioè l'icona di controllo di localizzazione compare in alto a sinistra solo se scorriamo i loghi a sinistra fino a quello della freccia in basso). 


## Visualizza il controllo di misurazione

Possiamo decidere di far visualizzare la funzione di misurazione della distanza da un punto ad un altro della mappa. Funzione molto utile in tante situazioni.

!!! tip "decidere come viene compiuta la funzione"

    Decidiamo se questa azione si realizza ==**sempre**==, ==**mai**==, o è una funzione ==**nascosta**== (cioè l'icona di controllo di misurazione - righello - compare in alto a sinistra solo se scorriamo i loghi a sinistra fino a quello della freccia in basso). 


## Mostra il controllo per aprire l'editor di OpenStreetMap

Possiamo decidere di far visualizzare la funzione che permette l'apertura dell'editor di Openstreetmap. 

!!! quote "da Wikipedia"

    *OpenStreetMap è un progetto collaborativo finalizzato a creare mappe del mondo a contenuto libero. Il progetto punta ad una raccolta mondiale di dati geografici, con scopo principale la creazione di mappe e cartografie.*
 

Questa funzione è utile per coloro che sono impegnati ad aggiornare i dati nella piattaforma mondiale.

!!! tip "decidere come viene compiuta la funzione"

    Decidiamo se questa azione si realizza ==**sempre**==, ==**mai**==, o è una funzione ==**nascosta**== (cioè l'icona di Openstreetmap compare in alto a sinistra solo se scorriamo i loghi a sinistra fino a quello della freccia in basso). 


## Mostra il controllo dei dati per i layer

Possiamo decidere di far visualizzare la funzione che permette di visualizzare tutti i layer (strati) di cui è composta la mappa. I layer della mappa rappresentano dgli stati di contenuti che sono differenziati per tematica, ad esempio in  una mappa della mobilità urbana possiamo avere un layer per le piste ciclabili, uno per le zone pedonali e uno per i percorsi dei bus. **E' consigliabile mostrare l'icona dei layer all'avvio della mappa proprio per comunicare immediatamente all'utente la strutturazione della mappa**.

!!! tip "decidere come viene compiuta la funzione"

    Decidiamo se questa azione si realizza ==**sempre**==, ==**mai**==, ==*espanso*== o è una funzione ==**nascosta**== (cioè l'icona di controllo dei dati per i layer compare in alto a sinistra solo se scorriamo i loghi a sinistra fino a quello della freccia in basso). In questo caso abbiamo una possibilità in più di scelta (==espanso==). Espanso significa che nel menù di sinistra all'avvio della mappa è possibile visualizzare un menù con il titolo dei vari layer di cui è composta la mappa.


## Visualizza il controllo del livello del tile

Il tile è lo ==sfondo== della mappa. Possiamo decidere di far visualizzare la funzione che permette di cambiare lo sfondo della mappa, scegliendolo tra i diversi che uMap mette a disposizione. In una pagina dedicata più avanti (**sfondo personalizzato**) vediamo anche come personalizzare uno sfondo diversamente da quelli resi disponibili da uMap.

!!! tip "decidere come viene compiuta la funzione"

    Decidiamo se questa azione si realizza ==**sempre**==, ==**mai**== o è una funzione ==**nascosta**== (cioè l'icona di controllo del livello del tile - sfondo - compare in alto a sinistra solo se scorriamo i loghi a sinistra fino a quello della freccia in basso). Dipende dal colore dei punti, polilinee e poligoni riportati nella mappa può essere conveniente cambiare lo sfondo della mappa, decidendo, ad esempio, per uno molto chiaro o scuro.


## Visualizza il pulsante per aggiungere una mappa come speciale

Possiamo decidere di far visualizzare la funzione che permette di aggiungere una mappa come speciale. Per rendere questa funzione applicabile, anche se siamo utenti non creatori di mappe su uMap, dobbiamo effettuare l'accesso ad uMap tramite i vari servizi previsti (GitHub, Twitter, Openstreetmap e Bitbucket).

!!! tip "decidere come viene compiuta la funzione"

    Decidiamo se questa azione si realizza ==**sempre**==, ==**mai**== o è una funzione ==**nascosta**== (cioè l'icona per aggiungere una mappa come speciale, compare in alto a sinistra solo se scorriamo i loghi a sinistra fino a quello della freccia in basso). 



## Visualizzare il controllo "altro"

Nel menù di sinistra possiamo decidere di far visualizzare un icona a forma di freccia verso il basso se vogliamo che l'utente possa scorrere tutti gli strumenti che abbiamo sopra elencato, nel caso avessimo deciso di renderli tutti o parzialmente visibili all'avvio della mappa. Se le funzioni abilitate come visibili ==sempre== sono molte, allora uMap permette la visualizzazione delle prime e poi con una freccia verso il basso permette l'apertura di altre icone cliccabili.

!!! tip "decidere come viene compiuta la funzione"

    Decidiamo se questa azione si realizza semplicemente cliccando su ==**on**== o ==**off**==. 


## Abilitare la rotellima del mouse per lo zoom

Possiamo decidere di abilitare la rotellina del mouse per gestire lo zoom in e zoom out della mappa. E' indubbiamente una funzione molto comoda per la consultazione di mappe web interattive.

!!! tip "decidere come viene compiuta la funzione"

    Decidiamo se questa azione si realizza semplicemente cliccando su ==**on**== o ==**off**==. 


## Visualizzare una mappa panoramica

uMap permette di far visualizzare in basso a destra una piccola mappa panoramica. Se abilitata questa funzione, viene generata una finsetra piccola in basso a destra nella quale viene riprodotta in piccolo la mappa con un rettangolo che identifica l'area nella quale stiamo zoommando.

!!! tip "decidere come viene compiuta la funzione"

    Decidiamo se questa azione si realizza semplicemente cliccando su ==**on**== o ==**off**==. 


## Visualizzare la scala

Se abilitata questa funzione, verrà visualizzato in basso a sinistra una scala che riporta un unità di misura in metri e feet (piedi), così da dare all'utente il senso generale e aprticolare delle geometrie presenti nella mappa.

!!! tip "decidere come viene compiuta la funzione"

    Decidiamo se questa azione si realizza semplicemente cliccando su ==**on**== o ==**off**==. 


## Visualizza un panello al caricamento

Quando l'utente clicca sull'indirizzo URL della mappa, attraverso  la funzione "Visualizza un panello al caricamento" è possibile far aprire una finestra laterale a sinistra in cui abbiamo alternativamente queste informazioni disponibili:

   - **Nulla**: in questo caso non si aprirà nessuna finestra laterale, ma si avvierà semplicemente la mappa in consultazione.
   - **Didascalia**: in questo caso si aprirà una finestra a destra con il **titolo mappa**, **descrizione mappa**, **nome dei layers della mappa**, e **Ringraziamento** cioè una sezione nella quale possiamo visualizzare i metadati della mappa come licenza rilasciata, nomi di persone/enti/organizzazioni che sono state citate, riconoscimenti per la mappa di sfondo che vengono forniti da uMap in automatico quando si sceglie lo sfondo da far visualizzare, e altri metadati che vediamo più avanti nell'apposita sezione **Ringraziamenti**.
   - **Visualizza i dati**: questa funzione se selezionata permette - all'avvio della mappa - di visualizzare nella finestra di destra un elenco di dati relativi ai contenuti della mappa (punti, polilinee, poligoni). Si seleziona questa scelta se si vuol dare all'utente immediatamente un elenco di dati tra i quali scegliere quelli da visualizzare puntualmente nella mappa.
   - **Faccetta di ricerca**: selezionando questa funzione, nella fienstra di destra viene visualizzata semplicemente una barra di ricerca che possiamo utilizzare per cercare qualcosa di specifico dentro la mappa.

!!! tip "decidere quale scelta effettuare"

    Nell'esperienza pluriennale d'uso di uMap, chi redige questa guida, tra le 4 selezioni possibili, ha utilizzato spesso la ==**Didascalia**== per il fatto che questa da l'opportuità di comunicare un numero elevato di informazioni e metadati e soprattutto perchè oltre al titolo della mappa compare la descrizione di cosa la mappa rappresenta e perchè è stata creata.


## Vista predefinita

Questa funzione serve per decidere come far visualizzare come vista predefinita. Cliccando sul menù a tendina abbiamo 4 scelte da poter effettuare:

   1. **Centro e zoom salvati**, la vista predefinita ricade sul centro della mappa;
   2. **Adatta tutti i dati**, la vista predefinita si adatta al complesso dei dati inseriti permettendo di avere nello schermo più o meno uniformemente distribuite le informazioni tracciate;
   3. **Ultimo oggetto**, la vista predefinita si riferisce all'ultimo oggetto inserito;
   4. **Posizione dell'utente**, la  vista predefinita si adatta alla posizione geografica dell'utente, se l'utente ha attivato la geolocalizzazione.

!!! tip "decidere quale scelta effettuare"

    Sarà la pratica a far decidere quale selezione effettuare. **Adatta a tutti i dati** potrebbe essere la soluzione che permette di visualizzare tutti i dati presenti nella mappa, ma dipende da caso a caso e dalla quantità di geometrie tracciate nella mappa.


## Visualizzare la finestra di pop up a piè di pagina

==Inserire testo==


## Visualizzare una didascalia

Attivando questa funzione (**on**) viene visualizzata un piccolo footer con il titolo della mappa.


## Visualizzare le etichette dei menù

==Inserire testo==
