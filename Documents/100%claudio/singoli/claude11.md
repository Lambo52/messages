## 11. Terminali mobile / rete / WiFi / lentezza / utenti espulsi

**Occorrenze principali:**  
2021: 04/08, 07/08, 15/12, 30/12  
2022: 21/01  
2023: 13/11, 04/12  
2024: 18/07, 24/07  
2025: 16/01, 20/01, 22/01, 27/01, 28/01, 31/01, 03/02  

**Descrizione generale:**  
Terminali mobili lenti, bloccati, disconnessi, con timeout, utenti espulsi da WAMAS, errori di rete durante discharge, impossibilità di connettersi al server. Impatto: operatori manuali/carrellisti fermi.

**Causa ricorrente:**  
Problemi rete/WiFi/internet; carico DB; worker mobile da riavviare; deploy; configuration change; sessioni appese; problemi infrastrutturali esterni.

**Soluzione / Workaround consolidato:**  
Restart terminal/mobile worker; kill sessioni; verifica rete/WiFi; rollback/fix dopo deploy; riavvio DC Mobile; contatto IT/call center quando esterno.

**Frequenza:**  
Alta: circa 19 occorrenze, tutti gli anni; molto frequente nel 2025.

**Note:**  
Nel 2025 la lentezza mobile è stata spesso collegata a query discharge/location Azienda e carico DB, con workaround temporaneo di restart worker.
