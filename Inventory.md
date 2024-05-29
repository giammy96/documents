La funzionalità di inventario raccoglie i metadati degli asset installati all’interno di tutti i provider presenti sulla SCMP.

Gli asset attualmente presenti sono:

-   Virtual Machine
-   Data Stores
-   Networks
-   Kubernetes
-   Security
-   Others
-   What If
-   Reports

I metadati eterogenei, provenienti da diverse fonti vengono poi normalizzati dalla SCMP per permettere una visualizzazione standard.

L’inventario è accessibile dalla voce di menu “Inventory”. Come mostrato in figura.

![Immagine che contiene schermata, testo, software, Software multimediale Descrizione generata automaticamente](media/8c766eaeb73044338a6d36a68ee69515.png)

Figura 90 - Accesso a Inventory

Figura 91 – Dahsboard di inventario

### Dashboard di inventario

La pagina Dashboard permette di avere una visione globale e aggregata di tutte le risorse, mentre i menu sopra il path del breadcrumb danno la possibilità di filtrare per tipologia di risorsa. () le funzionalità disponibli nelle varie pagine sono identiche tra loro.

![A screenshot of a computer Description automatically generated](media/96e132a17668133a94216f64ed186655.png)

All’interno della pagina del tab “Resources”, sono presenti dei filtri, nel primo filtro in alto è possibile inserire la ricerca delle risorse in base al nome, al gruppo di risorse, provider, ecc., viene reso possibile inoltre di filtrare le risorse per “Provider” e “Subsystem”.

L’ultimo filtro permette la ricerca tramite tag. Cliccare su di esso e selezionare un tag (Rif.5.10.2), infine cliccando sul pulsante che raffigura una lente d’ingrandimento la pagina si aggiorna e si ottiene la lista delle risorse filtrate.

![A screenshot of a computer Description automatically generated](media/c5ed15ee80b91ff0883f2d083916cf27.png)

Figura 92 - Ricerca generica, per tag, per Provider e Subsystem

È possibile, inoltre, cliccare sui grafici per applicare automaticamente i relativi filtri.

#### Visualizzazione dettaglio risorsa

Per visualizzare il dettaglio di una risorsa, si può cliccare come in figura:

![A screenshot of a computer Description automatically generated](media/613d582bea8e247fcd6833f7797c0385.png)

Figura 93 - Accesso alla risorsa in modalità lettura

Il dettaglio di un asset di inventario mostra in alto le caratteristiche principali come costo mensile, size della macchina e link esterno alla risorsa che punta al provider di riferimento.

Di seguito la visualizzazione dei dettagli di una VM:

![A screenshot of a computer Description automatically generated](media/3ca119e1c333c2e222e4828fb73d4853.png)

Figura 94 - Dettaglio risorsa

E in calce le relazioni dell’asset con altri elementi di SCMP, come mostrato in figura:

![A screenshot of a computer Description automatically generated](media/6fb6816e57acd18385d3f01fecbcf3d0.png)

Figura 95 - Grafico delle relazioni

Il grafico delle relazioni permette di navigare tra le risorse cliccando direttamente sul tondino della risorsa concatenata in relazione, al fine di atterrare sul dettaglio di quest’ultima.

Inoltre, è possibile editare alcuni attributi, come ad esempio i tags, come da figura ():

![A screenshot of a computer Description automatically generated with low confidence](media/d518651e66905f1a97083ab9a8744e1d.png)

Figura 96 - Selezione del tag

Per il campo “Provider Tags…” non è possibile selezionare un tag, in quanto i tag in questa sezione vengono recuperati direttamente dal sottosistema

Il campo “Add SCMP Tag…” permette di selezionare da un elenco o inserirne uno manualmente. All’interno del tag è presente il simbolo “X” per eliminare il suddetto.

È possibile inserire più tag per la risorsa.

Successivamente, in basso a destra della sezione “Tags & Note”, cliccare sul pulsante “Save” per salvare la modifica ed apparirà un banner in basso di avvenuto salvataggio del tag.

Scorrere la pagina verso il fondo, e cliccare sul pulsante “Close” posizionato a destra per tornare nella pagina del tab “Dashboard”.

#### Azioni sulle macchine di inventario

Sempre dalla pagina del dettaglio della risorsa è possibile effettuare le seguenti operazioni utilizzando il menu in alto nella pagina:

-   Avvio della macchina
-   Stop della macchina
-   Ridimensionamento della macchina
-   Aggiunta di dischi di memoria
-   Aggiunta di un interfaccia di rete
-   Eliminazione della risorsa
-   Rimozione del disco nella risorsa
-   Rimozione di un interfaccia di rete

    Le operazioni disponibili sono diverse per ogni provider e sono indicate in bianco quando possono essere eseguite e in grigio quando non sono supportate o non disponibili.

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/3fb0d69fbe836a3900b4124b61a45fac.png)

Figura 97 - Accesso al report di Inventory

### Reportistica Inventory

Sopra il path del breadcrumb, cliccare sul tab “Reports” (Figura 98). L’utente si ritrova all’interno del tab “Report Types” in cui è necessario cliccare sul pulsante “RUN NOW” in corrispondenza di “Inventory Summary” per avviare la modale in cui è possibile inserire i filtri per la creazione del report (Figura 99).

![A screenshot of a computer Description automatically generated](media/1b6aca5c5557fe3a1077e5a9438fe023.png)

Figura 98 - Accesso al report di Inventory

![A screenshot of a computer Description automatically generated with medium confidence](media/dab138b8c9c47456da4f58f0f0fefd1b.png)

Figura 99 - Esecuzione del report

Una volta che si sarà aperta la modale dei filtri, è possibile compilare alcuni o tutti i parametri. Una volta compilati i parametri desiderati, in basso a destra della modale, cliccare sul pulsante “Submit” (Figura 100).

![A screenshot of a computer Description automatically generated](media/e95579d6cca47de5b1d41638c4510090.png)

Figura 100 - Applicazione dei filtri report

Fatto ciò, l’utente si ritrova all’interno del tab “Results” in cui è presente lo storico di tutti i report (Figura 101).

Per arrivare in questa sezione senza effettuare prima un report bisogna cliccare sopra alla lista delle tipologie di report il tab “Results”

In fondo alla pagina a destra, è possibile selezionare il numero di elementi da visualizzare per pagina. Le frecce racchiuse all’interno del rettangolo consentono all’utente di visualizzare gli elementi delle pagine successive e precedenti. Invece, le frecce al di fuori del rettangolo consentono di spostarsi nell’ultima e nella prima pagina (Figura 102).

![A screenshot of a computer Description automatically generated](media/b588a399f04e9e76f55bf01cb3ee71bd.png)

Figura 101 - Gestione dello storico dei report

![A screenshot of a computer Description automatically generated with medium confidence](media/4f0a2888fd00c246ad1871c604195758.png)

Figura 102 - Gestione pagine report

Per visualizzare i dettagli del report generato, cliccare sul report che sta nella prima riga come indicato dalla freccia (Figura 102).

A questo punto, l’utente si ritrova all’interno del sommario del report (Figura 103). All’interno del sommario del report dell’Inventory è presente la sezione “Stats” in cui sono presenti il numero dei dischi, delle interfacce, delle reti e delle Virtual Machines appartenenti al provider selezionato.

Sotto la sezione “Stats”, sono presenti i filtri usati dall’utente per generare il report. Sotto i filtri, è presente la tabella riassuntiva delle risorse appartenenti al provider. A destra sono presenti due pulsanti: “PRINT” ed “EXPORT”.

Cliccando sul pulsante “PRINT”, appare una modale di anteprima della stampa. Per stampare il report, cliccare sul pulsante in basso a destra “Stampa”, a questo punto si avvierà la stampa del suddetto.

Cliccando sul pulsante “EXPORT”, è possibile esportare il report in formato “.csv”, “. json” o “.pdf”.

Per tornare al tab “Results”, in basso a destra, cliccare sul pulsante “CLOSE” oppure in alto a sinistra cliccare sulla freccia che punta verso la sinistra, accanto al titolo del report.

![A screenshot of a computer Description automatically generated](media/56c7076bb5fdd0b1003887e93cfab07c.jpeg)

Figura 103 - Sommario del report

### Funzionalità “WHAT IF”

Questa funzionalità permette di eseguire degli scenari di simulazione per la migrazione degli asset da un provider a un altro in modo da poter confrontare i costi di gestione e mantenimento.

Per eseguire una simulazione , cliccare sopra il path del breadcrumb il tab che raffigura una relazione che collega due entità denominato ‘What If’ (Figura 104).

Dopo aver fatto ciò, ci si ritrova all’interno della pagina del tab “What If” (Figura 105).

Possiamo notare sopra la lista delle simulazioni, sulla destra, due tab che permettono di filtrare la lista per tipologia di simulazione , nello specifico:

All’ apertura della pagina verranno visualizzate tutte le simulazioni di tipo “Change Provider” mentre cliccando sul tab “Capacity” sarà possibile visualizzare la lista delle simulazioni di tipo “Change size”

