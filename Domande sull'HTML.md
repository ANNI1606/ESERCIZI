1. HTML, o **Hypertext Markup Language**, è un linguaggio di formattazione per il web che definisce la struttura delle pagine web. Può essere definito come lo scheletro della pagina web in cui gli elementi sono collegati in maniera gerarchica in una struttura ad albero.
   Il linguaggio HTML descrive la struttura di un documento web attraverso i **tag**, o marcatori, che identificano il testo come intestazione, paragrafi, elenchi, collegamenti, immagini.

2. L'ultima versione di HTML è HTML5; è molto più dinamico e include elementi multimediali. Supporta nativamente il video e l'audio e permette anche di creare giochi o animazioni.

3. Al contrario dell'HTML, XHTML è un linguaggio di markup basato su XML. La sintassi di XML è leggermente differente da quella di HTML e i processori XML sono meno indulgenti nel caso in cui siano commessi errori.

4. Il **_doctype_** serve per indicare al browser il tipo di documento di cui si tratta ed è sempre collocata all'inizio del documento. Consiste in una vera e propria dichiarazione, dello sviluppatore della pagina web, circa il linguaggio utilizzato, la versione di tale linguaggio, la lingua, ecc. Si tratta di un'istruzione indirizzata al browser affinché adotti le giuste regole per il rendering del documento.

5. Il tag che apre, e chiude, il documento è quello **_html_**, che è quindi il contenitore di tutti gli altri tag.
   Subito dopo troviamo il tag **_head_**; i link esterni che rimandano, ad esempio, a un foglio di stile CSS.
   Nel tag **_body_** è racchiuso il corpo del documento, ovvero ciò che il broswer effettivamente visualizzerà: titoli, paragrafi, immagini, suoni e quant'altro.

6. I tag HTML sono istruzioni di formattazione. I tag sono racchiusi dalle parentesi angolari (_angle brackets_ in inglese) < > e sono sempre scritti in minuscolo. La maggior parte di essi hanno un tag iniziale e uno di chiusura.
   L'elemento HTML è formato dal tag iniziale, da quello finale e dal loro contenuto.

7. I commenti all'interno del codice sono delle note inserite dallo sviluppatore, non visibili agli utenti in quanto non verranno reinderizzate dal broswer. La sintassi di un commento è la seguente: <!-- TESTO DEL COMMENTO -->.

8. Il tag HTML head è il contenitore dei metadati. Si trova tra il tag HTML <html> e i tag body <> . In questa sezione vengono inseriti tutti i meta tag in HTML per definire il titolo, gli stili, gli script e le altre informazioni.

9. L'elemento _title_ contiene il titolo della pagina che verrà visualizzato nel broswer.

10. Per collegare un file CSS esterno alla pagina HTML basta richiamarlo nell'header del documento HTML attraverso il tag **link**.

11. Uno script JavaSricpt si può collegare a un documento HTML come file esterno utilizzando il tag _script_ con all'interno il nome del file.

12. Tutti gli elementi di blocco sono di tipo contenitore (cioè hanno un tag di chiusura e uno di apertura), ne sono un esempio gli elementi **_div_**. Un elemento a blocco inizia sempre su una nuova riga e i browser aggiungono automaticamente uno spazio (un margine) prima e dopo l’elemento.
    Un elemento inline non inizia su una nuova riga.

13. I collegamenti ipertestuali si creano con il tag **_a_**. La “a” sta per ancora, e fa riferimento al fatto che il link deve fornire un ancoraggio tra più pagine/elementi.Il link consente di navigare da una pagina all'altra o da un sito all'altro, senza utilizzare la tastiera del computer. Un link può linkare qualsiasi risorsa nell'indirizzo di destinazione ( es. altre pagine web, immagini, documenti, ecc. ).

14. Gli attributi HTML memorizzano informazioni aggiuntive in un tag HTML. Esempio di attributi sono: **id**, che identifica in modo univoco un elemento HTML; **class** si usa per assegnare un elemento a una o più classi; **style** definisce lo stile di un elemento HTML e può quindi impostare il colore, il font o la dimensione del carattere.

