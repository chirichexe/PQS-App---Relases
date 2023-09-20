# CHANGELOG

## Versione alpha-1.1.0 - [18/09/2023]

### Corretto
- Il nome ora è PQS App, da modificare in futuro
- l'ordine dei bottoni per le non conformità è stato cambiato
- I testi non sovrappongono più i campi per l'inserimento
- Il Colore di un paragrafo "non controllato" è bianco, "controllato" è verde, "contiene non applicabilità" giallo
- Cambiati alcuni nomi (Ad es. ora le sezioni sono informazioni, checklist, relazione audit)

### Modificato
- La "Checklist" ha 3 colonne in più che indicano la conformità/ non conformità/ non applicabilità dei punti della norma
- La sezione "Checklist" è inaccessibile se tutti i campi iniziali di "informazione" non sono stati approvati tramite il rispettivo bottone per validarli
- Non può essere più salvato un rapporto di non conformità senza che tutti i campi siano riempiti
- Nella sezione di controllo paragrafi la legenda è cambiata: "Bianco = paragrafo non finito", "Giallo = paragrafo contiene delle non applicabilità", "Verde = paragrafo controllato e non contiene non applicabilità". Solo nel caso in cui tutti i paragrafi hanno un colore sarà possibile visualizzare il riepilogativo e generare una relazione di audit
- La sezione Relazione Audit non è accessibile se non ho terminato i paragrafi (ovvero ogni paragrafo ha un colore)


### Aggiunto
- Aggiunto il bottone "Scegli schecklist" per scegliere manualmente la checklist da cui partire, in caso in cui ci si rende conto che la data mostrata dal programma non corrisponde a quella reale (Andrà testato poi se, appena viene creata una nuova checklist, il programma al riavvio riconosce quella creata come ultima checklist. In caso questo non dovesse succedere, bisognerà ripensarne un po' tutto il funzionamento)