![A screenshot of a computer Description automatically generated](media/dbd4b1c125e8b509a86b5c120bd684d5.png)

Figura 104 - Accesso a “What If”

![A screenshot of a computer Description automatically generated](media/cac53f52f62f824aabab392c030f69be.png) ![](media/925d4691f018db16eed72b17a3cbeed0.png)

Figura 105 - Pagina di “What If”

#### Scenario “What If”: Provider Migration

Per effettuare una simulazione del “What If: Migrate Provider”, cliccare nel riquadro a sinistra intitolato “Migrate to another provider” (Figura 106).

![A screenshot of a computer Description automatically generated](media/5c2e3880b39ea0b45e9a1cd4dad6a972.png)

Figura 106 - Accesso alla funzionalità "What If: Migrate Provider"

Dopo aver fatto ciò, l’utente si ritrova all’interno della pagina “Start” dello step 1 per la simulazione della migrazione da un cloud provider ad un altro (Figura 107).

A sinistra nel riquadro “Select Resources to migrate”, l’utente può ricercare le risorse tramite tre tipi di filtri tra cui:

-   “Search” che consente di cercare una risorsa per nome;
-   “Search by Type” di ottenere le risorse tramite la selezione del tipo di risorsa;
-   “Search by tags” che consente di ricercare le risorse tramite uno o più tag (5.11.2.).

