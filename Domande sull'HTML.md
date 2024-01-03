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
