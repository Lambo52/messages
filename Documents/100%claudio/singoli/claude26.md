Errore quantità anomala da operatore / Crash sistema calcolo peso
Occorrenze: 10/01/2024, 12/01/2024
Descrizione generale: L'operatore (stesso utente lp65) conferma quantità impossibili durante l'inventario (5.135 SC e 6.153 pezzi invece di 0). Il peso calcolato supera la soglia massima (~65.353 unità / ~104.000 kg), causando crash del sistema di calcolo peso MFS.
Causa: Errore dell'operatore (possibilmente errore di scansione). Il sistema non aveva protezione contro valori impossibili.
Soluzione / Workaround consolidato: Auto-ripristino del sistema. Contatto con l'operatore. Proposta protezione software: non consentire conferma di quantità > 2x pallet piena.
Frequenza: 2 occorrenze documentate nel gennaio 2024 (stesso operatore).
Note: La protezione software è stata proposta ma richiedeva modifiche estese al sistema. Si è deciso di affrontare il problema con l'operatore.