15. Possiamo inserire immagini nel documento HTML utilizzando il tag **img** seguito dall'attribuito **src** che specifica qual'è il percorso dell'immagine.

16. Il tag **_alt_** delle immagini è il cosiddetto testo alternativo per un'immagine. Serve a descrivere un'immagine o ciò che essa rappresenta. Il tag alt delle immagini o attributo alt è il cosiddetto testo alternativo per un'immagine. Serve a descrivere un'immagine o ciò che essa rappresenta. Nasce per dare la possibilità agli utenti ipovedenti di utilizzare il lettore dello schermo durante la navigazione.

17. Le liste HTML più utilizzate sono di due tipologie: la lista ordinata ( **_ol_** ) e la lista non ordinata ( **_ul_** ). Le singole voci delle liste sono espresse con il tag **_li_** (list item).

18. Il tag **_div_** può contenere paragrafi, immagini, titoli, ecc.; può contenere, dunque, qualsiasi tipo di elemento HTML. L'utilizzo appropriato consente una chiara separazione e organizzazione dei contenuti. Importante: il tag div ha comportamento bloccante.
    Il tag **_span_** contrassegna una parte di testo o, in genere, di documento, a cui vogliamo dare una caratteristica particolare, magari utilizzando un linguaggio di stile come il CSS. Il tag _span_ non cambia la struttura o il flusso del documento.
    In sintesi, la differenza principale tra i due tag riguarda la loro natura bloccante o di linea e il loro utilizzo. Entrambi gli elementi sono fondamentali nella creazione di layout e nell'applicazione di stili in HTML, ma vengono utilizzati in contesti diversi a seconda delle esigenze specifiche del progetto.

19. Il tag **_iframe_** consente di incorporare implicitamente contenuti aggiuntivi in un documento HTML. Si utilizza soprattutto per integrare oggetti di altri siti web nella propria pagina online, ad esempio, video di YouTube o Google Maps, plug-in dei social media o altre applicazioni specifiche.
    Perché il frame sia eseguito correttamente, vanno specificati i seguenti attributi:

- src: fonte del contenuto, specificato sotto forma di URL.
- width: larghezza del frame, specificata in pixel o in percentuale.
- height: altezza del frame, specificata in pixel o in percentuale.
- name: nome del frame specifico.
- sandbox: associa il frame ad alcune misure precauzionali.
- srcdoc: contiene il codice HTML da visualizzare nell’iframe.

20. HTML5 consente di manipolare i contenuti multimediali utilizzando i tag HTML <audio> e <video> specificando sempre l'url del file. L’uso del tag <video> crea un lettore video HTML5 nativo e consente ulteriori opzioni per la personalizzazione e la visualizzazione dei contenuti video utilizzando gli attributi specifici.

21. Il **box model** regola la presentazione dei vari elementi di una pagina. Una pagina HTML non è altro che un insieme di box rettangolari, che si tratti di elementi blocco o di elementi inline. Le regole che gestiscono l'aspetto visuale degli elementi non sono state introdotte con i CSS, ma fanno parte del normale meccanismo di rendering di un documento HTML. Quando realizziamo una pagina HTML senza fogli di stile, è il browser ad applicare le sue impostazioni predefinite. Per esempio, introdurrà un certo margine tra un titolo e un paragrafo o tra due paragrafi. Con i CSS possiamo controllare con precisione tutti questi aspetti andando a modificare le impostazioni di default applicate dal browser.

22. Il contenitore della tabella è il tag <table> che abbraccerà tutti gli altri. Il tag <caption> rappresenta il titolo della tabella. Il tag <thead> ha al suo interno le righe, definite col tag <tr>, e le colonne, all’interno del tag <th>. Il corpo della tabella è racchiuso col tag <tbody></tbody>, costituito dai dati nelle singole celle, inseriti nel tag <td></td>. Infine, alla base della tabella troviamo il <tfoot></tfoot>, che delinea il footer della tabella e in cui possono essere inseriti dei dati di riepilogo. Lo stile della tabella deve essere aggiunt sempre attraverso l’inserimento di un foglio CSS.

