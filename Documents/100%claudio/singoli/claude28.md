## 28. Errori di input operatore su quantità/peso

**Occorrenze:**  
2024: 10/01, 12/01  

**Descrizione generale:**  
Quantità errate inserite su pallet/pick; peso calcolato troppo alto; WAMAS si bloccava durante il calcolo peso per MFS.

**Causa ricorrente:**  
Errore operatore; mancanza protezioni su input anomali.

**Soluzione / Workaround consolidato:**  
Analisi SMCOD/OGCOD; confronto con operatore e shift leader; spiegazione crash; proposta protezione.

**Frequenza:**  
Bassa: 2 occorrenze ravvicinate.

**Note:**  
Più che un guasto software, era un rischio operativo da input validation.
