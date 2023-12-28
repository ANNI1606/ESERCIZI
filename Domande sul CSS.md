1. L'acronimo CSS sta per &#8220**Cascading Style Sheet** &#8221 ovvero &#8220foglio di stile a cascata&#8221 ; significa che il nostro foglio CSS verrà letto dal browser, letteralmente, dall’alto verso il basso. Il linguaggio CSS aiuta a personalizzare la nostra pagina web memorizzando comandi per elementi di stile come caratteri, animazioni, colori, ecc. L'interfaccia grafica del nostro sito è ciò che media il rapporto tra utente e macchina, dunque è essenziale che sia chiara, immediata, estremamente piacevole, dinamica e accattivante.

2. I fogli di stile possono essere:

- **INTERNI**. In questo caso il codice CSS viene scritto con uno stile **_inline_** direttamente all'interno del tag che si desidera formattare utilizzando l'attributo **style**. Esempio: <p style="color: #FF0000;">Testo rosso</p>.
  I fogli di stile interni possono anche essere inseriti nell'intestazione del documento HTML all'interno dei tag <style></style>.
  Esistono una serie di differenze logiche e pratiche nell'implementazione _inline_ e quella attraverso un foglio di stile: la prima assegnerà lo stile a quello specifico elemento; assegnando, invece, uno stile nell'intestazione della pagina a un tag, tutti gli elementi dello stesso tipo assumeranno lo stesso stile;
- **ESTERNI**. Per creare un foglio di stile esterno basta inserire tutte le istruzioni CSS all'interno di un semplice file di testo che dovrà poi essere salvato con estensione **.css**. Questa soluzione realizza la perfetta separazione tra formattazione e struttura e rappresenta la tecnica **_ideale_**.

3. Per collegare un file CSS esterno alla pagina HTML basta richiamarlo nell'header del documento HTML attraverso il tag **link** in questo modo:
<link rel="stylesheet" type="text/css" href="style.css">.
L'attributo **rel**
