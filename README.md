**DIRECTA SIM**

<a href="http://www.directa.it/">Directa</a> è una Società di Intermediazione Mobiliare costituita a Torino nel 1995, con l'obiettivo di permettere agli investitori privati di comprare e vendere azioni per via telematica, direttamente dal loro PC.

**I REPOSITORY DEI PROGETTI** 

I repository rappresentano il punto di riferimento per gli sviluppatori interessati ad utilizzare i servizi messi a disposizione da Directa [per i propri clienti] tramite la piattaforma <a href="http://www.directa.it/pub2/it/darwin/intro.html">Darwin</a>. I *progetti* proposti sono:

- <a href="https://github.com/directa-it/darwinCommandLine">*Darwin CommandLine*</a>: e' una versione di Darwin senza interfaccia grafica che permette di utilizzare le API (dati storici, prezzi e scambi in tempo reale, funzioni per il trading) fornite da Directa
- *<a href="https://github.com/directa-it/pluginExcel">Plugin Excel*</a>: e' la libreria che permette di utilizzare le API di Darwin in Excel
- <a href="https://github.com/directa-it/pluginMulticharts">*Plugin Multichart*</a>: e' il plugin che permette di utilizzare Darwin (Directa) come flusso dati e come broker per Multichart

Ad ogni *progetto* corrisponde un repository che conterra' sempre l'ultima versione aggiornata (degli eseguibili) del software messo a disposizione da Directa. Oltre ad offrire un sistema di controllo di versione, l'obiettivo e' quello di facilitare la segnalazione di eventuali bug e seguirne la relativa correzione nei vari rilasci di versione, creare un punto per la discussione di eventuali proposte di miglioramenti e/o integrazioni, (e raccogliere esempi o ...)

**API DIRECTA**

Le API Directa utilizzano dei socket in ascolto sulla macchina locale e mettono a disposizione tre flussi dati:

- *Datafeed*: flusso dati per la sottoscrizione di un titolo; permette di ricevere gli eseguiti / bid-ask / book 5 livelli per il titolo scelto
- *Trading*: flusso dati per eseguire operazione di trading
- *Chiamate Storiche*: flusso dati per richiedere varie combinazioni in termini di timeframe e periodi dei dati storici (candele, dati tick by tick)

Il funzionamento delle API e' condizionato all'avvio della piattaforma  <a href="http://www.directa.it/pub2/it/darwin/intro.html">Darwin</a> con un conto abilitato a tale servizio.

**PREREQUISITI**

Darwin 2.0 è sviluppata in Java  e richiede la presenza della versione aggiornata Java JRE e JDK.

**DOCUMENTAZIONE ED UTILIZZO**

Ogni repository e' relativo ad un singolo progetto [ in modo da facilitare il processo di segnalazione e correzione di bug o discussione di proposte/miglioramenti relativi al progetto in questione]. Per la documentazione ed esempi seguire i link:

- <a href="https://directa-it.github.io/documentation/#InfoMute"> Darwin CommandLine</a> 

- <a href="https://directa-it.github.io/documentation/excel.html"> Plugin Excel</a> 

- <a href="https://directa-it.github.io/documentation/#InfoMC"> Plugin Multichart</a> 

**BUG REPORTING**

Per segnalare eventuali bug si suggerisce di aprire una segnalazione nel Tab Issue del repository relativo al progetto in questione. 

**DISCLAIMER**

Per l'utilizzo delle API e dei relativi plugin è necessario essere in possesso/ titolari di un conto presso Directa e procedere alla sottoscrizione di un disclaimer disponibile a partire dalla pagina personale su directratrading.com,  cliccando su *Info -> punto 5a   (ABILITAZIONI e VARIAZIONI CONTRATTUALI / Abilitazioni) -> punto 3i  (API)*.

**LIBRERIE TERZE PARTI**

Le librerie di terze parti incluse nei progetti sono:

- <a href="https://github.com/google/gson">GSON</a>
- <a href="https://commons.apache.org/">Apache Commons</a>

Tali librerie sono rilasciate sotto <a href="https://github.com/directa-it/documentation/blob/master/ApacheLICENSE-2.0.txt">Apache 2.0 License</a>. 

```
This product includes software developed at
The Apache Software Foundation (http://www.apache.org/).
```

**OFFICIAL WEBSITE**

Sito ufficiale Directa: http://directa.it

Descrizione servizio API: http://www.directa.it/pub2/it/darwin/api.html