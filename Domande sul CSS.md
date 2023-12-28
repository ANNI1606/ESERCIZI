1. Il linguaggio CSS aiuta a personalizzare la nostra pagina web memorizzando comandi per elementi di stile come caratteri, animazioni, colori, ecc. L'interfaccia grafica del nostro sito è ciò che media il rapporto tra utente e macchina, dunque è essenziale che sia chiara, immediata, estremamente piacevole, dinamica e accattivante.

2. I fogli di stile possono essere:

- **INTERNI**. In questo caso il codice CSS viene scritto con uno stile **_inline_** direttamente all'interno del tag che si desidera formattare utilizzando l'attributo **style**. Esempio: <p style="color: #FF0000;">Testo rosso</p>.
  I fogli di stile interni possono anche essere inseriti nell'intestazione del documento HTML all'interno dei tag <style></style>.
  Esistono una serie di differenze logiche e pratiche nell'implementazione _inline_ e quella attraverso un foglio di stile: la prima assegnerà lo stile a quello specifico elemento; assegnando, invece, uno stile nell'intestazione della pagina a un tag, tutti gli elementi dello stesso tipo assumeranno lo stesso stile;
- **ESTERNI**. Per creare un foglio di stile esterno basta inserire tutte le istruzioni CSS all'interno di un semplice file di testo che dovrà poi essere salvato con estensione **.css**. Questa soluzione realizza la perfetta separazione tra formattazione e struttura e rappresenta la tecnica **_ideale_**.

3. Per collegare un file CSS esterno alla pagina HTML basta richiamarlo nell'header del documento HTML attraverso il tag **link** in questo modo:
<link rel="stylesheet" type="text/css" href="style.css">.

Analizziamo il tag **link**:

- l'attributo **rel** indica la relazione tra il documento HTML e il file linkato;
- l'attributo **type** definisce il tipo di file;
- l'attributo **href** fa riferimento al percorso del file CSS da richiamare all'interno della pagina.

4. Il **_selettore_** serve per selezionare uno o più elementi della pagina cui applicare le dichiarazioni contenute tra le parentesi graffe. Mediante il **selettore di tipo** si applica uno stile a tutti i tag di un dato tipo: tutti i link, tutti i paragrafi, tutti i DIV, ecc.
   Utilizzando il **selettore di classe** è possibile definire uno o più elementi cui applicare un dato stile.

5. Per selezionare un elemento HTML specifico utilizzando un selettore di classe basterà inserire un attributo **class** nel tag interessato. All'interno del foglio CSS va inserito il nome della classe precuduto da un punto.

6. Il foglio di stile CSS funziona a cascata. Significa che le istruzioni verranno lette dal broswer dall'alto verso il basso. L'organizzazione a cascata si basa sul peso di ogni regola;questo fa in modo che, se ad un elemento vengono assegnate due proprietà identiche, ma con valori diversi, il broswer leggerà l'ultimo valore inserito.

7. La regola con peso maggiore ha la priorità su quelle con peso minore: i selettori id hanno un'importanza e una specificità maggiori rispetto ai selettori di classe.

8. La specificità è il valore che permette di definire la priorità di una regola CSS rispetto a un'altra. Il valore di specificità di una regola CSS può essere rappresentato da un numero di quattro cifre. In questo sistema numerico, l'importanza dei numeri è ordinata da sinistra a destra, quindi valori più alti indicano una maggiore specificità.
   Per ogni tipo di selettore avremo un valore di specificità diverso.

9. Dato che un documento HTML può essere immaginato come un albero con un elemento radice e tanti figli al proprio interno, i selettori di relazione gestiscono i rapporti tra gli elementi del DOM. Uno di questi selettori di relazione è quello **del discendente** che serve a selezionare tutti gli elementi che nella struttura ad albero siano discendenti di un altro elemento. Ricordiamo che un elemento è discendente di un altro se è contenuto al suo interno. Di seguito un esempio:
codice CSS:
div p{
color:yellow;
}
codice HTML:
<div>
<p>Questo sarà di colore giallo</p>
</div>.

10. Il selettore universale seleziona tutti gli elementi di un documento. Si espriem con il carattere \* (asterisco).

11. Il **box-model** in CSS descrive lo spazio preso dall'elemento HTML esattamente come un riquadro. Ogni modello consiste di tre componenti: _padding_(lo spazio tra il contenuto e il border), _border_ (letteraòmemte il bordo del box) e _margin_ (lo spazio esterno al border). Tutti i componenti del box model accettano un valore in pixel da settare su 4 proprietà: top, right, bottom e left.

12. Grazie alla proprietà **box-sizing** è possibile definire la dimensione di un box in relazione a eventuali padding e bordi. Con la formattazione standard il dimensionamento di un box riguarda solo l'area di contenuto, non includendo eventuali margini, padding e bordi.

13. Con **border-box** la dimensione effettiva del box sarà quella espressa da _width_ e _height_. Il valore border-box rende il bordo l'elemento ultimo del nostro box e fa sì che la larghezza consideri padding e bordi come interni.
