## 24. Memoria / RAM / memory spike su WAMASAPP

**Occorrenze principali:**  
2021: 19/10  
2022: 27/06, 19/07  
2023: 19/04  
2024: 29/08  

**Descrizione generale:**  
Memoria WAMASAPP quasi esaurita, warning SNMP, picchi notturni/matutini, servizi da riavviare, Lighthouse/mobile down.

**Causa ricorrente:**  
Processi/script anomali; restart applicativi; Firefox/Lighthouse; startup post-deploy; memory leak non confermato.

**Soluzione / Workaround consolidato:**  
Chiusura processi; restart servizi; monitoraggio; disabilitazione script problematici.

**Frequenza:**  
Media-bassa: circa 5 occorrenze.

**Note:**  
Non sempre è stata trovata root cause definitiva; in alcuni casi il problema è rientrato dopo riavvio.
