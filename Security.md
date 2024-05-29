La funzionalità della SCMP che riguarda la security mostra le vulnerabilità degli asset di inventario presenti sulla SCMP.

Per accedere alla funzionalità di “Security”, in alto a sinistra cliccare sul pulsante bento. Fatto ciò, apparirà la barra dei menu in cui è necessario cliccare su “Security” (Figura 252).

![](media/1a5f36251f1324a6125dc220b4f5fa98.png)

Figura 252 - Accesso a Security

### Dashboard generale

A questo punto, l’utente si ritrova all’interno della pagina del tab “Dashboard” (Figura 253) dove vengono mostrati in modalità aggregata, i dati della compliance delle risorse per tutti i provider configurati.

In alto è presente una barra dei filtri che permette di filtrare i risultati per sottosistema di appartenenza , status e/o nome della policy.(Figura 253).

Dopodiché, l’utente nota la presenza del grafico a barre che indica lo stato di compliance delle risorse suddiviso per sottosistema.

Passando il mouse su una sezione del grafico possiamo notare che i valori visualizzati in pagina vengono aggiornati per mostrare un anteprima del dettaglio.

È possibile cliccare su una sezione del grafico per applicare automaticamente i filtri “sottosistema” e “status” alla pagina.

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/241862c2a4580ac51686e3dbad3ab903.png)

Figura 253 – Dashboard di Security

Scorrendo la pagina verso il basso, è presente la tabella delle policies (Figura 254) che verrà filtrata automaticamente in base ai filtri selezionati.

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/6ba2bdee84151afd8b98e487d67f7a63.png)

Figura 254 - Tabella delle policies

Cliccando su una riga della tabella verrà aperta una finestra di dettaglio,(Figura 255) dove all’interno possiamo trovare tutte le informazioni relative alla policy selezionata, inoltre sarà disponibile la lista delle risorse interessate. È possibile cliccare sul nome di una macchina per visualizzarne i dettagli , in questo caso l’utente verrà reindirizzato all’ interno della risorsa di inventario SCMP in modalità “view”

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/2f505cae12c7d55984b1fd59c79def93.png)

Figura 255 - Dettaglio delle policy

Per uscire dal dettaglio bisogna cliccare all’ esterno della finestra che verrà chiusa automaticamente.

### Dashboard specifiche per tipologia di risorsa

Viene data la possibilità di filtrare ulteriormente le policy per tipologia di risorsa, utilizzando i tab presenti in alto nella pagina (Figura 256)

Una volta selezionata la tipologia di risorsa è possibile navigare nelle pagine seguendo le modalità descritte nel paragrafo precedente (5.12.1)

![](media/d78736dce1968d513278f7fc588b47a2.png)

Figura 256 - Dashboard delle compliance delle Virtual Machines

### Dashboard SIEM

Per visualizzare la dashboard del SIEM, cliccare sul tab che raffigura uno scudo. Nella parte superiore è presente un menu a tendina in cui è possibile selezionare la sottoscrizione di interesse, mentre accanto è presente il menu a tendina in cui è possibile selezionare un intervallo di tempo.

Sotto, è presente la sezione “Summary” in cui sono presenti delle informazioni, tra cui ad esempio “Alerts” che indica il numero degli avvisi. Sempre all’interno della sezione “Summary” è presente il grafico “”Incidents by status” che indicano gli incidenti per stato.

Sotto la sezione “Summary”, è presente la sezione “Hourly Events Grouped By Type” in cui è presente un grafico a istogrammi che indica gli eventi orari per tipo.

![](media/d6ce0500b7ac3299fe7b3d5a5b351e32.png)

Figura 257 - Dashboard SIEM

Scorrendo la dashboard del SIEM, è presente il grafico “Event types” che indica tutti i tipi di eventi (Figura 258).

![A screenshot of a computer Description automatically generated with medium confidence](media/97764625aa86ffaa06c5d596af555639.png)

Figura 258 - “Event types" della dashboard SIEM

Infine, nella parte inferiore della pagina, sono presenti due tabelle: a sinistra la tabella “Alert rules” in cui mostra un insieme di regole degli allarmi, mentre a destra è presente la tabella “Incidents” che mostra invece gli incidenti (Figura 259).

![Immagine che contiene testo, interni, screenshot Descrizione generata automaticamente](media/47a5b697b4b507bea266133b2db39d38.png)

Figura 259 - Tabelle "Alert rules" e "Incidents"

Cliccando su una riga della tabella verrà aperta una finestra di dettaglio,(Figura 260) dove all’interno possiamo trovare tutte le informazioni relative alla regola o incident selezionato”.

![Immagine che contiene schermata, testo, software, Software multimediale Descrizione generata automaticamente](media/46b20879489bd8691be65f5f9b4bed8c.png)

Figura 260 - Dettaglio degli "Incidents"

### Dashboard Secret Manager

Per visualizzare la dashboard del SIEM, cliccare sul tab che raffigura una chiave (Figura 261). Nella parte superiore è presente un menu a tendina in cui è possibile selezionare la sottoscrizione di interesse.

![A screenshot of a computer Description automatically generated with medium confidence](media/385e2684a6519080d4435c19bda94ea7.png)

Figura 261 - Dashboard di Key Vault

All’ interno della pagina in basso è possibile notare dei pulsanti per navigare la tabella e una tabella.

A seconda della pagina selezionata (Figura 262) la tabella mostrerà rispettivamente:

-   Secret
-   Keys
-   Certificates

![](media/26416675407c45d4ac76fb530089d26d.png)

Figura 262 - Risorse visualizzabili

Cliccando su una riga della tabella è possibile visualizzare il dettaglio della risorsa selezionata. (Figura 263)

![A screenshot of a computer Description automatically generated](media/fe26a37e0688f2b34c096aa1426e34b3.png)

Figura 263 - Dettaglio della chiave

### Dashboard Clusters

A questo punto, l’utente si ritrova all’interno della pagina del tab “Dashboard” (Figura 264) dove vengono mostrati in modalità aggregata, tutti gli alert generati dai sottosistemi configurati di tipo “Cluster” nella SCMP

In alto è presente una barra dei filtri che permette di filtrare i risultati per namespace , sottoscrizione e/o nome della policy.(Figura 264).

Dopodiché, l’utente nota la presenza del grafico a barre che indica il totale degli “alert” ricevuti suddiviso per sottosistema

Passando il mouse su una sezione del grafico possiamo notare che i valori visualizzati in pagina vengono aggiornati per mostrare un anteprima del dettaglio.

È possibile cliccare su una sezione del grafico per applicare automaticamente i filtro “sottosistema” .

![](media/622a45f8c988e20138210e01df8f24f9.png)

Figura 264 – Dashboard dei “Cluster alerts”

Scorrendo la pagina verso il basso, è presente la tabella degli “alert” (Figura 265) che verrà filtrata automaticamente in base ai filtri selezionati.

![](media/df024c8ddf23d82bb424eabcc2d686e2.png)

Figura 265 - Tabella degli alert

Cliccando su una riga della tabella verrà aperta una finestra di dettaglio,(Figura 266) dove all’interno possiamo trovare tutte le informazioni relative all’ “alert” selezionato.

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/2f505cae12c7d55984b1fd59c79def93.png)

Figura 266 - Dettaglio degli Alert sui clusters

Per uscire dal dettaglio bisogna cliccare all’ esterno della finestra che verrà chiusa automaticamente