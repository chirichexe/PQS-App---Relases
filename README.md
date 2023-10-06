# PQS App

## Descrizione
Progetto in divenire realizzato per la PQS. Può
- Leggere, scrivere e interpretare checklist, rapporti di non conformità, relazioni di audit.

## Utilizzo
!!! IMPORTANTE !!!

Per la sezione checklist è fondamentale che ogni cartella abbia una struttura del tipo:

AZIENDA - NORMA DI RIFERIMENTO - ANNO (2023 ad es.) - PQS - DATA (formato "gg mm aaaa" ad es. 10/11/2023) - CHECKLIST / Relazione audit
Nel caso in cui questi vincoli non venissero rispettati è bene scegliere un'azienda e selezionare una checklist di partenza "a mano". Poi, dopo averci lavorato, con "Salva" il programma creerà in automatico un percorso "standard". Nel caso l'app (dopo almeno un salvataggio avvenuto tramite il programma) al riavvio non riconoscesse ancora la checklist creata come "ultima checklist", è opportuno eliminare la cartella riconosciuta come "ultima checklist" dal programma, ricordandosi di spostare l'eventuale relazione di audit precedente nella nuova cartella creata dal programma. In ogni caso, sono disponibile per ogni tipo di chiarimento.

### Sezione Checklist:
#### 1. Pagina informazioni:
 - Vengono visualizzate tutte le informazioni dell'azienda.
- Appena si avvia un'applicazione tutti i campi sono "approvati" (bottone verde), ma se viene cambiata data (quindi è un audit diverso da quello della checklist di "partenza" selezionata) bisognerà riapprovare tutti i campi per passare alle pagine successive. 
 - è bene che, nell'atto di approvazione si correggano eventuali righe vuote / formattazioni errate nella tabella "funzioni coinvolte"

#### 2. Pagina Checklist:
Ogni paragrafo va controllato come "conforme"/"non conforme"/"non applicabile". La selezione "non conforme" fa aprire una scelta del rapporto di non conformità. Legenda colori:

- Paragrafo bianco: non ancora aperto
- Paragrafo giallo: contiene delle non applicabilità
- Paragrafo verde: controllato e non contiene delle non applicabilità

- Riferimento verde: conforme
- Riferimento giallo: non applicabile
- Riferimento rosso: non conforme

Appena tutti i paragrafi hanno un colore si piò passare alla terza sezione

#### 3. Relazione di audit:
-Viene visualizzato un resoconto di tutte le non conformità a sinistra. Tramite un pulsante verranno poi aperti tutti i rispettivi documenti word (Dove andrà cambiato il numero del rapporto in base al totale delle non conformità generate).
- Dopo aver chiuso tutte i documenti word delle non conformità è possibile scrivere una relazione di audit partendo da quella precedente (se il programma non riuscità a trovarla, chiederà di selezionarla manualmente)
- Dopo aver salvato tutto verrà chiusa la pratica e sarà possibile salvare il pdf della relazione di audit e dei rapporti di non conformità, che sarà possibile inviare via mail tramite apposito pulsante (!! NON ANCORA IMPLEMENTATO !!)
 
## Installazione
Basta scaricare i file e inserirli in una cartella a scelta. Poi andrà eventualmente scelto il path della "piazzetta" che verrà ricordato dal programma.
