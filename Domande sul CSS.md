1. Il linguaggio CSS aiuta a personalizzare la nostra pagina web memorizzando comandi per elementi di stile come caratteri, animazioni, colori, ecc. L'interfaccia grafica del nostro sito è ciò che media il rapporto tra utente e macchina, dunque è essenziale che sia chiara, immediata, estremamente piacevole, dinamica e accattivante.

2. I fogli di stile possono essere:

- **INTERNI**. In questo caso il codice CSS viene scritto con uno stile **_inline_** direttamente all'interno del tag che si desidera formattare utilizzando l'attributo **style**.
  I fogli di stile interni possono anche essere inseriti nell'intestazione del documento HTML all'interno dei tag <style></style>.
  Esistono una serie di differenze logiche e pratiche nell'implementazione _inline_ e quella attraverso un foglio di stile: la prima assegnerà lo stile a quello specifico elemento; assegnando, invece, uno stile nell'intestazione della pagina a un tag, tutti gli elementi dello stesso tipo assumeranno lo stesso stile;
- **ESTERNI**. Per creare un foglio di stile esterno basta inserire tutte le istruzioni CSS all'interno di un semplice file di testo che dovrà poi essere salvato con estensione **.css**. Questa soluzione realizza la perfetta separazione tra formattazione e struttura e rappresenta la tecnica **_ideale_**.

3. Per collegare un file CSS esterno alla pagina HTML basta richiamarlo nell'header del documento HTML con il tag **link**, che deve contenere:

- l'attributo **rel** che indica la relazione tra il documento HTML e il file linkato;
- l'attributo **type** che definisce il tipo di file;
- l'attributo **href** fa riferimento al percorso del file CSS da richiamare all'interno della pagina.

4. Il **_selettore_** serve per selezionare uno o più elementi della pagina cui applicare le dichiarazioni contenute tra le parentesi graffe. Mediante il **selettore di tipo** si applica uno stile a tutti i tag di un dato tipo: tutti i link, tutti i paragrafi, tutti i DIV, ecc.
   Utilizzando il **selettore di classe** è possibile definire uno o più elementi cui applicare un dato stile.

5. Per selezionare un elemento HTML specifico utilizzando un selettore di classe basterà inserire un attributo **class** nel tag interessato. All'interno del foglio CSS va inserito il nome della classe precuduto da un punto.

6. Il foglio di stile CSS funziona a cascata. Significa che le istruzioni verranno lette dal broswer dall'alto verso il basso. L'organizzazione a cascata si basa sul peso di ogni regola;questo fa in modo che, se ad un elemento vengono assegnate due proprietà identiche, ma con valori diversi, il broswer leggerà l'ultimo valore inserito.

7. La regola con peso maggiore ha la priorità su quelle con peso minore: i selettori id hanno un'importanza e una specificità maggiori rispetto ai selettori di classe.

8. La specificità è il valore che permette di definire la priorità di una regola CSS rispetto a un'altra. Il valore di specificità di una regola CSS può essere rappresentato da un numero di quattro cifre. In questo sistema numerico, l'importanza dei numeri è ordinata da sinistra a destra, quindi valori più alti indicano una maggiore specificità.
   Per ogni tipo di selettore avremo un valore di specificità diverso.

9. Dato che un documento HTML può essere immaginato come un albero con un elemento radice e tanti figli al proprio interno, i selettori di relazione gestiscono i rapporti tra gli elementi del DOM. Uno di questi selettori di relazione è quello **del discendente** che serve a selezionare tutti gli elementi che nella struttura ad albero siano discendenti di un altro elemento. Ricordiamo che un elemento è discendente di un altro se è contenuto al suo interno.

10. Il selettore universale seleziona tutti gli elementi di un documento. Si espriem con il carattere \* (asterisco).

11. Il **box-model** in CSS descrive lo spazio preso dall'elemento HTML esattamente come un riquadro. Ogni modello consiste di tre componenti: _padding_(lo spazio tra il contenuto e il border), _border_ (letteraòmemte il bordo del box) e _margin_ (lo spazio esterno al border). Tutti i componenti del box model accettano un valore in pixel da settare su 4 proprietà: top, right, bottom e left.

12. Grazie alla proprietà **box-sizing** è possibile definire la dimensione di un box in relazione a eventuali padding e bordi. Con la formattazione standard il dimensionamento di un box riguarda solo l'area di contenuto, non includendo eventuali margini, padding e bordi.

13. Con **border-box** la dimensione effettiva del box sarà quella espressa da _width_ e _height_. Il valore border-box rende il bordo l'elemento ultimo del nostro box e fa sì che la larghezza consideri padding e bordi come interni.

14. **_Display_** è la proprietà che serve per il controllo dell'impaginazione.

15. Gli elementi con **_block_** iniziano su una nuova linea e occupano tutta la larghezza dello schermo estendendosi da sinistra verso destra. Gli elementi **_inline_**, invece occupano lo spazio necessario.

16. Con la proprietà **_float_** è possibile rimuovere un elemento dal normale flusso del documento e spostarlo su uno dei lati (destro o sinistro) del suo elemento contenitore utilixzzando i valori _left_ o _right_. Il valore _inherit_ dice all’elemento a cui è applicato di ereditare il valore di float del suo elemento padre. Il valore _none_ è il valore di default e dice all’elemento di non spostarsi sotto l’effetto del float. Il contenuto che circonda l'elemento scorrerà intorno ad esso sul lato opposto rispetto a quello indicato come valore di float.

17. La proprietà **_clear_** serve a impedire che al fianco di un elemento compaiano altri elementi con il float. Si applica solo agli elementi blocco e non è ereditata.

18. Si possono cenrare gli elementi impostando la proprietà **position** dell'elemento genitore a _relative_ e quella dell'elemento figlio a _absolute_, top e left a 50%.

19. Si può nascondere un elemento utilizzando la proprietà "display:none" oppure _visibility:hidden_. Se vogliamo eliminare completamente un elemento dalla pagina, useremo la prima; se, invece, vogliamo farlo scomparire con la condizione di mantenere la posizione, useremo il CSS visibilità.

20. L'attributo _id_ è usato per identificare in modo univoco un elemento.
    Una singola classe, al contrario, può essere assegnata a più elementi, anche dello stesso tipo.

21. Gli pseudo-elementi in CSS, sono parole chiave che possono essere aggiunte ai selettori per renderli più specifici. Sono facili da riconoscere perché sono sempre preceduti da uno o due punti.

22. Gli **_pseudo-selettori_** servono per selezionare degli elementi in base a determinate condizioni. Esempio: passando il mouse su un elemento lo si vede cambiare. Molto probabilmente quello che è cambiato è lo stato dell’elemento che è passato dallo stato normale allo stato di hover. _Hover_, è una pseudo-classe, ovvero una classe che definisce il modo in cui verrà raffigurato un elemento in un determinato stato.

23. Si può personalizzare il simbolo da utilizzare come marcatore in una lista attraverso la proprietà _list-style-type_ aggiungendo determinati valori come ad esempio: **lower-alpha** per caratteri ASCII minuscoli (a ,b ,c ,d , …); **lower-greek** per lettere greche minuscole; **lower-latin** per lettere latine minuscole; **square** per avere un quadrato pieno; ecc.
