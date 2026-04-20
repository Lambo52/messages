Empty pallet request errate / in eccesso / tipo incompatibile
Occorrenze: 30/07/2021, 06/08/2021 (D151), 06/02/2024, 22/03/2024, 28/03/2024, 20/03/2025
Descrizione generale: WAMAS genera empty pallet request errate: tipo di pallet non ammissibile (E invece di F), empty request in loop per ordini già serviti, 3 empty request per 2 destinazioni disponibili, request residue dai test CR. Le stazioni si bloccano in attesa di pallet vuoti che non arrivano o in loop.
Causa: (1) Configurazione MD500 che non copre casi di "negative picking line" seguito da "normal picking". (2) Reservation non cancellate su ordini già serviti. (3) Esecuzione contemporanea di empty request quando disponibile solo uno slot. (4) Empty request "zombie" rimaste dai test CR.
Soluzione / Workaround consolidato: Modifica manuale del tipo empty request. Cancellazione delle empty request in eccesso o obsolete. Verifica assenza di residui su tutte le stazioni dopo test CR.
Frequenza: 6 occorrenze documentate tra 2021 e 2025.
Note: La gestione dei residui dei test CR deve essere più accurata. Empty request obsolete risalenti fino al 2021 sono state trovate nel sistema nel febbraio 2024.
