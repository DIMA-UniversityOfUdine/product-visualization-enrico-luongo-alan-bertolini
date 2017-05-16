<meta charset="utf-8">

# DESCRIZIONE

L'idea è stata quella di creare un configuratore 3D di sedie, che mostra un modello 3D configurabile all'interno di un ambiente chiuso.
Il progetto fa uso delle librerie di Three.js contenute in lib, delle textures per i modelli contenute nella cartella textures,
un file index.html contenente tutto il codice.


----------------------------------------------------------------------------------------------------------------------------

# RISULTATI
Il risultato finale è un configuratore 3D che permette di cambiare materiali e colori alle varie parti del modello (guscio, imbottitura,
contorni e cuscini); inoltre è possibile sia ruotare la telecamera attorno all'oggetto, sia facendo lo zoom;
in modo da vedere il prodotto da più angolazioni. I movimenti sono stati limitati in modo da non oltrepassare i limiti della stanza ed in modo
da non entrare nell'oggetto.
E' stata creata una cubemap di un ambiente chiuso attorno al modello 3D, che viene riflessa sull'oggetto. 

# IMMAGINI

![Example 1](pictures/Immagine1.png)

![Example 2](pictures/Immagine2.png)

![Example 3](pictures/Immagine3.png)

--------------------------------------------------------------------------------------------------------------------------------

# PROCESSO

I modelli sono stati scaricati già creati in formato OBJ e importati con il loader di THREE.js.
Per scaricare e modificare le textures è stato usato il software Substance Player.
Per gli shader è stato deciso di scriverli unendo quelli degli esempi delle lezioni e apportando le modifiche necessarie ad adattarli al progetto.
Per l'ambiente è stato scelto di creare una cubemap di un salotto in modo da vedere gli effetti di riflessione sull'oggetto.


<!-- Markdeep: -->

 