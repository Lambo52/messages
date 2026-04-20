Issue A186: Empty LU request in loop / PO con priorità alta senza empty request
Occorrenze: 11/09/2024, 23/10/2024
Descrizione generale: Non appena un AGV deposita un pallet vuoto alla pick station, WAMAS crea un TPO verso S46 e genera una nuova empty request in loop. La stazione è bloccata in un ciclo infinito.
Causa: Una PO con priorità alta non ha né empty request né TPO per le sorgenti, ma viene trattata come la prima da eseguire. In altro caso, una gru si è bloccata causando l'uscita del pallet sorgente senza cancellazione dell'empty LU request del negative picking.
Soluzione / Workaround consolidato: Finalizzazione manuale della PO problematica. Cancellazione manuale dell'empty LU request residua.
Frequenza: 2 occorrenze documentate nel 2024. Classificata come ricorrente (A186).
Note: Analisi in corso su priorità di esecuzione PO nel codice. Mancanza implementativa nel software per la gestione delle empty request dopo disconnessione gru.
