**DIRECTA SIM**

<a href="http://www.directa.it/">Directa Sim</a> è una Società di Intermediazione Mobiliare costituita a Torino nel 1995, con l'obiettivo di permettere agli investitori privati di comprare e vendere azioni per via telematica, direttamente dal loro PC.

**I REPOSITORY DEI PROGETTI** 

I repository rappresentano il punto di riferimento per gli sviluppatori interessati ad utilizzare i servizi messi a disposizione da Directa [per i propri clienti] tramite la piattaforma <a href="http://www.directa.it/pub2/it/darwin/intro.html">Traing Online Darwin</a>. I *progetti* proposti sono:

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

Per l'utilizzo delle API e dei relativi plugin è necessario essere in possesso/ titolari di un conto presso Directa e procedere alla sottoscrizione di un disclaimer disponibile a partire dalla pagina personale su http://www1.directatrading.com,  cliccando su *Info -> punto 5a   (ABILITAZIONI e VARIAZIONI CONTRATTUALI / Abilitazioni) -> punto 3i  (API)*.

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




**DIRECTA SIM**

<a href="http://www.directa.it/">Directa SIM</a> is a financial brokerage company founded in Turin, Italy, in 1995. With the aim of allowing private investors to buy and sell financial instruments electronically, directly from the ease of their computers, 

 **THE PROJECTS' REPOSITORY ** 
 
 The repositories represent a reference point for developers interested in offering the services provided by Directa [ to their customers] through the platform] <a href="http://www.directa.it/pub2/it/darwin/intro.html">Darwin  Online Trading Platfrom</a>. The proposed *projects* are:

- <a href="https://github.com/directa-it/darwinCommandLine">*Darwin CommandLine*</a>: is a Darwin version with no graphical interface, which allows the use of the APIs (historical data, real-time pricing and exchanges, and trading functions) all provided by Directa
-  *<a href="https://github.com/directa-it/pluginExcel">Plugin Excel*</a>: This is the library that allows the use of Darwin's API in Microsoft Excel
- <a href="https://github.com/directa-it/pluginMulticharts">*Plugin Multichart*</a>: is the plugin that allows the use of Directa's Darwin trading platform for the data flow, and MULTICHART as the broker 

For each *project* there is a matching repository that will contain always the latest updated version (the executables) of the software provided by Directa. As well as offering a version control system, the aim is to make easier any eventual bug reporting, to be followed up by bug-fixing patch releases, in various version releases, and also to create a discussion point of any possible user suggestions for improvements and / or additions, (and to collect examples or ...ect)

**DIRECTA'S API**

Directa APIs make use of listening sockets on the local machine and so make available three types of data flows:
- * Data Feed *: a dataflow to apply for a security ; It allows you to receive the executed orders / bid-ask / book
- 5 Book levels for the selected security
- *Trading*: data flow to carry out trading operations
- *Historical Data Requests*: a dataflow to request various combinations, in terms of time frames, and the historical data periods (candles, tick by tick data)


The API's functionality depends on the start-up of 

<a href="http://www.directa.it/pub2/it/darwin/intro.html">Darwin Trading Platform </a> with an account that is enabled for that  service.

**PREREQUISITES**

Darwin 2.0 is developed in Java and requires the presence on the local machine of an updated version of the Java JRE & JDK.
 
**USER GUIDE AND DOCUMENTATION** 

Each repository is related to a single project [in order to simplify the process of bug reporting as well ass bug fixing or the discussion of user proposals / improvements related to the project in question]. documentation and examples can be found on the following links: 

- <a href="https://directa-it.github.io/documentation/#PluginDirecta"> Darwin CommandLine</a> 

- <a href="https://directa-it.github.io/documentation/excel.html"> Plugin Excel</a> 

- <a href="https://directa-it.github.io/documentation/#InfoMC"> Plugin Multichart</a> 



**BUG REPORTING**

To report eventual bugs, we suggest you to open a message in the Issues Tab of the repository for the concerned project.


**DISCLAIMER**

In order to use the APIs and the related plugins you must own an account at Directa Sim, and also proceed to sign the disclaimer that is reachable starting from the  personal home page of your trading account at http://www1.directatrading.com, by going to > *Info -> 5.ADDITIONAL ACTIVATIONS AND VARIATIONS > Additional Activations > More > i.API


**THIRD PARTY LIBRARIES**

third-party libraries included in the projects are:

- <a href="https://github.com/google/gson">GSON</a>
- <a href="https://commons.apache.org/">Apache Commons</a>
These libraries are released under the  <a href="https://github.com/directa-it/documentation/blob/master/ApacheLICENSE-2.0.txt">Apache 2.0 License</a>. 

```
This product includes software developed at
The Apache Software Foundation (http://www.apache.org/).
```

**OFFICIAL WEBSITE**

Directa sim's Official website: http://www.directa.it

API service description at : http://www.directa.it/pub2/it/darwin/api.html