23. **_Vedi sopra_**

24. L'accessibilità HTML è un aspetto essenziale dello sviluppo web. Si riferisce alla pratica di progettare in modo da rendere i contenuti web accessibili alle persone con disabilità e rendere il web più inclusivo. L'accessibilità non è solo un requisito legale, ma anche un imperativo morale. Garantendo l'accessibilità web, si può migliorare l'esperienza dell'utente, raggiungere un pubblico più vasto e incoraggiare l'innovazione. Pertanto, è fondamentale assicurarsi che i contenuti siano accessibili a tutti, indipendentemente dalle loro capacità.
    Esistono diverse best practice per l'accessibilità HTML, tra cui:

- Utilizzare l'**HTML semantico**. Si riferisce all'uso di elementi html che trasmettono significato. Alcuni esempi di elementi HTML semantici includono intestazioni, elenchi e tabelle;

- Fornire **testo alternativo** per le immagini. Le immagini rappresentano una parte importante dei contenuti Web. Fornendo un testo descrittivo per le immagini (**_alt_**), puoi garantire che gli utenti con disabilità possano comprenderne il contenuto.

- Utilizzare **ruoli e attributi ARIA**. I ruoli e gli attributi ARIA (Accessible Rich Internet Applications) forniscono informazioni aggiuntive sullo scopo e sulla struttura degli elementi HTML. Alcuni esempi di ruoli ARIA includono "pulsante", "collegamento" e "casella di riepilogo".

- Garantire **l'accessibilità della tastiera**. L'accessibilità tramite tastiera è importante per gli utenti che non possono utilizzare il mouse. Ciò include la garanzia che tutti i collegamenti e i pulsanti possano essere attivati ​​utilizzando il tasto "Tab" e la fornitura di scorciatoie da tastiera per le azioni frequenti.

- Fornire **didascalie e trascrizioni per i video**. Quanto detto per le immagini vale anche per i video. Aggiungere didascalie e trascrizioni, come ad esempio i sottotitoli, è una best practice per garantire a tutti l'accesso ai contenuti multimediali.

- Usare il **contrasto di colore**. Il contrasto dei colori è importante per gli utenti ipovedenti o daltonici. Le linee guida per l'accessibilità dei contenuti Web (WCAG) consigliano un rapporto di contrasto minimo di 4,5:1 per il testo normale e 3:1 per il testo di grandi dimensioni.

25. ARIA è l’acronimo di _Accessible Rich Internet Applications_. Si tratta di un insieme di attributi speciali pubblicati dal W3C che possono essere aggiunti agli elementi HTML per rendere le pagine Web e le applicazioni più accessibili alle persone con disabilità. Questi attributi forniscono descrizioni aggiuntive per le tecnologie assistive (AT) come i lettori di schermo.
    I ruoli vengono aggiunti tramite l’attributo **_role_**. I ruoli dei punti di riferimento semplificano la navigazione suddividendo la pagina in diverse sezioni, come ricerca, banner, navigazione, applicazione e così via. I ruoli widget vengono utilizzati per dare significato agli elementi come collegamento, pulsante, casella di controllo e così via. Gli attributi del widget consentono di interagire con la pagina web, ad esempio, possono aprire e chiudere schede, compilare moduli e così via. I ruoli del documento contengono descrizioni delle strutture che organizzano il contenuto della pagina, come img, elenco, riga, barra degli strumenti e così via.

26. Per modulo si intende quella parte di pagina html in grado di permettere all'utente di immettere dati in diversi elementi. Il termine tecnico che riassume tutti questi elementi è **form**. Per la creazione di un form utilizziamo l'omonimo tag _form_. Scopo di questo tag è di fare da contenitore ad una serie di altri tag che costituiranno gli specifici controlli del modulo.
    I principali attributi del tag form sono:

- **method**. Specifica il metodo di invio dei dati ed accetta i valori get o post.
- **action**. Controllerà ed elaborerà i dati raccoltri tramite il form;
- **target**. Specifica se il frutto dell'elaborazione verrà mostrata nella stessa finestra oppure in un altra.
  Una volta definito un form sarà necessario aggiungere una serie di tag annidiati al suo interno, attraverso i quali sarà possibile creare i vari elementi per l'interazione con l'utente come, ad esempio, caselle di testo o menu di selezione.
  Il tag _button_ genera un pulsante che può svolgere diverse azioni a seconda del valore dell'attributo _type_:
- **submit** è usato per l'invio del modulo;
- **reset** è usato per azzerare il modulo.
  Il tag _select_ crea una casella di riepilogo a scorrimento, chiamata in gergo selectbox, al cui interno sono annidiate le diverse <option> tra cui l'utente può scegliere;
  Il tag _textarea_ genera un'area di testo in cui è possibile andare a capo e viene utilizzata per inserire descrizioni, commenti o comunque testi piuttosto lunghi.

27. Il tag _input_ genera la maggior parte degli elementi dei form HTML, a seconda del type specificato:

- **text** è utilizzato per creare caselle di testo in cui l'utente può scrivere del contenuto su "singola linea";
- **file** è utilizzato per creare caselle di selezione di file in locale al fine di poterli trasmettere al server remoto;
- **radio** - permette di creare un gruppo di opzioni al cui interno deve essere fatta una scelta (non ammette scelte multiple);
- **checkbox** permette di creare un gruppo di opzioni al cui interno devono essere fatta delle scelte (ammette scelte multiple);
- **button** permette di creare bottoni "neutri" ai quali, cioè, può essere associata un'azione mediante Javascript;
- **submit** crea bottoni di invio attraverso i quali viene, appunto inviato e processato il form;
- **image** inserisce immagini "attive" all'interno del modulo che fungeranno da bottoni;
- **reset** crea bottoni per il reset del form;
- **color**;
- **date** consente di scegliere una data fornendo anche un piccolo calendario navigabile;
- **datetime** dà la possibilità all'utente di scegliere oltre alla data anche l'orario;
- **email**;
- **number** con cui è possibile far accettare al campo di input solo valori numerici. Attraverso gli attributi min e max, poi, si può anche definire l'intervallo in cui deve essere contenuto il valore;
- **range** consente di far selezionare all'utente un valore numerico compreso tra due intervalli attraverso l'utilizzo di uno slider;
- **search** è utilizzato per i campi di ricerca;
- **time** consente di selezionare un orario;
- **url** per inserire indorizzi web.
  I tag input prevedono (oltre a name) due attributi principali:
  **_type_**: che definisce il tipo di input;
  **_value_**: definisce il valore dell'input; nei campi "text" è facoltativo e, se previsto, rappresenta una sorta di valore predefinito che gli utenti potranno modificare.

28. Il protocollo HTTP è stato progettato per gestire le connessioni tra un client ed un server attraverso diversi metodi. Con il metodo GET i dati vengono trasmessi attraverso la URL della risorsa mediante l'aggiunta di una _Query String_ sotto forma di coppie nome/valore. Con il metodo POST, invece, i dati vengono inviati all'interno delle intestazioni HTTP.

29. Gli attributi _required_ e _pattern_ consentono di simulare due aspetti molto importanti da tenere in considerazione quando si tratta di validazione dei dati. L'attributo required, come ci suggerisce il nome, ci consente di impedire l'invio del modulo se i campi obbligatori non sono stati compilati. L'attributo pattern può essere utilizzato in combinazione con l'attributo required. Esso, infatti, consente di definire delle espressioni regolari (nel formato supportato da JavaScript) per validare i dati dei moduli.
