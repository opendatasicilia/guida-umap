# Inserire manualmente punti, polilinee e poligoni

In alto nel menù di destra abbiamo 3 icone: ==punti==, ==polilinee== e ==poligoni==.

![](https://raw.githubusercontent.com/opendatasicilia/guida-umap/main/docs/img/menu-destra-inserisci-umap.PNG)

Possiamo utilizzare questi 3 strumenti per tracciare tre diversi tipi di informazioni sul territorio. 

## Punto di interesse

Cliccando prima sull'icona del punto di interesse, poi possiamo cliccare con il mouse nel punto preciso della mappa in cui lo vogliamo posizionare, una volta effettuata questa azione si aprirà una finestra nella quale possiamo inserire un titolo al punto che abbiamo posizionato, e anche una descrizione.

Nella descrizione possiamo usare carattere normale, *italico*, **grassetto**, inserire link, immagini e anche video, attraverso la funzione di "embedding" (incorporare). 

### Inserimento di video

Questa funzione risulta di grande utilità in quanto in un punto in cui descriviamo qualcosa possiamo approfondire l'interesse sul sito fornendo un video dedicato. Di seguito si riporta un esempio di inserimento di video in un punto.

<iframe width="100%" height="600px" frameborder="0" allowfullscreen allow="geolocation" src="//umap.openstreetmap.fr/it/map/mappa-delle-vittime-cadute-per-mafia-a-palermo_20793?scaleControl=false&miniMap=false&scrollWheelZoom=false&zoomControl=true&editMode=disabled&moreControl=true&searchControl=null&tilelayersControl=null&embedControl=null&datalayersControl=true&onLoadPanel=none&captionBar=false&captionMenus=true"></iframe><br></br>

Nel campo **descrizione** della finestra che si presenta in riferimento ad un punto, dobbiamo inserire il codice del video youtube (può essere anche un video di un altra piattaforma web).  Il codice è del tipo:
```
{{{https://www.youtube.com/embed/TT0CvRDKLck|250}}}
```
dove

**`https://www.youtube.com/embed`** è sempre uguale per tutti i video di youtube

**`TT0CvRDKLck`** è il codice identificativo specifico per quel determinato video di youtube

**`250`** è la dimensione della larghezza del video dentro la finestra che si apre quando l'utente clicca sul punto per visualizzare il video.


### Inserimento di link, immagini e iframe

Per l'inserimento di link immagini e iframe basta seguire le indicazioni che vengono visualizzate nella finestra, cliccando nel simbolo del punto interrogativo (**?**):

`Link semplice: [[http://example.com]]`

`Link con testo: [[http://example.com|testo del link]]`

`Immagini: {{http://image.url.com}}`

`Immagine con larghezza personalizzata (width) (in px): {{http://image.url.com|width}}`

`Iframe: {{{http://iframe.url.com}}}`

`Iframe con altezza (in px) personalizzata: {{{http://iframe.url.com|height}}}`

`Iframe con altezza e larghezza personalizzata (in px): {{{http://iframe.url.com|height*width}}}`



## Polilinea 

La polilinea è utilizzata quando c'è la necessità di tracciare sul territorio un percorso preciso.

Anche nel caso della polilinea valgono le possibilità di inserire (abbinate alla polilinea) video, link, immagini e iframe. In qualsiasi punto della polilinea clicchiamo, si aprirà una finestra con il contenuto che abbiamo inserito nel campo "descrizione".



## Poligono

Il Poligono rappresenta un area che vogliano tracciare sul territorio.

Anche nel caso del poligono valgono le possibilità di inserire (abbinate al poligono) video, link, immagini e iframe. In qualsiasi punto del poligono clicchiamo, si aprirà una finestra con il contenuto che abbiamo inserito nel campo "descrizione".




!!! warning "importante: salva le azioni effettuate"

    Qualsiasi azione effettuiamo (inserimento punti, polilinee, poligono, video, link, immagini e iframe) alla fine della singola azione dobbiamo cliccare il tasto <span style="background-color: #3366ff; color: #ffffff;"><strong>Salva</strong></span> in colore azzurro che si trova in alto a destra nel pannello di controllo. Questa azione è molto importante in quanto ci consente di non perdere il lavoro svolto.





