
# MkDocs GLightbox
Qui trovi la [documentazione ufficiale](https://blueswen.github.io/mkdocs-glightbox/ "MkDocs GLightbox")


## Immagine con Titolo e descrizione
![bla bla](../img/test_gallery/01.jpg "immagine di prova"){ data-title="bla bla." data-description="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean sit amet sapien nibh. " }

## immagine semplice
![pippo pippo](../img/test_gallery/02.jpg "immagine di prova2")


## Galleria 
![bla bla](../img/test_gallery/01.jpg "immagine di prova"){data-gallery="Galleria pippo pippo" data-title="bla bla." data-description="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean sit amet sapien nibh. " }

![bla bla](../img/test_gallery/02.jpg "immagine di prova"){data-gallery="Galleria pippo pippo" data-title="bla bla." data-description="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean sit amet sapien nibh. " }

## Galleria immagini resize
![bla bla](../img/test_gallery/01.jpg "immagine di prova" ){data-gallery="Galleria pippo pippo" data-title="bla bla." data-description="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean sit amet sapien nibh." class="resized33" }
![bla bla](../img/test_gallery/02.jpg "immagine di prova" ){data-gallery="Galleria pippo pippo" data-title="bla bla." data-description="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean sit amet sapien nibh." class="resized33"}
![bla bla](../img/test_gallery/03.jpg "immagine di prova" ){data-gallery="Galleria pippo pippo" data-title="bla bla." data-description="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean sit amet sapien nibh." class="resized33"}

## Modifiche al CSS

Ho aggiunto al CSS una serie di regole per ridimensionare le immagini dal 10% al 75% per usarle ti basta aggiungere la clsse css al codice dell'immagine **class="resizedXX"**

### Esempio 

![bla bla](../img/test_gallery/03.jpg "immagine di prova" ){ class="resized33" data-title="bla bla." data-description="Lorem ipsum dolor sit amet" class="resized33"}

```
![bla bla](../img/test_gallery/03.jpg "immagine di prova" ){ class="resized33" data-title="bla bla." data-description="Lorem ipsum dolor sit amet" class="resized33"}
```


```
/*Ridimensiona immagine*/
img.resized10 { width: 10%; height: auto; margin:1px; }
img.resized15 { width: 15%; height: auto; margin:1px; }
img.resized20 { width: 20%; height: auto; margin:1px; }
img.resized25 { width: 24%; height: auto; margin:1px; }
img.resized33 { width: 32%; height: auto; margin:1px; }
img.resized35 { width: 33%; height: auto; margin:1px; }
img.resized50 { width: 48%; height: auto; margin:1px; }
img.resized75 { width: 75%; height: auto; margin:1px; }	
```
