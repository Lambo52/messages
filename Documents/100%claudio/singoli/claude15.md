Issue A138: Doppio TPO verso destacker già occupato
Occorrenze: 09/01/2025, 10/01/2025, 28/05/2025
Descrizione generale: WAMAS crea un TPO per un secondo stack verso il destacker mentre il primo stack è ancora in transito. L'AGV arriva con il secondo stack su una posizione già occupata.
Causa: Finestra temporale in cui MFS non vede il TPO attivo per lo stack master mentre quello per la sub-LU è in creazione. Se il job di replenishment gira in quel momento, genera un secondo TPO verso un destacker già pieno.
Soluzione / Workaround consolidato: Rilascio manuale dell'ATX con il secondo stack. Proposta di aumentare l'intervallo del job a 5-10 minuti come misura temporanea.
Frequenza: 3 occorrenze documentate nel 2025. Issue A138 ancora aperta.
Note: Il caso si applica sia a stack DA che AF. Fix strutturale necessario ma non ancora implementato al luglio 2025.
