# PND
La stima delle attività è stata effettuata utilizzando la tecnica del **Planning Poker**.
Questa metodologia consente di stimare la complessità relativa delle attività
attraverso l’uso di Story Points, favorendo il confronto tra i membri del team. 

Il Planning Poker è stato utilizzato per ridurre il margine di errore durante le stime, in quanto ogni membro del gruppo può esprimere il proprio parere considerando anche membri più o meno esperti.

Per le stime è stata utilizzata la scala di Fibonacci, utilizzata per evidenziare l'incertezza nell'aumentare della complessità che prevede l'attività.

Come unità di misura è stata utilizzata gli **Story Points**, che misurano la complessità dell'attività. Per quanto riguarda il volume settimanale del team, si stima che in totale si possa raggiungere i **8 SP a settimana**. La stima risulta essere così bassa considerando che tutti i membri del gruppo dovranno adempiere ad altri lavori durante tutta la durata del progetto(es. il CTO avrà tante riunioni, i programmatori svolgono anche supporto tecnico).


| Attività                 | Stima | Motivazione
|-----------------------------|-------|-------------------------------------------------------------|
| **1. Configurazione** | 8 | Tutte attività molto semplici, ma le pipeline potrebbero rallentare il processo 
| **2. UI/UX** | 55 | Risulta essere una parte fondamentale per il progetto, e seppur semplice, l'interfaccia grafica deve essere analizzata a fondo per non essere poi modificata radicalmente in corso d'opera
| **3. Gestione utenti e autenticazione** | 34 | Seppur con tante attività, è facilitata dal precedente lavoro sull'interfaccia grafica
| **4. Gestione del profilo dell'atleta** | 89 | Presenta numerose attività e complessità. La feature del calendario e i vari grafici portebbero richiedere molto tempo
| **5. Gestione documenti** | 34 | Non presenta criticità particolari, ma il controllo per il rispetto della normativa deve essere eccellente
| **6. Gestione del profilo dello specialista** | 21 | Non presenta criticità particolari
| **7. Hardening e supporto tecnico** | 55 | La stima così elevata è stata effettuata considerando l'aumentare della complessità data dagli imprevisti che sono sempre presenti a fine progetto. Da considerare comunque che il report e la rifattorizzazione prendono tanto tempo

Il tempo totale stimato è **296 SP**, che corrispondono a 37 settimane (poco più di 9 mesi), perfettamente in linea con le aspettative.

### Diagramma
Di seguito è stato creato il diagramma attraverso l'uso di **Canva**, un potente strumento utilizzato per tanti scopi. La creazione del diagramma è stata fatta al fine di avere un quadro completo delle dipendenze tra attività, in modo da riuscire a comprendere quali potrebbero essere i rallentamenti e le criticità di ciascuna attività. 

Diagrama: [PND](./PND.png)
Per una migliore visualizzazione si consiglia di utilizzare il [link](https://www.canva.com/design/DAG9Wz9HIcs/8Ej-hYgYiQCEiY8LljDWrA/edit?utm_content=DAG9Wz9HIcs&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) 