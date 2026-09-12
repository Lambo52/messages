## 2. Gestione stack / destacker / loading aid speciali D-F-H-U-DA-HA

**Occorrenze principali:**  
2021: 29/06, 09/08, 09/09, 27/09, 04/10, 11/10  
2024: 17/04, 18/04, 19/04, 22/04, 23/04, 24/04, 29/04, 12/06, 17/06, 19/06, 12/07, 15/07  
2025: 09/01, 10/01, 28/05  

**Descrizione generale:**  
Problemi legati a stack di pallet, destacker, loading aid D/F/H/U e soprattutto DA/HA: stack non riconosciuti, cubature errate, TPO verso stacker già occupati, AGV che depositano stack in location errate, empty request incoerenti, MFS o PLC non aggiornati, incompatibilità tra loading aid e stazione/flusso.

**Causa ricorrente:**  
Configurazione cubature errata o mancante; mapping location errato lato Rocla/MFS; PLC crane non aggiornato; finestra temporale in cui il destacker risulta libero mentre una stack è già in transito; loading aid non correttamente abilitati; parametri di replenishment o slaving errati.

**Soluzione / Workaround consolidato:**  
Correzione cubature; allineamento mapping Rocla; aggiornamento PLC crane; restart MFS; rilascio manuale ATX/stack; cancellazione empty request/TPO errati; aumento intervallo job per evitare creazione TPO duplicati; modifica configurazioni MD/FW; fix software pianificati.

**Frequenza:**  
Alta: circa 25-30 occorrenze, con picco nel 2024 e ricorrenze nel 2025.

**Note:**  
Nel 2024 il tema DA/HA è stato uno dei più impattanti. Nel 2025 è stata individuata con maggiore precisione la root cause sulla creazione della seconda stack verso stacker occupato, ma spesso il fix definitivo è rimasto pianificato o parziale.
