---
layout: default
title: WBS
nav_exclude: true
---

# Work Breakdown Structure (WBS)

La WBS prodotta sarà derivata partendo dal POS e dall'RBS, in quanto il team ha ritenuto che i documenti fossero già abbastanza specifici per poter produrre un ottimo WBS.

#### 1. Configurazione
- 1.1 Configurazione della repository
  - 1.1.1 Decidere quale software per il controllo di versione usare
  - 1.1.2 Configurazione delle Protection Rules per i branch
- 1.2 Configurazione dell'IDE e dei tool necessari
  - 1.2.1 Configurazione VSCode 
  - 1.2.2 Selezione delle varie estensioni da usare
  - 1.2.3 Comprare le licenze per tool AI di completamento codice 
- 1.3 Creazione pipeline per la _Continuous Integration & Deployment_
  - 1.3.1 Creazione pipeline per il testing automatico
  - 1.3.2 Creazione pipeline per il rilascio della documentazione
  - 1.3.3 Creazione pipeline per caricare le immagini di Docker
- 1.4 Creazione pipeline per il versioning
  - 1.4.1 Decidere quale sistema di versioning usare
  - 1.4.2 Creare pipeline per i check sui commit
  - 1.4.3 Creare pipeline per il sistema di versioning precedentemente deciso

#### 2. UI/UX
- 2.1 Insieme al consulente, creare i mockup per l'interfaccia grafica
  - 2.1.1 Cercare un consulente affidabile
  - 2.1.2 Creazione interfacce grafiche
- 2.2 Creare dei tutorial per gli atleti
  - 2.2.1 Tramite i mockup, creare dei tutorial
  - 2.2.2 Attraverso i tutorial, verificare la semplicità dell'applicazione
  - 2.2.3 Effettuare dei test con dei target user
- 2.3 Creare dei tutorial per gli esperti
  - 2.3.1 Tramite i mockup, creare dei tutorial
  - 2.3.2 Attraverso i tutorial, verificare la semplicità dell'applicazione
  - 2.3.3 Effettuare dei test con gli specialisti
- 2.4 Usabilità dell'interfaccia
  - 2.4.1 Attraverso i dati raccolti dai test, rimodellare l'interfaccia
  - 2.4.2 Verificare l'accessibilità dell'interfaccia per persone daltoniche, sorde o cieche 

#### 3. Gestione utenti e autenticazione
- 3.1 Registrazione login utenti
  - 3.1.1 Gestire la creazione di token
  - 3.1.2 Inserire dei controlli sulle password
  - 3.1.3 Modellare la salatura delle password
  - 3.1.4 Creazione interfaccia accesso
  - 3.1.5 Creazione interfaccia registrazione
  - 3.1.6 Creazione interfaccia recupero password
  - 3.1.7 Utilizzo di librerie per invio mail per il recupero password
- 3.2 Gestione profilo personale
  - 3.2.1 Creazione interfaccia per la visualizzazione del profilo
  - 3.2.2 Creazione interfaccia per la modifica del profilo
- 3.3 Gestione ruoli (atleta, specialista, admin)
  - 3.3.1 Decisione di cosa visualizzare nei vari ruoli
  - 3.3.2 Inserimento del ruolo nel token
  - 3.3.3 Implementazione effettiva dei permessi dei vari ruoli
- 3.4 Autenticazione sicura
  - 3.4.1 Implementazione autenticazione a due fattori (facoltativo per l'utente, obbligatorio per il personale)
  - 3.4.2 Implementazione autenticazione tramite passkey (facoltativo per l'utente, obbligatorio per il personale)

#### 4. Gestione del profilo dell'atleta
- 4.1 Visualizzazione dati personali
  - 4.1.1 Creazione interfaccia 'Home' 
  - 4.1.2 Interfaccia dedicata al calendario
  - 4.1.3 Implementazione notifiche per ogni visita nel calendario 
- 4.2 Storico allenamenti
  - 4.2.1 Interfaccia dedicata agli allenamenti
  - 4.2.2 Caricamento manuale degli allenamenti
  - 4.2.3 Creazione dei grafici per i principali dati dell'allenamento
    - Frequenza cardiaca
    - Passo: min/km
    - Cadenza corsa
    - Mappa del percorso
  - 4.2.4 (Plus) Caricamento automatico delle attività tramite integrazione con device esterni
- 4.3 Storico referti e documenti clinici
  - 4.3.1 Interfaccia dedicata ai referti e documenti
  - 4.3.2 Interfaccia dedicata all'apertura di un unico documento
- 4.4 Consultazione piano alimentare
  - 4.4.1 Interfaccia dedicata all'alimentazione
  - 4.4.2 Visualizzazione pasti giorno per giorno
  - 4.4.3 Possibilità di inserire gli alimenti mangiati durante il giorno
  - 4.4.4 Possibilità di inserire il peso in data x
  - 4.4.5 Possibilità di inserire note nei vari giorni utili poi allo specialista
- 4.5 Visualizzazione progressi
  - 4.5.1 Implementazione algoritmi per calcolare i miglioramenti
  - 4.5.2 Implementazione di grafici per il confronto prestazioni mese per mese
  - 4.5.3 Implementazione di grafici per il confronto tra referti (es. analisi del sangue)

#### 5. Gestione documenti
- 5.1 Caricamento documenti
  - 5.1.1 Upload documenti da parte dello specialista
  - 5.1.2 Validazione formato e dimensione file
- 5.2 Modifica e aggiornamento
  - 5.2.1 Possibilità di modificare i documenti da parte dello specialista
- 5.3 Archiviazione sicura
  - 5.3.1 Possibilità di scaricare i documenti da parte dell'atleta
- 5.4 Organizzazione per categoria
  - 5.4.1 Organizzare i documenti per categoria
  - 5.4.2 Implementazione di filtri per data
  - 5.4.3 Implementazione barra di ricerca
- 5.5 Rispetto della normativa GDPR
  - 5.5.1 Ulteriore controllo al trattamento dei dati personali
  - 5.5.2 Inserimento cookies per il trattamento dei dati personali

#### 6. Gestione del profilo dello specialista
- 6.1 Accesso ai profili assegnati
  - 6.1.1 Lista atleti seguiti
  - 6.1.2 Implementazione filtri e barra di ricerca
- 6.2 Consultazione dati atleta
  - 6.2.1 Interfaccia profilo atleta
  - 6.2.2 Possibilità di vedere i documenti allegati all'atleta
- 6.3 Inserimento note e aggiornamenti
  - 6.3.1 Possibilità di inserire note ai documenti degli atleti
  - 6.3.2 Possibilità di inserire note private ai profili degli atleti
- 6.4 Comunicazione interna
  - 6.4.1 Implementazione chat con colleghi
  - 6.4.2 Possibilità di comunicazioni rapide alla segreteria

#### 7. Hardening e supporto tecnico
- 7.1 Backup e recovery
  - 7.1.1 Duplicazione Database per backup
  - 7.1.2 Uso di Kubernetes per le server replicas
- 7.2 Integrazioni con sistemi esterni
- 7.3 Supporto a estensioni future
  - 7.3.1 Rifattorizzazione finale del codice per estensioni future
  - 7.3.2 Fix bug minori
  - 7.3.3 Documentazione del codice
  - 7.3.4 Report finale
