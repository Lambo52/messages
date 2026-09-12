## 1. Deploy / patch / rollback con regressione o configurazione mancante

**Occorrenze principali:**  
2021: 27/07, 04/08, 11/08, 27/08, 26/11  
2022: 31/01, 01/02, 04/04, 02/05, 09/05, 23/05, 01/07, 23/09  
2023: 06/02, 01/08, 28/08, 29/08, 17/10, 23/10, 13/11, 04/12, 07/12  
2024: 12/02, 19/03, 22/04, 17/06, 07/10  
2025: 20/01, 24/03  

**Descrizione generale:**  
Dopo un deploy o una patch si sono verificati blocchi funzionali, regressioni, mancanza di configurazioni, permessi non allineati, client non aggiornati, problemi a stampanti, labeler, mobile terminal, TPO, OBD, comunicazioni host o DB. L’impatto operativo è stato spesso elevato: stazioni ferme, area automatica rallentata o bloccata, utenti espulsi, necessitá di rollback.

**Causa ricorrente:**  
Pack di deploy incompleti o con bug; script di grants/migrazione non eseguiti o obsoleti; parametri non visibili o non migrati; versioni client non aggiornate; modifiche DB non allineate; configurazioni locali perse.

**Soluzione / Workaround consolidato:**  
Rollback alla versione precedente; restart servizi/istanza; esecuzione script di grants; ripristino configurazioni stampanti/parametri/permessi; aggiornamento PC/client; fix successivo con nuovo deploy.

**Frequenza:**  
Molto alta: circa 30+ occorrenze, tutti gli anni.

**Note:**  
È una delle cause trasversali più rilevanti. Spesso il deploy ha introdotto o rivelato problemi di permessi, master data, stampanti, mobile terminal, DB e comunicazioni. In più occasioni è stato necessario rollback in giornata o deploy correttivo serale.
