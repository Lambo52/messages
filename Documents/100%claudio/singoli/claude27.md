## 27. Distribuzione pallet su corsie LCOD

**Occorrenze:**  
2024: 05/03, 06/03, 08/03  

**Descrizione generale:**  
WAMAS indirizzava pallet verso corsie LCOD lente invece di distribuirli sulle corsie più rapide; capacità disponibile non sfruttata correttamente; shipment LU instradate in modo non ottimale.

**Causa ricorrente:**  
Logica di distribuzione/capacità corsie; verifica mapping location-lane; comportamento variabile.

**Soluzione / Workaround consolidato:**  
Analisi log/query DB; verifica capacità; monitoraggio; raccolta screenshot.

**Frequenza:**  
Bassa: 3 occorrenze, tutte nel 2024.

**Note:**  
Alla fine di alcune verifiche WAMAS è risultato lavorare correttamente, ma il comportamento percepito era problematico.
