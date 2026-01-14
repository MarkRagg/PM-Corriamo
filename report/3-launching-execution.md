---
layout: default
title: Launching and execution
nav_order: 4
---

# Launching and execution
Ora che il progetto è stato definito ed è correttamente pianificato, il team è pronto per passare alla fase di launching and execution. In questa fase vengono concordati alcuni aspetti pratici che serviranno durante lo sviluppo.

## Kick-off meeting
Questa fase inizia con un breve kick-off meeting. Questo incontro è destinato principalmente alla presentazione dei vari aspetti del progetto e la decisione delle modalità operative da seguire durante lo sviluppo.

In particolare le fasi del meeting sono:

- Introduzione
- Presentazione del progetto da parte del committente
- Presentazione del progetto da parte del project manager
- Presentazione dei membri del team
- Presentazione delle milestones e dell'approccio scelto (SCRUM).
- Identificazione tools da utilizzare
- Decisione delle regole operative
  - Problem solving
  - Decision making
  - Conflict resolution
  - Team meeting

### Tools

- **GitHub**: Piattaforma utilizzata per la gestione della repository e delle pipeline di testing. Presenta anche delle feature per l'issue tracking e tool per il project management, come la gestione dei task, Kanban, team planning, bug tracker e roadmap.
- **Canva**: Piattaforma largamente utilizzata per creare presentazioni. Al suo interno è possibile anche creare diagrammi e flowchart.
- **Microsoft teams**: Software per creare meeting online, utile anche grazie al calendario integrato che permette una facile pianificazione della settimana.

## Matrice di responsabilità
Come matrice di responsabilità è stata selezionata la matrice **RASCI**
- **R** => **Responsabile**: Responsabile dell’attività e del suo completamento con
successo
- **A** => **Accountable**: Incaricato dell’approvazione del risultato dell’attività
- **S** => **Support**: Risorsa assegnata per supportare il responsabile
- **C** => **Consulted**: Disponibile per assistere il responsabile
- **I** => **Informed**: Membro che deve essere tenuto informato sullo stato di avanzamento

Il progetto comprende delle parti che riguardano diversi stakeholder (es. allenatore, nutrizionista, medico ecc..), per ogni task relativo ad un ambito specifico, verrà assegnato un esperto del dominio che potrà essere consultato per il chiarimento di dubbi riguardanti la sua materia. Questa assegnazione non verrà inserita all'interno della matrice perchè l'unico ruolo che avrebbe l'esperto riguarderebbe solo uno specifico task e, per non togliere troppo tempo al suo lavoro, il suo supporto ha un limite temporale.


| Attività               | Simone Zama| Luca Ferar | Alessio Bifulco |
|----------------------|-------------|-------------|-------------------------|
| **Configurazione progetto** | R | C | I
| **UI/UX** | R | C | I
| **Creazione tutorial vari** | A | I | R
| **Registrazione ed autenticazione** | I | R | C
| **Gestione profilo personale e ruoli** | A | R | I
| **Storico allenamenti e progressi** | R | C | I
| **Storico referti** | C | R | S
| **Consultazione piano alimentare** | A | S | R
| **Gestione documenti** | I | C | R
| **Controllo normativa GDPR** | R | C | S
| **Gestione profilo specialista** | I | S | R
| **Backup e recovery** | A | R | S
| **Refactor e documentazione** | R | C | C

## Regole operative per il team
Dopo aver creato la matrice di responsabilità, il team si è focalizzato sulle regole operative che verranno utilizzate durante lo sviluppo del software.
### Problem solving
Come metodo di problem solving ci si è affidati ad un approccio standard, largamente utilizzato nello sviluppo di software, i cinque passi di **Daniel Couger**:

- **1. Definizione del problema**: si identifica il problema ed il "proprietario"
- **2. Raccolta dati rilevanti e cause**: si raccolgono i dati e le cause che hanno portato al problema
- **3. Generazione idee**: il team comunicherà per raccogliere idee utili alla risoluzione del problema
- **4. Valutazione e ranking idee**: si valuteranno le idee e le verrà assegnato un ranking  (dalla più utile, alla meno utile)
- **5. Sviluppo piano d'azione**: verrà, infine, sviluppato un piano per risolvere il problema partendo dalle idee generate

### Decision making
Come approccio al decision making il team ha deciso il **Consultative style**. La soluzione verrà ideata a partire dalla consultazione dei membri del team, dalle informazioni ed idee che ne vengono fuori. **Il verdetto finale rimane sempre al responsabile**, che prenderà la decisione finale.
Il responsabile scelto è **Simone Zama**, in quanto CTO dell'azienda.

### Team meetings

Sono state introdotte delle linee guida per gestire al meglio i meeting, in modo che abbiano uno scopo ben preciso, chiarire la frequenza e la durata di essi.

A tal senso, sono state create delle "categorie" di meeting per facilitarne l'utilizzo durante lo sviluppo:

- **Daily standup Meeting**: Sono incontri quotidiani molto brevi (max. 15 minuti) effettuati all'inizio del turno di lavoro per aggiornare gli altri membri del team in cosa si sta lavorando e come sta procedendo. Questo tipo di meeting è necessario per l'approccio al framework SCRUM.

- **Sprint review**: Sono incontri che si effettuano alla fine di uno sprint, possibilmente il venerdì pomeriggio (orario molto apprezzato da tutti i membri del team e dagli stakeholder, in quanto può essere un'attività leggera e diversa rispetto alla monotonia del lavoro). In questo meeting vengono presentati al committente i progressi fatti e si ascoltano eventuali modifiche. In alcuni e specifici meeting saranno anche presenti gli esperti del dominio per quanto riguarda feature che dovranno poi utilizzare loro.

- **Sprint planning**: Sono incontri che si effettuano per dare inizio al prossimo sprint, definirne gli obiettivi e deciderne la pianificazione. Questo tipo di meeting (insieme alla sprint review) viene eseguito ogni **due settimane**, solitamente il lunedì mattina, ed ha una durata massima di 2 ore.

- **Help meeting**: Sono creati al bisogno quando un membro del team non sa come risolvere un problema, la durata è variabile, ma per problemi di minore entità si sta un massimo di 1 ora.

- **Support meeting**: Un meeting creato da un membro del team con un esperto del dominio. Lo scopo è quello di chiedere delle informazioni riguardanti le feature che poi utilizzerà lo stakeholder stesso, in modo da agevolarne la creazione. La durata massima è di 30 minuti.   

## Regole per il cambio di scope
Ci potrebbero essere dei casi in cui gli stakeholder, non contenti del risultato, abbiano la necessità di attuare dei cambiamenti di scope. In tal caso, viene definita una procedura formale per valutare ed in caso attuare questo tipo di cambiamenti:

- **Proposta di cambiamento di scope**: Uno dei membri del team o il committente può proporre un cambiamento di scope, a seguito di nuove idee o problemi sorti durante lo sviluppo

- **Analisi della richiesta**: Il team si riunisce per capire se la proposta possa essere una buona idea e ne deduce la fattibilità

- **Analisi dell'impatto del cambiamento**: Se la proposta viene considerata idonea, si passa all'analisi dell'impatto che essa avrà nel progetto, sia in termini di tempo e costi, sia in termini di risultato finale e relativi benefici

- **Riunione per la decisione finale**: Viene creato un incontro insieme al committente dove il Project Manager espone l'analisi che produce il cambiamento di scope e il committente, insieme al P.M., decide se approvare il cambiamento.