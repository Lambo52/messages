## 10. Comunicazione WAMAS ↔ AS400 / Host / MQ / record interfaccia

**Occorrenze principali:**  
2021: 02/07  
2022: 11/02, 21/02, 14/03, 04/04  
2023: 13/02, 23/02, 30/08, 07/12, 11/12, 20/12, 21/12, 28/12  
2024: 27/08, 07/10  
2025: 14/04, 07/07  

**Descrizione generale:**  
Comunicazione assente o instabile tra WAMAS e AS400/Host; messaggi/record bloccati, in errore o non inviati; record 03, 14/15, 24/25, 30, 36, A5; outbound messages non in Finished; check-in message rifiutato; disallineamento dati.

**Causa ricorrente:**  
MqSender/MqReceiver non avviati o da resettare; messaggi con lunghezza non conforme; migrazioni DB; proxy/backup; flag di invio disattivati; problemi IT/AS400; deploy.

**Soluzione / Workaround consolidato:**  
Restart/reset MQ sender/receiver; script per correggere lunghezza messaggi; riattivazione flag; patch; risincronizzazione; intervento IT/host; reinvio manuale dove necessario.

**Frequenza:**  
Alta: circa 19 occorrenze, tutti gli anni.

**Note:**  
La causa esatta cambia, ma la famiglia è stabile: interfaccia WAMAS-Host/AS400 e code messaggi. Più episodi critici hanno richiesto intervento urgente.
