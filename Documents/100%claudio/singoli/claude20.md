Blocco pick station per picking order / PO activity residua non eliminata
Occorrenze: 22/01/2023, 26/02/2024, 22/07/2024, 13/09/2024, 29/12/2023
Descrizione generale: Le pick station si bloccano perché un picking order o una PO activity rimane attiva/connessa a una LU che non dovrebbe più essere associata. Il sistema non riesce a proseguire con nuovi ordini.
Causa: (1) Perdita dell'ordine a livello PLC durante riavvio. (2) LU con PO activity non eliminata dopo completamento (bug A168). (3) Interruzioni DB che causano perdita/corruzione di dati relativi a pick order. (4) Sequenze anomale con "report as full" che perdono la shipment LU.
Soluzione / Workaround consolidato: Finalizzazione manuale della PO. Disconnessione della LU dall'ordine. Release source LU per forzare la creazione del TO. Prenotazione su lost&found.
Frequenza: 5 occurrenze documentate tra 2023 e 2024.
Note: Fix pianificato dal team SSI per il caso A168. Il "report as full" è stato identificato come fonte di anomalie nella gestione della shipment LU.