All’interno della tabella delle risorse verranno visualizzate solo risorse che abbiano una relazione nel catalogo (5.9.1.1 Esportazione scenario “What If”: Provider Migration

All’interno della tabella delle risorse, cliccare su una di essa e tramite la tecnica del “drag and drop”, trascinarla a destra, all’interno nel riquadro intitolato “Currently selected ”.

È possibile inserire un numero massimo di tre risorse per simulazione.

Successivamente, in basso a destra, cliccare sul pulsante “Next”.

![A screenshot of a computer Description automatically generated](media/c4a14078687e607fb198d968ddf3bca8.png)

Figura 107 - Scelta delle risorse in cui effettuare la migrazione del provider

Dopo aver fatto ciò, l’utente si ritrova all’interno della pagina “Destination Providers” dello step 2 in cui è possibile cliccare sul checkbox in corrispondenza di uno o più provider ove, in base al tipo di provider selezionato, verrà automaticamente compilato in basso a sinistra il valore nel campo ‘Option selected” con i nomi dei providers selezionati (Figura 107).

Successivamente, in basso a destra, cliccare sul pulsante “Next”, mentre per tornare alla pagina “Start” dello step 1, cliccare sul pulsante “Back”.

![A screenshot of a computer Description automatically generated](media/fc7cad6b6d1bb766bbfc8effc214db8d.png)

Figura 108 - Scelta del Cloud Provider in cui migrare le risorse

Dopo aver cliccato sul pulsante “Next”, l’utente si ritroverà all’interno della pagina dello step 3 intitolato “Details” (Figura 109).

All’interno della pagina, nel riquadro a sinistra intitolato “Region”, selezionare dal menu a tendina una o più regione.

Dopodiché, a destra è presente, il riquadro intitolato “Cost Model” in cui è necessario selezionare il tipo di costo.

Dopo aver selezionato la regione e il tipo di costo, in basso a destra, cliccare sul pulsante “Next”, invece per tornare allo step 2 della pagina “Destination Providers”, cliccare sul pulsante “Back”.

![A screenshot of a computer Description automatically generated](media/e72a22c657bdf1aab0a1f9d9a3dc8bf6.png)

Figura 109 - Selezione della "Regione" e del "Cost Model"

Dopo aver cliccato sul pulsante “Next”, l’utente si ritroverà all’interno dello step 4 intitolato “Duration” (Figura 110).

Dalla pagina “Duration” dello step 4, selezionare un intervallo per la simulazione tra:

-   “One Month”
-   “Six Months”
-   “One Year”

Per tornare indietro alla pagina “Details”, in basso a destra, cliccare sul pulsante “Back”. Invece, per andare avanti con la simulazione, cliccare sul pulsante “Launch Simulation”.

![A screenshot of a computer Description automatically generated with medium confidence](media/d5cdc1031962a8e89867b761aefa5405.png)

Figura 110 - Selezione dell'intervallo di tempo

Dopo aver cliccato sul pulsante “Launch Simulation”, l’utente si ritroverà all’interno della pagina “Results” dello step 5 (Figura 111).

L’utente ritrovandosi all’interno della pagina “Results”, in alto noterà il riquadro “Simulation parameters” con i dati dei parametri per ottenere la simulazione per la migrazione ad un altro provider.

Sotto è presente il riquadro “Summary” in cui è presente il consiglio se effettuare la migrazione al cloud provider selezionato durante la simulazione.

Sotto il riquadro “Summary”, è presente un grafico a istogrammi nel riquadro “Details”, nel quale la barra viola rappresenta gli attuali costi, mentre la barra verde rappresenta il target dei costi.

In basso, è presente la tabella dei costi della/e risorse (Figura 112).

Per uscire dalla simulazione senza salvare la suddetta, in basso a destra, cliccare sul pulsante “Close”.

Fatto ciò, l’utente si ritrova all’interno della pagina “What If”. Per salvare la simulazione, cliccare sul pulsante “Save” accanto al pulsante “Close”, e poi cliccare su “Confirm”.

Dopo aver cliccato sul pulsante “Save”, l’utente viene reindirizzato nella pagina del tab “What If”.

![A screenshot of a computer Description automatically generated](media/501f5324d8601f2a5928f5bd9207049c.png)

Figura 111 - Parametri di configurazione e consiglio sulla simulazione

![A screenshot of a computer Description automatically generated](media/024ca6c12cf5df0c0150969929846006.png)

Figura 112 - Tabella riassuntiva della/e risorse

![A screenshot of a computer Description automatically generated](media/1431fa6090d9bbd542ed455c14c80537.png)

Figura 113 - Avvio per l'aggiornamento della simulazione di tipo "Migrate to another provider"

#### Scenario “What If”: Change Resource Capacity

Questa funzionalità permette di confrontare i costi di una risorsa in caso di modifica delle caratteristiche tecniche.

Sempre dalla pagina del tab “What If”, in alto a destra, cliccare sul riquadro “Change resources capacity “(Figura 114).

![A screenshot of a computer Description automatically generated with medium confidence](media/e49a6ca7762be1efded9594eae489c4f.png)

Figura 114 - Accesso alla funzionalità "What If: Change resources capacity"

Dopo aver fatto ciò, l’utente si ritroverà all’interno della pagina “Start” dello step 1 (Figura 115).

A sinistra nel riquadro “Select Resources to change”, l’utente può ricercare le risorse tramite tre tipi di filtri tra cui:

-   “Search” che consente di cercare una risorsa per nome;
-   “Search by Type” che consente di ottenere le risorse tramite la selezione del tipo di risorsa;
-   “Search by tags” che consente di ricercare le risorse tramite uno o più tag associato alle suddette (Rif.5.11.2).

Nella tabella delle risorse verranno riportate (se ci sono) solo risorse che, all’interno del catalogo SCMP, abbiamo più di una “Relazione” (5.9.1.1) con size differenti ma appartenenti alla stessa regione, stesso tipo di prezzo e sistema operativo.

In basso a sinistra, è presente la tabella delle risorse, che può essere filtrata in base ai parametri inseriti nel o nei filtri. All’interno della tabella delle risorse, cliccare su una di essa e tramite la tecnica del “drag and drop”, trascinarla a destra, all’interno nel riquadro intitolato “Currently selected :”.

È possibile inserire un numero massimo di tre risorse per simulazione.

Successivamente, in basso a destra, cliccare sul pulsante “Next”.

![A screenshot of a computer Description automatically generated](media/cb6cf358ac717e5dd2c25caf098e7a61.png)

Figura 115 - Selezione delle risorse da cui modificare le capacità

Dopo aver fatto ciò, l’utente si ritrova all’interno della pagina “Resource Provider” dello step 2 in cui è possibile modificare la size di una o più risorse (Figura 116).

All’interno della pagina “Resource Provider” dello step 2, in corrispondenza di una risorsa, cliccare sul menu a tendina della colonna “Size” e selezionare una size diversa da quella iniziale.

Dopodiché, in basso a destra, cliccare sul pulsante “Next” per proseguire la simulazione.

Per tornare alla pagina “Start” dello step 1, cliccare sul pulsante “Back”.

![A screenshot of a computer Description automatically generated](media/51901a3e7c67d753f7563026bf0c77c0.png)

Figura 116 - Modifica della size di una risorsa

Dopo aver cliccato sul pulsante “Next”, l’utente si ritroverà all’interno della pagina “Duration” dello step 3 (Figura 116).

All’interno della suddetta pagina, è necessario selezionare un intervallo per la simulazione.

Dopodiché, in basso a destra, cliccare sul pulsante “Launch Simulation”.

Per tornare indietro, cliccare sul pulsante “Back”, in questo modo l’utente si ritrova all’interno della pagina “Resource Provider” dello step 2.

![A screenshot of a computer Description automatically generated](media/8889b5c0ba5db8def1f1b9b24ecd6404.png)

Figura 117 - Selezione dell'intervallo per la simulazione

Dopo aver cliccato sul pulsante “Launch Simulation”, l’utente si ritrova all’interno della pagina “Results dello step 4 (Figura 117).

All’interno della pagina “Results”, in alto è presente il riquadro “Summary” che consiglia se modificare la size delle risorse. Sotto, è presente un grafico di istogrammi, in cui la barra viola rappresenta i costi attuali, mentre la barra verde rappresenta i costi target.

Per salvare la simulazione, cliccare sul pulsante “Save” accanto al pulsante “Close”, e poi cliccare su “Confirm”. Fatto ciò, l’utente viene reindirizzato nella pagina di “What If”.

Per uscire dalla simulazione senza salvare la suddetta, in basso a destra, cliccare sul pulsante “Close”. Fatto ciò, l’utente si ritrova all’interno della pagina “What If”.

![A screenshot of a computer Description automatically generated](media/ff4e62458fa38b3e9188edfd1e968f10.png) ![A screenshot of a computer Description automatically generated with medium confidence](media/c4c5da07bd65658d00e050f734609f22.png) ![](media/1700b51bd79cbc1aaf6e81aa71d19fdb.png)

Figura 118 - Parametri di configurazione e consiglio sulla simulazione

#### Esportazione scenario What If

Per una simulazione della modifica di una size di una risorsa, è possibile esportare la suddetta in formato pdf, csv e json.

All’interno della pagina di “What If”, in basso è presente una tabella delle simulazioni, cliccare sul pulsante “Capacity” posizionato nell’angolo superiore destro della suddetta tabella.

Dopo aver fatto ciò, la tabella mostra le simulazioni sulla modifica della size delle risorse.

In corrispondenza di una simulazione, cliccare sul pulsante che raffigura una freccia.

A questo punto si aprirà un sottomenu in cui è possibile effettuare l’export nei tre formati precedentemente descritti (Figura 119).

![A screenshot of a computer Description automatically generated](media/b0c1b0b226282b465d4b9bd5353e1ca3.png)

Figura 119 - Export della simulazione

Sempre per una simulazione è possibile effettuare la stampa della suddetta.

In corrispondenza di una simulazione, cliccare sul kebab menu, e a quel punto cliccare sull’opzione “Print” (Figura 120).

A questo punto, apparirà una modale dell’anteprima del documento da stampare. Infine, cliccare sul pulsante “Stampa” per avviare la stampa del documento.

![A screenshot of a computer Description automatically generated](media/c35c3577aed0bc27fbf8ce4e501cc99e.png)

Figura 120 - Stampa della simulazione

In corrispondenza di una simulazione, cliccare sul kebab menu,

Dalla lista delle opzioni, cliccare su “Delete” (Figura 121).

Dopo aver cliccare sull’opzione “Delete”, apparirà una modale in cui è necessario confermare l’eliminazione della simulazione cliccando sul pulsante “Confirm” (Figura 122).

Fatto ciò, la simulazione non è più presene all’interno della tabella.

Se invece non si vuole dare la conferma per l’eliminazione della simulazione, cliccare sul pulsante “Cancel”.

![A screenshot of a computer Description automatically generated](media/96e765acaf4fc818e087d06b0d3fd04c.png)

Figura 121 - Opzione per eliminare una simulazione

![A screenshot of a computer Description automatically generated](media/2984d9ec7431d988e3d5ba19fe2b89e8.png)

Figura 122 - Conferma dell'eliminazione della simulazione

È possibile effettuare una modifica alla simulazione, cliccando semplicemente nel rigo della suddetta simulazione. L’utente si ritroverà all’interno dello step 1 della pagina “Start” in cui può modificare la risorsa presente nel riquadro a destra, oppure può aggiungerne altre (per un massimo di tre risorse totali), e così con la modifica della size delle risorse, e dell’intervallo della simulazione. Gli step da seguire sono simili a quelli descritti precedentemente.

![A screenshot of a computer Description automatically generated](media/d00955954af6427673ec7c53572e29e1.png)

Figura 123 - Lista simulazioni già eseguite

![A screenshot of a computer Description automatically generated](media/534f7a9b1b6d6fa970463c30e2f551a0.png)

Figura 124 - Aggiornamento della simulazione