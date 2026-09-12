## 21. Archiving / activity protocol / retention / tabelle enormi

**Occorrenze principali:**  
2022: 01/02, 11/11  
2023: 29/03, 31/03, 28/09, 04/12, 08/12  
2024: 08/04, 12/04  
2025: 29/01  

**Descrizione generale:**  
Job di archiving bloccato; activity protocol con milioni di righe; DB pieno; rallentamenti; ordini non archiviati; necessità di ridurre retention o eseguire truncate.

**Causa ricorrente:**  
Retention troppo lunga; job locked; volumi non previsti; tabelle protocollo enormi; mancanza history server.

**Soluzione / Workaround consolidato:**  
Sblocco job; riduzione retention; cleanup/truncate; rischedulazione; monitoraggio; pianificazione history server.

**Frequenza:**  
Media: circa 10 occorrenze.

**Note:**  
Strettamente correlato al gruppo performance DB. Più volte è stato raccomandato di non tagliare dati storici senza controllo e di predisporre archiviazione adeguata.
