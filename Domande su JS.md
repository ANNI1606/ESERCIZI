1. JavaScript è un popolare **linguaggio di scripting** che consente di aggiungere funzionalità interattive e altri contenuti dinamici alle pagine web. Esempi ben noti di contenuti JavaScript sono moduli compilabili, slideshow di gallerie fotografiche e grafica animata.
   JavaScript è utilizzato anche per lo sviluppo di giochi basati su broswer web e applicazioni mobile.

2. Sia Java che JavaScript sono linguaggi nati per sviluppare pagine e applicazioni web. Tuttavia, hanno differenze distintive, tra cui:

- **Programmazione orientata agli oggetti**: Java è un linguaggio di programmazione orientato agli oggetti. JavaScript è un linguaggio di scripting basato sugli oggetti.
- **Sintassi**: La sintassi di JavaScript è più semplice per la maggior parte degli utenti.
- **Compilazione**: Java è un linguaggio compilato, mentre JavaScript è un linguaggio interpretato linea per linea in fase di esecuzione; i linguaggi compilati tendono ad essere più veloci, ma i linguaggi interpretati tendono ad essere più flessibili.
- **Ambiente**: È possibile utilizzare le applicazioni Java essenzialmente in qualsiasi ambiente, eseguendole in macchine virtuali o in browser; JavaScript è solo per i browser.
- **Utilizzo della memoria**: Java richiede più memoria di JavaScript; questo rende JavaScript preferibile per le pagine e le applicazioni web.

3.
4. Il DOM, o _Document Object Model_, agisce come interfaccia tra un linguaggio di programmazione come JavaScript e un documento sottostante – in particolare, documenti HTML e XML.
   DOM è definito come _“un’interfaccia indipendente dalla piattaforma e dal linguaggio che permette a programmi e script di accedere dinamicamente e aggiornare il contenuto, la struttura e lo stile di un documento”_. I documenti consistono in un insieme di singoli elementi e proprietà (testo, pulsanti, link, ecc.).

5. Le variabili sono dichiarate utilizzando la parola chiave **_var_**. Non è necessario che abbiano un valore assegnato al momento della dichiarazione, anche se viene fatto spesso.

6. Il linguaggio JavaScript comprende cinque tipi di dato semplici o primitivi: numeri, stringhe, booleani, null e undefined. JavaScript prevede anche un tipo di dato complesso, gli oggetti (object), al cui interno ricadono altri tipi di dato tra i quali gli array JavaScript, le espressioni regolari e le funzioni in JavaScript.

7. Le funzioni sono blocchi di codice che eseguono compiti specifici. Le funzioni sono definite utilizzando la seguente sintassi:
   **function function_name()**.
   In seguito la funzione dovrà essere eseguita.

8. Gli oggetti sono contenitori che possono racchiudere proprietà, metodi o entrambi. Si possono creare in diversi modi con JavaScript.
   In primo luogo, si può seguire l’approccio _object literal_, dichiarando l'oggetto e poi elencandone tutte le proprietà all'interno di parentesi graffe.
   Un secondo metodo è usare l'operatore **_new_**. Questo operatore deve essere seguito da una funzione particolare che prende il nome di **costruttore**. Una funzione costruttore ha lo scopo di inizializzare l'oggetto appena creato. Esempio: _let x = new Object();_.
   L'ultimo modo con cui è possibile creare oggetti in Javascript consiste nell'utilizzo dei prototipi. Quasi tutti gli oggetti in Javascript hanno un secondo oggetto associato: il **prototipo**. Gli oggetti, oltre ad avere le loro proprietà, ereditano anche le proprietà del prototipo. Ad esempio, se un oggetto A ha le proprietà x e y, se creiamo un oggetto B che ha come prototipo A, allora B avrà anch'esso le proprietà x e y ereditate da A. Per poter far questo bisogna usare la funzione **_Object.create_**.

9. Gli operatori in JavaScript sono simboli o parole chiave che permettono di eseguire operazioni specifiche tra variabili, costanti o valori letterali. Essi sono fondamentali nella programmazione, poiché consentono di manipolare i dati, confrontare valori e controllare il flusso di esecuzione del codice. Gli operatori si dividono in diverse categorie:

- **aritmetici**, utilizzati per eseguire operazioni matematiche, come addizione, sottrazione, moltiplicazione e divisione. I simboli sono per, diviso, più e meno, a cui va aggiunto il resto, indicato con il %;

- **condizionali**, che permettono di confrontare valori e stabilire relazioni tra di essi, come maggiore, minore, uguale e disuguale. La sintassi utilizzata è la seguente:

  > maggiore
  > < minore
  > = maggiore o uguale
  > <= minore o uguale
  > L'operatore di **_disuguaglianza !==_** confronterà sia i valori che i tipi, mentre != confronterà esclusivamente i valori.
  > Questi caratteri saranno utili anche per valutare ipotesi;

- **logici**, utilizzati per creare espressioni booleane, combinando condizioni con operazioni logiche come and, or e not. I simboli usati nel codice sono: **&& per and, || per or, ! per not**;

