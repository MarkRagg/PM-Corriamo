---
layout: default
title: Financial analysis
nav_exclude: true
---

# Financial analysis

In questa analisi si valuteranno i principali costi da sostenere, i rischi che potrebbero esserci e il potenziale ritorno economico. Tutte le valutazioni qui sotto riportate si riferiscono a delle stime.

## Obiettivi finanziari del progetto 

- Migliorare la qualità del servizio
- Migliorare il coordinamento interno
- Aumentare la popolarità dell'azienda
- Aumentare il numero di clienti
- Ridurre i tempi di erogazione delle informazioni (documenti consegnati direttamente sulla piattaforma, l'utente avrà bisogno di molti meno confronti con gli allenatori/medici)

## Costi di sviluppo
La stima dei costi di sviluppo si divide principalmente in due categorie: costi interni e costi esterni.

### Costi interni
I costi interni rappresentano la parte maggiore dell'investimento e principalmente sono legati ai salari dei tre sviluppatori che lavoreranno sul progetto. La stima di questi costi viene eseguita utilizzando la RAL come valore di riferimento.

- **Simone Zama**: Project Manager, CTO e sviluppatore -> 70.000€
- **Luca Ferar**: SCRUM Master e sviluppatore senior -> 50.000€
- **Alessio Bifulco**: Sviluppatore -> 35.000€

Ai fini di un calcolo più mirato si stima che la durata minima del progetto sia di 1 anno e la durata massima di 2 anni.

| Nome                 | Ruolo | Costo 1 anno | Costo 2 anni |
|----------------------|-------| --| ----------------------------------------------------------------|
| **Simone Zama** | Project Manager, CTO e sviluppatore |  70.000€ | 140.000€
| **Luca Ferar** | SCRUM Master e sviluppatore senior |  50.000€ | 100.000€
| **Alessio Bifulco** | Sviluppatore | 35.000€ | 70.000€
| **Totale costo** | | **155.000€** | **310.000€**

### Costi esterni
All'interno di questa sezione vengono aggiunti tutti i costi di licenze esterne, possibili consulenze e infrastrutture hardware per mantenere il sito attivo.

| Titolo  | Descrizione              | Stima costo |
 --|-------------------|---------------------------------------------|
| **Consulenza UX/UI** | Consulenza per ottenere un risultato grafico eccellente | 10.000€
| **Licenze software** | Riguardanti IDE e asset tool | 3.000€ / annuo
| **Dominio ed email** | | 500€
| **Campagne marketing** | Pubblicizzare il nuovo servizio (volantini, cartelloni) | 2.000€
| **Infrastrutture Hardware / Cloud** | Per la sicurezza dei dati personali dei pazienti | 10.000€ / annuo

Per un totale costi di **12.500€** di investimento iniziale e **13.000€** annuali.

### Costo totale

Si può notare come l'investimento iniziale sia minimo rispetto al budget, mentre i costi annuali potrebbero fare la differenza nel costo totale di sviluppo. Siccome la maggior parte di essi riguardano i salari degli sviluppatori, con una buona organizzazione si ridurrebbero eventuali ritardi di sviluppo e di conseguenza eventuali costi aggiunti. 

Il costo totale stimato del progetto varia tra 167.500 € (1 anno) e 336.000 € (2 anni), rientrando pienamente nel budget massimo previsto.

Per quanto riguarda i costi annuali di mantenimento (13.000€/annuo), dovrebbero essere ampiamente coperti dal valore economico atteso.


## Risk analysis
In seguito all'analisi dei costi, è necessario eseguire anche l'analisi dei rischi per capire come far fronte ad essi. I rischi sono stati gestiti secondo il modello Identification -> Assessment -> Mitigation.

### Legenda classificazione

- **Scope Triangle**
  - Tempo
  - Scopo/Qualità
  - Risorse/Costo
- **Impatto**
  - Bassa
  - Media
  - Alta
  - Critica
- **Azioni**
  - Accept: accettare il rischio
  - Avoid: rimodellare i requisiti per evitare il rischio
  - Mitigate: creare un piano per minimizzarne l'impatto negativo
  - Contingency planning: stabilisce cosa deve essere fatto se l'evento si verifica
  - Transfer: si utilizzano contromisure per trasferire l'impatto a terzi (assicurazioni, ricorso a terzi, ecc.)

### Tabella dei rischi

| Descrizione                                           | Scope Triangle | Impatto | Azione                                
|-------------------------------------------------------|----------------|---------|----------------------------------------
| Interfaccia grafica non intuitiva                     | Scopo/Qualità  | Critico | Transfer*                               
| Rallentamenti nello sviluppo                          | Tempo          | Alta    | Mitigate                                
| Cambiamenti improvvisi di mercato                     | Scopo/Qualità  | Alta    | Accept                                  
| Difficile integrazione con strumenti esterni          | Scopo/Qualità  | Medio   | Accept                                  
| Violazione o gestione non conforme dei dati sanitari | Scopo/Qualità  | Critico | Mitigate + Contingency planning         
| Familiarizzare con API e tool esterni (database in cloud) | Tempo      | Bassa   | Accept  

\* => Richiedere il rimborso al consulente UX/UI

## Ritorno economico atteso

Il ritorno economico di questo progetto si basa sul medio-lungo termine. In questo caso il ritorno economico atteso si divide in due macro categorie: **diretto** e **indiretto**.

Tra i ritorni economici diretti sono presenti:
- Aumento del fatturato => +5%-10%
- Aumento della fidelizzazione => -20% sugli abbandoni
- Aumento della popolarità di Corriamo s.r.l. => +15% visite sui profili social 

Per quanto riguarda i ritorni alcuni economici indiretti risulta più difficile utilizzare degli indicatori per quantificare il miglioramento, perciò verranno solo elencati:

- Migliore qualità del servizio
- Aumento del prestigio dell'azienda
- Meno tempo speso in comunicazioni frammentate
- Migliore coordinamento tra specialisti
- Possibilità di espansione futura dell'applicativo