### [07/06/22 13:18] — Post-deploy: StoCompAssemblage non creato / counters DB / unpicking station 9
**Descrizione:** Errore “StoCompAssemblage couldn’t be created”; problemi su rilascio OG buffer e pick station #9 in unpicking mode.  
**Causa identificata:** Counter in WAMAS non aggiornati correttamente per errore utente.  
**Soluzione / Workaround:** Fix; riavvio WAMAS alle pick station; ripristinato.  
**Note:** Patch incluse nel deploy. Possibile correlazione con: deploy.