- **di assegnazione**, servono per assegnare valori a variabili;

- **di confronto**, usati per confrontare i valori e i tipi di due operandi.

10. Gli **_array_** sono elenchi di dati a una o più dimensioni.
    Nel caso di array di una dimensione possiamo definirli semplicemente così:

let valori = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9];.

11. Sono operatori condizionali. **== uguale** (il segno è doppio) confronta solamente i valori, mentre l'operatore **===** (triplo uguale) confronta sia i valori che i tipi.

12. I commenti possono essere di una singola riga: ed iniziano con // oppure multilinea: /_ ... _/ .

13. I cicli vengono utilizzati in JavaScript per eseguire attività ripetute in base a una condizione. Le condizioni in genere restituiscono **_true_** o **_false_**. Un ciclo continuerà a funzionare fino a quando la condizione da noi definita ritorna false.

14. Le variabili _var_ possono essere aggiornate o ri-dichiarate dentro il loro ambito; le variabili _let_ possono essere aggiornate ma non re-dichiarate; le variabili _const_ non possono essere né aggiornate né re-dichiarate.

15. La pratica di codifica comunemente accettata richiede di dichiarare le variabili prima o contemporaneamente alla definizione.
    JavaScript, tuttavia, permette alle variabili di essere dichiarate dopo che sono state definite o utilizzate. Usando una caratteristica chiamata hoisting, JavaScript sposta le dichiarazioni all’inizio dello script o della funzione corrente. Mentre l’hoisting può semplificare la programmazione permettendo ad un programmatore di correggere una mancata dichiarazione senza dover scorrere indietro il codice, dichiarare le variabili dopo l’utilizzo non è coerente con le best practice della programmazione.

16. La **_garbage collection_** è un processo di osservazione della memoria Heap, che identifica o meglio “marchia” (si parla infatti di _marking process_) gli oggetti irraggiungibili li distrugge e compatta la memoria liberata per un uso successivo più efficiente.
    Il primo passo nel processo è chiamato **marcatura** (marking). Qui il garbage collector identifica quali pezzi di memoria sono in uso e quali no. Il secondo passo è la **cancellazione** normale dove vengono rimossi gli oggetti senza riferimento e lasciati gli oggetti referenziati e i puntatori allo spazio libero.

17. Un **callback** è una funzione passata come argomento di un'altra funzione.

18. **SELEZIONARE UN ELEMENTO NEL DOM**.
    **_querySelector('#selettore')_**
    **_querySelectorAll('selettore')_**
    Entrambi questi metodi accettano come parametro un **selettore CSS** che verrà utilizzato per selezionare gli elementi all’interno dell’html.
    **MODIFICARE LO STILE DI UN ELEMENTO**
    title.style.color = 'yellow';
    title.style.backgroundColor = 'black'
    Ogni oggetto catturato sul DOM avrà la proprietà “style”, che ci darà accesso a tutte le proprietà CSS che possiamo modificare.
    L’unica particolarità a cui dobbiamo fare attenzione è che nel linguaggio CSS le proprietà composte da più parole sono scritte in _kebab-case_ (come ad esempio background-color): questo in JavaScript non è possibile perchè il simbolo “-” viene considerato come l’operatore matematico meno. Quindi dovremo scrivere le proprietà CSS in _camelCase_, questo vuol dire che: background-color diventerà backgroundColor; font-size diventerà fontSize e via dicendo.
    **MODIFICARE LE CLASSI DI UN ELEMENTO**
    Una volta selezionato un elemento, possiamo accedere alla proprietà **_classList_** e utilizzare 4 metodi:

- **add()**. Aggiungere una classe
- **remove()**. Rimuovere una o più classi
- **toggle()**. Aggiungere una classe se questa non è presente o a toglierla se questa è presente.
- **replace()**. Sostituire una classe con una nuova classe, se e solo se la prima è presente all’interno dell’elemento.
  **MODIFICARE IL CONRENUTO DI UN ELEMENTO**
  Per modificare il contenuto di un elemento HTML dobbiamo modificare una proprietà presente all’interno di un elemento del DOM ovvero **_innerHTML_**. Questa proprietà ci permette di inserire all’interno di un elemento del DOM non solo del semplice testo ma, addirittura, del codice html.

19. In JavaScript, gli eventi rappresentano tutto ciò che succede quando l'utente o il browser manipola una pagina. Anche il caricamento di una pagina web è un evento; cliccare su un pulsante è un evento; muovere il mouse è un evento. Per rilevare gli eventi e reagire nel modo che desideri ci si affida ai gestori di eventi. JavaScript usa il metodo **_addEventListener_**. La maggior parte degli eventi viene chiamata su uno specifico elemento DOM.

20. Tutte le azione predefinite possono essere prevenute se vogliamo gestire gli eventi esclusivamente tramite JavaScript.
    Per prevenire un’azione predefinita si possono usare **_event.preventDefault()_** oppure **_return false_**. Il secondo metodo è valido solo con gestori assegnati con on<event>.
    Se l’azione predefinita è stata prevenuta, il valore di _event.defaultPrevented_ diventa _true_, altrimenti è _false_.

