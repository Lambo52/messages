## 9. Empty LU request / empty pallet request duplicate, residue o non cancellate

**Occorrenze principali:**  
2021: 24/06, 12/07, 29/07, 30/07, 09/08, 27/09  
2024: 06/02, 19/03, 22/03, 28/03, 22/04, 23/04, 10/07, 01/10, 22/10, 23/10, 30/10  
2025: 20/03  

**Descrizione generale:**  
Richieste di pallet vuoto mancanti, duplicate, residue o non cancellate; pick station bloccate in attesa di empty pallet; loop AGV; empty request che occupano destination; richieste generate con tipo loading aid errato.

**Causa ricorrente:**  
Empty request non cancellata dopo fine PO/test; duplicate richieste per stesso PO; priorità di esecuzione; conflitti tra location; configurazione station/DA/HA; mancata assegnazione LU.

**Soluzione / Workaround consolidato:**  
Cancellazione manuale empty request; finalizzazione PO; riavvio stazione; nuova richiesta pallet vuoto; correzione configurazione; rimozione manuale pallet; fix software pianificati.

**Frequenza:**  
Alta: circa 19-20 occorrenze, soprattutto 2024.

**Note:**  
Nel 2024 è stato uno dei principali motivi di blocco pick station, spesso legato a test CR, DA/HA o empty request residue.
