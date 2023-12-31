# Aggiungi layer :fontawesome-solid-layer-group:

Questa sezione del menù di destra, contrassegnata dall'icona a 3 fogli sovrapposti, serve per aggiungere uno o più layer (**strati**) di informazioni nella mappa.

Prima di creare una mappa è buona prassi fare uno schema delle tipologie tematiche di dati che devono essere rappresentati geograficamente.

Facciamo un esempio: se vogliamo costruire una mappa, anche semplice, della mobilità urbana potremmo decidere di avere i seguenti layer su cui caricare le diverse tipologie tematiche di dati:

   1. piste ciclabili :person_biking_tone1:
   2. percorsi del tram :tram:
   3. aree pedonali :woman_walking:
   4. percorsi del taxi sharing :oncoming_taxi:
   5. area della zona a traffico limitato (ZTL) :traffic_light:
   6. stalli di parcheggio del car sharing :red_car:
   7. percorsi delle navette gratuite nel centro storico della città :bus:

Queste informazioni necessitano di avere layer separati in quanto si tratta di tematismi diversi. Posso disporre già dei dati di 4 dei 7 tematismi in quanto tratto questi dati in alcuni software gestionali, e per essi posso fare un caricamento con la funzione "**importa dati**", mentre per altri 3 tematismi posso pensar di cominciare da zero, tracciando i punti (es. stalli car sharing) con i marcatori nella mappa.

uMap permette così di lavorare in modalità ibrida, caricando dataset in alcuni layer con la funzione "**importa dati**" e inserendo punti, polilinee e poligoni **manualmente**.

## Cosa inserire per ogni layer

Vediamo cosa inserire per ogni layer creato.

### Nome

Titolo del layer, breve preferibilmente.

### Descrizione

Descrivere brevemente a cosa serve il layer creato.

### Tipo layer

   - **Predefinito**
   - **Raggruppata**, più punti vengono accorpati in un unico punto che geograficamente rappresenta il centro di tutti quelli raggruppati. In questo caso dentro il punto comparirà il numero dei punti raggruppati. Si utilizza questa funzione quando i punti sulla mappa sono numerosi e visualizzarli tutti comporterebbe una confusione.
   - **Mappa di densità**, in questo caso si crea una mappa con una rappresentazione grafica dei dati dove i singoli valori contenuti in una matrice sono rappresentati da colori (Wikipedia). Si usa quando si vuole rappresentare l'intensità di fenomeni rappresentati da una mole numerosa di dati sulla geografia del territorio.
   - **Cloropleth**, le mappe coropletiche forniscono un modo semplice per visualizzare come una variabile varia in un'area geografica o mostrare il livello di variabilità all'interno di una regione ([Wikipedia](https://en.wikipedia.org/wiki/Choropleth_map)). Queste mappe sono caratterizzate da poligoni, che in base al colore e alla tonalità di colore indicano variazioni di fenomeni.


![](https://upload.wikimedia.org/wikipedia/commons/e/e8/Densita_Veneto.png) <sup>Mappa di densità</sup>

![](https://raw.githubusercontent.com/opendatasicilia/guida-umap/main/docs/img/mappa-cloropetica.PNG) <sup>Mappa coropletica</sup>

## Mostra al caricamento

Questa funzione se attivata (**`on`**) permette di visualzizare il layer e relativo contenuto all'avvio della mappa.

## I dati sono consultabili?

Impostato su **`off`** nasconde il layer dalla presentazione, dal browser dati, dalla navigazione popup.

## Show this layer in the caption

Se abilitata la funzione, al caricamento della mappa nella pagina web, nel pannello laterale destro, oltre alle informazioni relative al nome e descrizione della mappa, verrà visualizzato il layer con il relativo titolo e colore. Sicuramente è una funzione comoda perchè oltre ai metadati generali sulla mappa vengono visualizzati i layer che compongono la mappa. È da ricordare che i layers sono visibili anche nel menù di sinistra della mappa uMap per l'utente visualizzatore.


## Proprietà della geometria

**`colore`**, è possibile scegliere da menù specifico un colore per tutte le geometrie (punti, polilinee e poligoni) rappresentati nel layer.

**`forma dell'icona`**, nel caso di punti (marcatori) è possibile scegliere tra "predefinito", "cerchio", "goccia", "palla".

**`simbolo dell'icona`**, da un menù è possibile scegliere tra diverse icone che possono essere riportate sui punti della mappa. È possibile anche importare un icona attraverso un indirizzo URL da fornire in questo campo.

**`opacità dell'icona`**, un campo in cui è possibile scegliere il livello di opacità dell'icona attraverso un cursore.

**`opacità`**, un campo in cui è possibile scegliere il livello di opacità della polilinea o poligono attraverso un cursore.

**`tratto`**, attraverso una funzione di on/off è possibile attivare/disattivare la visualizzazione del tratto di un poligono. Indica se visualizzare o meno i lati dei poligoni.

**`peso`**, un cursore permette di definire il livello di peso della polilinea o del poligono.

**`riempimento`**, Indica se riempire i poligoni con il colore.

**`colore di riempimento`**, opzionale. Stesso colore se non assegnato.

**`opacità riempimento`**, attraverso un cursore si può definire l'opacità di riempimento di un poligono.


## Proprietà avanzate

**`semplifica`**, quanto vuoi semplificare la polilinea per ogni zoom (più = maggiori performance a aspetto più semplificato, meno = maggior dettaglio).

**`tratteggio`**, una lista di numeri separati da virgola che definisce lo schema del tratto e del trattino. Es.: "5, 10, 15".

**`livello di zoom predefinito`**, livelli di zoom per zoom automatici.

**`dallo zoom`** - **`allo zoom`**, funzioni opzionali.

**`campo etichetta`**, il nome della proprietà da utilizzare come etichetta (es.: "nome"). Può anche essere utilizzata una proprietà tra parentesi per usarne più di una o combinarle con contenuto statico (ad esempio: "{nome} in {luogo}").



