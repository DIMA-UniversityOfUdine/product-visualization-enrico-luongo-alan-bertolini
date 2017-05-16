<meta charset="utf-8">

# 06/05/2017
Consultati vari visualizzatori 3D online.
Raccolto prime idee.

# 07/05/2017
Scelto come procedere per svolgere il progetto e suddiviso il lavoro in varie parti.

# 08/05/2017
Scelto i modelli da usare e scaricati modelli già creati.
Importati i modelli in una scena di prova con i loader di THREE.js.

# 09/05/2017
Scelte, scaricate e modificate le texture da applicare ai modelli.
Applicate le texture ai modelli.

# 10/05/2017
Iniziato a creare la scena, aggiunte le luci.
Consultati gli shader degli esempi delle lezioni.

# 11/05/2017
Creati gli shader unendo quelli degli esempi delle lezioni e modificati per adattarli al progetto.

# 12/05/2017
Creata la cubemap e aggiunta alla scena.
Creato l'ambiente che ospiterà la cube map.
Modificati gli shader per ospitare tre luci.

# 13/05/2017
Aggiunti i modelli alla scena.
Modificati gi shader per la displacement map e la environment light.

# 15/05/2017
Risolto un problema riguardante le texture utilizzate: le texture con roughness pari a 0 non riflettevano 
la luce e apparivano completamente nere. Inizialmente abbiamo pensato che fosse un problema delle texture,
poichè se le sostituivamo con le texture usate negli esempi delle lezioni, il problema non si presentava;
ma poi ci siamo accorti che nelle funzioni degli shader, quando la roughness era 0, il risultato veniva 
moltipicato per 0 annullando il risultato.  

# 16/05/2017
Ultime modifiche agli shader e alle luci, aggiunta di altri materiali ai modelli. 
Risolto un problema che impediva il rendering del modello all'apertura della pagina.

<!-- Markdeep: -->