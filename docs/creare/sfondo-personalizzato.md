# Sfondo personalizzato

Questa sezione del pannello di controllo di uMap permette di personalizzare lo sfondo della mappa. Risulta una possibilità molto utile anche perchè ad esempio uMap per l'Italia non consente di fissare la restituzione satellitare del territorio. Con questa funzione possiamo risolvere questa criticità, importando dall'esterno lo sfondo.

## Due campi per nome e URL dello sfondo

Nel momento in cui cominciamo a creare una mappa, uMap ci fornisce di default lo sfondo di Openstreetmap.  Nei primi due campi di questa sezione abbiamo:

   1. il primo che indica il nome dell'attuale sfondo, nel caso di OpenStreetMap, apparirà "OpenStreetMap",
   2. nel secondo campo appare un indirizzo URL. Nel caso dello sfondo OpenStreetMap apparirà il seguente URL: `https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png`

!!! info "il codice /{z}/{x}/{y}.png"

    Nel campo dedicato all'URL dello sfondo mappa possiamo inserire vari URL che fanno ocaricare a uMap uno sfondo personalizzato, prelevandolo da una fonte esterna. Una condizione essenziale per rendere efficace pienamente questa funzione è che la parte finale dell'URL deve finire sempre in `/{z}/{x}/{y}.png`. Infatti nel pannello di controllo dello "sfondo personalizzato" è riportato il seguente testo: **Schema supportato: http://{s}.domain.com/{z}/{x}/{y}.png**

Di sotto un esempio di impostazione dello sfondo personalizzato della mappa:

![](https://private-user-images.githubusercontent.com/20488693/296460825-a1c24814-ccb5-4c20-9c5d-5a60336d5736.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDUxNTUwNDAsIm5iZiI6MTcwNTE1NDc0MCwicGF0aCI6Ii8yMDQ4ODY5My8yOTY0NjA4MjUtYTFjMjQ4MTQtY2NiNS00YzIwLTljNWQtNWE2MDMzNmQ1NzM2LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAxMTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMTEzVDE0MDU0MFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTkwMjJiMmE3MjhiMGNmZGVlY2EzZmZjZWFmODYxNDZkODA0OWIxN2Y4Y2RlZThiZGMxNjgxMmRmZTQzYmQ1MWImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.VQ_p4RGUja8eesdYRq-luaeAia5SRhZ0Cy-r9jL5PWg)


## Altri due campi per zoom in e out

Il terzo e quarto campo contengono degli spazi in cui è possibile assegnare un valore numerico alle funzioni di **zoom in** e **zoom out**. Rappresentano i valori per fare zoomare da un massimo di .... ad un minimo di ....

## Un ultimo campo per i metadati dello sfondo 

Il quinto campo permette di editare testo per inserire i metadati dello sfondo mappa. Nel caso dello sfondo preimpostato "OpenStreetMap", compare il seguente testo: 

==map data © [[http://osm.org/copyright|OpenStreetMap contributors]] under ODbL==

## TMS

Infine è disponibile l'attivazione della funzione **formato TMS**.

Il termine "TMS" si riferisce a "Tile Map Service", un protocollo per la distribuzione di mappe in forma di tile. Le mappe vengono divise in piccoli "tiles", ognuno con una propria posizione e zoom specifici. Questo protocollo è comunemente utilizzato per la visualizzazione di mappe online. Il protocollo TMS è supportato da varie librerie e strumenti GIS, tra cui GDAL.

## Una fonte di numerosi sfondi per uMap

Esistono diverse fonti per alimentare e personalizzare lo sfondo delle mappe su uMap. Una fonte molto interessante per varietà di sfondi é: 

[**https://leaflet-extras.github.io/leaflet-providers/preview**](https://leaflet-extras.github.io/leaflet-providers/preview/). 

Diversi sfondi sono disponibili previo pagamento di servizi che erogano API ad hoc, ma si trovano tanti sfondi da poter utilizzare gratuitamente alla sola condizione di citare la fonte nella sezione "metadati" della funzione "personalizzazione sfondo".

## Un editor per creare sfondi da usare su uMap

[**https://mapwarper.net**](https://mapwarper.net/) è un servizio web molto utile che permette di generare sfondi da poter usare su uMap.

Si può partire dal caricamento di un immagine JPG o un file in fomato PDF, e attraverso un sistema di georeferenziazione dei punti, per far coincidere quelli dell'immagine con quelli forniti dai servizi di Mapwarper, si riesce a georiferire l'immagine caricata e si ottiene l'indirizzo URL che termina con **`/{z}/{x}/{y}.png`** da usare nel campo "sfondo personalizzato" di uMap.

A questo link [**http://u.osmfr.org/m/228928**](http://u.osmfr.org/m/228928/) è possibile vedere l'effetto finale del procedimento sinteticamente esposto.

