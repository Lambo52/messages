## 18. Pending events / eventi non consumati / messaggi stuck

**Occorrenze principali:**  
2023: 17/10, 18/10, 28/12  
2024: 11/01, 16/01, 06/02, 14/10  
2025: 07/03, 29/04, 26/06  

**Descrizione generale:**  
Pending event bloccano SRM, crane, foiling, pick station o code; TU/LU inesistenti; eventi non consumati dopo errori o finalizzazioni; messaggi stuck che fermano MFS/device.

**Causa ricorrente:**  
Eventi residui dopo errori; LU cancellate con vincoli DB; TPO/PO finalizzati in modo incoerente; messaggi PLC/MFS non consumati.

**Soluzione / Workaround consolidato:**  
Eliminazione pending event; scollegamento LU; cancellazione messaggi stuck; reset; fix software; analisi log.

**Frequenza:**  
Media: circa 10-11 occorrenze.

**Note:**  
La soluzione immediata è quasi sempre manuale. Più volte è stata richiesta analisi root cause per evitare il ripetersi.
