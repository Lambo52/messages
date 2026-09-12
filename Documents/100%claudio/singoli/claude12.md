## 12. Spazio insufficiente / location piene / wait for storage failed / capacity zone

**Occorrenze principali:**  
2021: 24/06, 02/07, 26/07, 08/09, 25/08, 09/09, 15/09, 17/09  
2022: 19/05  
2024: 29/04, 08/08, 22/10  
2025: 15/04  

**Descrizione generale:**  
Pallet non stoccabili per mancanza spazio; zone piene; “wait for storage failed”; HBW senza location idonee; capacity zone in errore; deadlock tra buffer, empty pallet e source full.

**Causa ricorrente:**  
Aisle/location pieni; loading aid non compatibili; spazio HBW esaurito; routing specializzato; saturazione buffer; empty LU non inviata; mancanze di configurazione.

**Soluzione / Workaround consolidato:**  
Forzare altro aisle; liberare location; cancellare TPO; finalizzare PO; creare TPO manuali; inviare pallet a zone alternative; sblocco capacity; monitoraggio saturazione.

**Frequenza:**  
Media-alta: circa 15 occorrenze.

**Note:**  
Problema operativo ricorrente, spesso aggravato da saturazione fisica e logica. In alcuni casi è stata proposta una miglioria/CR per protezione automatica.
