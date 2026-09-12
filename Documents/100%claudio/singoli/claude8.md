## 8. AGV / ART / Rocla / Hive: offline, mancate missioni, deadlock, conferme errate

**Occorrenze principali:**  
2021: 24/06, 25/06, 28/06, 30/06, 08/07, 14/07, 27/08, 03/09, 07/09, 14/09, 24/09, 29/09, 22/10, 28/10  
2024: 02/01, 07/02, 22/04, 27/07  
2025: 28/04, 23/07  

**Descrizione generale:**  
AGV fermi, offline, in errore, non assegnati, deadlock a catena, missioni create ma non eseguite, veicoli fantasma, mancate conferme di pick/deposit, problemi dopo reboot Rocla/Hive.

**Causa ricorrente:**  
Comunicazione WMS-Rocla/Hive; porte bloccate; servizi Rocla non avviati; scanner sporchi; navigazione; errori di flotta; restart VM; interventi manuali; mancata conferma missione.

**Soluzione / Workaround consolidato:**  
Restart AGV/Rocla/Hive; rilascio porta; agvDisable/enable; pulizia scanner; rimozione AGV dal sistema; riassegnazione manuale missione; riavvio servizi; intervento fornitore Rocla.

**Frequenza:**  
Alta: circa 20 occorrenze, tutti gli anni con maggiore densità nel 2021.

**Note:**  
Nel 2024-2025 molti casi sono legati a riavvii server, porte di comunicazione, integrazione Hive/Rocla. Nel 2021 erano frequenti deadlock e problemi di flotta.
