## 5. TPO bloccati, non creati, non attivi, senza missione Cway

**Occorrenze principali:**  
2021: 13/07, 03/08, 03/09, 17/09, 27/08  
2022: 07/01, 04/04, 05/04, 10/05, 26/04, 27/06, 01/07, 04/07  
2023: 23/02, 09/05, 29/08  
2024: 19/03, 16/07, 18/10, 01/08  
2025: 08/01, 10/02, 24/07, 26/07  

**Descrizione generale:**  
Transport order creati ma non eseguiti, TPO in stato NEW invece di ACTIVE, TPO senza missione su Cway, “wait for routing lock MFS”, TPO manuali non funzionanti, utenti mobile che vedono “no transport order”, pallet fermi nonostante ordine.

**Causa ricorrente:**  
Mobile worker/cache; comunicazione WMS-MFS; route non trovata; modifiche manuali; DB lento; problemi post-deploy; code bloccate; ordini Hive/Rocla non consumati.

**Soluzione / Workaround consolidato:**  
Restart mobile/DcMobile worker; suspend+resume TPO; cancellazione e ricreazione TPO; reset/refresh; restart MFS; fix software; rollback; pulizia ordini Hive/Cway.

**Frequenza:**  
Alta: circa 25 occorrenze, tutti gli anni.

**Note:**  
Spesso compare dopo deploy, riavvii, interventi manuali o congestione DB. La soluzione è stata frequentemente il workaround, mentre la root cause ha richiesto analisi specifiche.
