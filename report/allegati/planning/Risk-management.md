---
layout: default
title: Risk Management
nav_exclude: true
---

# Risk Management

Alla luce dei rischi analizzati in precedenza, è stato deciso di analizzarli più nel dettaglio, descrivendo il tipo di problema, la probabilità che accada e come una possibile soluzione se presente.

## Interfaccia non intuitiva

- **Scope Triangle**: Scopo/Qualità
- **Impatto**: Critico
- **Probabilità**: Bassa
- **Azione**: Transfer

Avere un'interfaccia non intuitiva causerebbe grossi problemi nell'utilizzo del sito, tanto da avere sia dei rallentamenti da parte del personale che è costretto ad usarlo, sia da parte del cliente che potrebbe non gradire il software. In questo caso, ci si aspetterebbe una diminuzione del fatturato ed una perdita di clientela, causando un danno critico per l'azienda.

Il team è d'accordo nel ritenere che le eventualità siano basse o minime. Questo perchè i controlli che vengono svolti sono svariati ed è stato contattato un consulente per evitare problematiche di questo tipo.

Nell'eventualità che ciò accada, l'azienda chiederà i danni al consulente, in quanto non soddisfa i requisiti richiesti ed ha inoltre creato un danno all'azienda.

## Rallentamenti nello sviluppo

- **Scope Triangle**: Tempo
- **Impatto**: Alta
- **Probabilità**: Alta
- **Azione**: Mitigate

I rallentamenti nello sviluppo rimangono un rischio sempre presente quando si parla di sviluppo software. In questo caso, il team IT è piccolo e svolge altre attività oltre alla realizzazione del software. 

L'impatto è considerato alto poichè l'accumulo di ritardo non è quantificabile facilmente e potrebbe sforare la durata massima di 2 anni prevista durante la raccolta dei requisiti. Lo scopo di una gestione di un progetto, però, ha anche tra gli obiettivi quello di minimizzare i ritardi e avere delle timeline corrette. Il team IT si è inoltre accordato su come impostare le priorità in fasi critiche dove l'accumulo di ritardo è possibile o indotto da imprevisti che non riguardano il progetto (es. server non funzionanti), cercando di evitare il più possibile il context switch, che causa rallentamenti.

In fasi critiche è stata aperta la possibilità di incrementare il reparto informatico, reclutando programmatori per il progetto.

## Cambiamenti improvvisi di mercato

- **Scope Triangle**: Scopo/Qualità
- **Impatto**: Alta
- **Probabilità**: Minima
- **Azione**: Accept

Vista l'analisi di mercato che mostra un chiaro incremento in questo settore è stato considerato molto improbabile un cambiamento improvviso di mercato. 

## Difficile integrazione con strumenti esterni

- **Scope Triangle**: Tempo
- **Impatto**: Medio
- **Probabilità**: Medio
- **Azione**: Accept

L'integrazione con gli strumenti esterni potrebbe essere un fattore che aumenterebbe il ritardo dello sviluppo del progetto. Essendo principalmente dovuto da cause esterne (es. API utilizzate molto complesse o poco utili), non è possibile mitigare questo rischio. Essendo una feature opzionale, il ritardo accumulato potrebbe essere gestito anche dopo il rilascio della versione completa.

## Violazione o gestione non conforme dei dati sanitari degli utenti

- **Scope Triangle**: Scopo/Qualità
- **Impatto**: Critica
- **Probabilità**: Bassa
- **Azione**: Mitigate + Contingency plan

L'eventuale violazione dei dati personali degli utenti potrebbe essere un enorme problema per l'azienda. Oltre alle multe da pagare, ci sarebbe anche un grosso danno all'immagine aziendale. 

Per questo motivo le principali soluzioni adottate sono le seguenti:

- Durante e alla fine dello sviluppo, devono essere effettuati dei controlli rigidi sul trattamento personale dei dati.
- L'utilizzo di una polizza assicurativa per eventuali problemi, in modo da mitigare i danni in caso ci fossero.

L'utilizzo della polizza viene considerato un ulteriore controllo, poichè per accettare i termini assicurativi anche loro vorranno fare dei controlli più approfonditi su come vengono trattati i dati.

## Familiarizzare con API e tool esterni (database in cloud)

- **Scope Triangle**: Tempo
- **Impatto**: Bassa
- **Probabilità**: Medio
- **Azione**: Accept