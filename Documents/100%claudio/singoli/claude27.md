Negative picking / Deadlock spazio insufficiente (D159)
Occorrenze: 22/10/2024, 23/10/2024 (correlato)
Descrizione generale: Pick station bloccata in deadlock: la PO necessita di un pallet per negative picking ma tutte le location source e buffer sono piene, impedendo l'assegnazione.
Causa: Problema di sequenza: il sistema esegue prima i pallet HBW1 (sequence 0) riempiendo la stazione, ma non riesce poi a inserire l'empty LU (sequence 1) perché non c'è spazio. Si manifesta quando ci sono più di 4 sorgenti LU in una PO con negative picking.
Soluzione / Workaround consolidato: Finalizzazione manuale della PO del negative picking.
Frequenza: 2 occorrenze documentate nell'ottobre 2024.
Note: Fix pianificato con simulazione locale. Problema aggravato dall'errore del supporto che aveva bloccato una buffer location durante l'intervento.
