# CHANGELOG

## Versione beta-1.0.0 - [07/10/2023]

### Corretto
- Nella Lista distribuzione verrà rimossa la parola "ALLE" che veniva mostrata per errore
- Nella sezione "Estensione" la data viene cambiata automatcamente 
### Bug Presenti
- I campi nella relazione di audit a volte sono incompleti, bisogna ancora correggerli manualmente

## Versione alpha-1.3.0 - [06/10/2023]

### Aggiunto
- Aggiunto il bottone "Stampa Pdf" per generare il pdf di tutto l'audit (quindi con non conformità e relazione di audit unite insieme)
- Aggiunta la gestione di Funzione valutata (legata a un Paragrafo, non so perché a volte al primo paragrafo fa degli errori, va testata)
- Il N. report selezionato all'inizio ora viene mostrato in fase di generazione della relazione di audit
  
### Corretto
- Corretta l'impostazione del paragrafo "Non Completato" (giallo) con una non conformità (diventa VERDE o ROSSO solo e solamente quando tutti i sottoparagrafi sono stati controllati, mentre prima diventava rosso anche con una sola non conformità selezionata)
- Invertito l'ordine di Conclusioni e Lista distribuzione nella generazione di una r. audit

### Modificato
- Ho leggermente modificato il funzionamento nella parte finale. Si veda il video inviato su Whatsapp.
- L'area di testo per inserire le note e tutti i campi della relazione di audit sono state estese (Da testare sul pc aziendale)
- I bottoni, se cliccati, cambiano colore. Quindi é più facile controllare quando il programma sta eseguendo azioni o é fermo

### Non Implementato (Rispetto alla RAC Agorà del 27 settembre 2023)
- La scelta dell campo "soluzione soddisfacente/insoddisfacente" in un rapporto di n.c. (Tramite una chiamata vorrei chiederle alcuni chiarimenti)
- Non sono possibili Taglia/Copia e Incolla di testi nell'applicazione senza l'uso di CTRL+C e CTRL+V e non è possibile inserire campi in grassetto o corsivo, in quanto sono funzionalità offerte unicamente da "Microsoft Office Word" e l'implementazione sarebbe troppo complicata ed inutile vista la "provvisorietà" del software. Per ora si può ovviare scrivendo il contenuto tramite l'app ed evidenziandolo in grassetto nel riepilogo
- Non è ancora presente un bottone per invertire funzioni e collaboratori. L'implementazione sarebbe troppo complessa, il tutto può essere ovviato tramite un controllo fatto alla checklist il giorno prima dell'audit invertendo manualmente i dati (in modo da correggere manualmente eventuali errori di formattazione e "preparare" i dati per la loro immissione nel futuro database).

## Versione alpha-1.2.0 - [25/09/2023]

### Modificato
- Il colore di un paragrafo adesso è: "non controllato" = bianco, "controllato" = verde, "non finito" = giallo, "contiene non conformità" = rosso
- Il riepilogativo ora segue le Cartelle e non un file txt

### Aggiunto
- Aggiunto il bottone "Scegli relazione di audit" per scegliere manualmente la relazione di audit nel pannello finale

## Versione alpha-1.1.0 - [22/09/2023]

### Corretto
- l'ordine dei bottoni per le non conformità è stato cambiato
- I testi non sovrappongono più i campi per l'inserimento
- Il tasto "invia mail" non compare fin quando non è stata generata una relazione di audit

### Modificato
- Il colore di un paragrafo adesso è: "non controllato" = bianco, "controllato" = verde, "contiene non applicabilità" = giallo
- Cambiati alcuni nomi (Ad es. ora le sezioni sono informazioni, checklist, relazione audit)
- Il nome ora è PQS App, da modificare in futuro
- La "Checklist" che verrà generata in formato word ha 3 colonne in più che indicano la conformità/ non conformità/ non applicabilità dei punti della norma
- La sezione "Checklist" è inaccessibile se tutti i campi iniziali di "informazione" non sono stati approvati tramite il rispettivo bottone per validarli (Inoltre, il cambio della data, che il programma interpreta come "Voglio generare una nuova checklist nella data selezionata" invalida automaticamente tutti i campi, in quanto si presuppone che si sta effettuando un nuovo audit)
- La sezione Relazione Audit non è accessibile se non ho terminato i paragrafi (ovvero ogni paragrafo ha un colore)
- Non può essere più salvato un rapporto di non conformità senza che tutti i campi siano riempiti
- Non può essere più salvata una Relazione di Audit senza che tutti i campi siano riempiti
- Nella sezione di controllo paragrafi la legenda è cambiata: "Bianco = paragrafo non finito", "Giallo = paragrafo contiene delle non applicabilità", "Verde = paragrafo controllato e non contiene non applicabilità". Solo nel caso in cui tutti i paragrafi hanno un colore sarà possibile visualizzare il riepilogativo e generare una relazione di audit
- Il tasto invia mail che si genera da solo appena viene conclusa una pratica non riesce ancora ad inviare una mail da solo. Tuttavia per il momento mi è sembrato opportuno usare un "mailto" (da testare) ovvero un sistema che apre automaticamente il gestore locale delle mail SENZA TUTTAVIA RIUSCIRE AD ALLEGARE I RAPPORTI DI NON CONFORMITA E LA RELAZIONE DI AUDIT (inserisce infatti solo destinatario ,soggetto e corpo) 

### Aggiunto
- Aggiunto il bottone "Scegli schecklist" per scegliere manualmente la checklist da cui partire, in caso in cui ci si rende conto che la data mostrata dal programma non corrisponde a quella reale (Andrà testato poi se, appena viene creata una nuova checklist, il programma al riavvio riconosce quella creata come ultima checklist. In caso questo non dovesse succedere, bisognerà ripensarne un po' tutto il funzionamento)
- Nel pannello "Relazioni di audit" c'è una sezione per il riepilogativo (Ovvero un conteggio di tutte le non conformità che sono state generate, classificate per tipo). Serve perchè quando verranno aperte le non conformità da approvare "chiudendo il documento word" bisognerà aggiornare il N.Rapporto in base al numero di non conformità.

### Da modificare
- Devo ancora modificare la scelta delle funzioni coinvolte. Dopo qualche test dell'applicazione dal lato "utente" decideremo come fare