21. Le espressioni regolari sono sequenze di caratteri (stringhe), che possono identificare insiemi di stringhe molto più complessi.
    In JavaScript anche le espressioni regolari sono degli oggetti, e vanno dichiarati come costanti (con const) o come variabili (con var o let). Gli elementi di partenza per usare le espressioni regolari sono le parentesi quadre, la barra inversa, il punto, il punto interrogativo, l’asterisco, il più, il dollaro, la lettera d (minuscola e maiuscola) la lettera w (minuscola e maiuscola) e il caret (accento circonflesso):
    **[ ]** includono i caratteri da analizzare;
    \
    **. ? \*** selezionano parti della stringa;
    **^ $** indicano inizio e fine stringa;
    **d** indica le cifre da 0 a 9;
    **w** indica i caratteri alfabetici;
    **W** tutto ciò che non è carattere alfabetico;
    **D** tutto ciò che non è cifra.

22. Il costrutto **_try...catch_** per prima cosa esegue il codice all’interno del blocco _try {...}_. Se non si verifica alcun errore, allora _catch(err)_ viene ignorato; se si verifica un errore, allora l’esecuzione del resto del codice all’interno del try viene interrotta, e si passa all’esecuzione del codice all’interno di catch(err).

23. Le promise introducono per certi versi la programmazione asincrona. Le promise sono state concepite per rappresentare operazioni incomplete in un preciso momento a runtime, che saranno però complete in futuro. Si tratta di un componente adottato nel caso di elaborazioni asincrone. Gli stati del promise sono tre:

- Resolved: quando il valore che rappresenta diviene disponibile, cioè quando restituisce il valore.
- Rejected: quando l'attività asincrona associata non restituisce un valore.
- Pending: quando non è né risolta né rigettata, cioè la richiesta di esecuzione di un'attività asincrona è partita ma non abbiamo ancora ricevuto un risultato.
  La sintassi della promise è questa:
  _var promise = new Promise(handler);_
  Il promise handler agisce su due canali, prendendo due funzioni come argomenti.
  Il primo parametro corrisponde alla funzione da chiamare quando il valore restituito dall'operazione asincrona è disponibile. Il valore restituito dall’attività asincrona viene passato alla funzione in questione.
  Il secondo corrisponde alla funzione da invocare quando la promise non può essere risolta, ad esempio se si è verificato un errore o se il valore restituito non è considerato valido.
  Quindi avremo:
  var promise = new Promise(function(resolve, reject) {

if (statement) {
resolve(value);
} else {
reject(reason);
}
});

24. Per come è progettato, JavaScript è un linguaggio di programmazione sincrono. Ciò significa che quando il codice viene eseguito, JavaScript inizia dalla parte superiore del file ed esegue il codice riga per riga, fino al completamento.
    In termini tecnici, viene definita a filo unico, ovvero **_single-threaded_**.
    Tutte le operazioni, dall'elaborazione dell'input dell'utente alla visualizzazione del risultato sulla pagina web, sono affidate a questo singolo thread, che scandisce i tempi. L’esecuzione è, quindi, detta sincrona.
    Per molti impieghi, la sincronia non è un buon modo di eseguire il software. Per questo motivo, si utilizza la programmazione asincrona: alcune funzioni vengono gestite al di fuori del single thread, in modo da evitare blocchi o altri problemi.
    Sono esempi di funzioni asincrone **setTimeout()** o **fetch()**.

25. Async/Await è un modo di scrivere promesse che ci consente di scrivere codice asincrono in modo sincrono. Per utilizzare async/await dobbiamo anteporre async alla funzione. Questo non la rende una funzione asincrona, ma ci permette semplicemente di usare await al suo interno.

26. In JavaScript, la parola chiave this ci consente di:

- Riutilizzare funzioni in diversi contesti di esecuzione. Vale a dire che una funzione, una volta definita, può essere chiamata per oggetti diversi usando la parola chiave this.
- Identificare l'oggetto nel contesto di esecuzione corrente quando chiamiamo un metodo.

27. L’ereditarietà rappresenta un meccanismo che consente di definire delle classi figlie che ereditano dalle classi padre tutti gli attributi. Si definisce "classe figlia" quella che eredita tutte o parte delle proprietà e dei metodi definiti nella classe padre. In questo modo, si viene a formare una gerarchia. La "classe figlio" riutilizza tutti i campi e i metodi della classe genitore.

28. In JavaScript esistono molte operazioni per lavorare sugli elementi dell’array, dette **metodi**, che consentono di eseguire operazioni come l'aggiunta o la rimozione di elementi, la ricerca, la trasformazione e molto altro ancora. Tra questi, **_push(), pop(), shift(),_** e **_unshift()_** per aggiungere o rimuovere elementi dall'inizio o dalla fine dell'array JavaScript, oppure **_sort()_** e **_reverse()_** per ordinare gli elementi all'interno dell'array.
