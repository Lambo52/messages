### [11/07/24, 12:12] — AF pallet inviato in HBW e usato per negative picking, crash MFS
**Descrizione:** Empty AF inviato in HBW e usato per negative picking; MFS crasha.  
**Causa identificata:** Errore su negative picking con AF; parametro mancante.  
**Soluzione / Workaround:** Aggiunto parametro per evitare crash MFS.  
**Note:** AF non dovrebbe andare in HBW né essere usato per negative picking.
