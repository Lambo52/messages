Problema NullPointerException / broken boxes (A176)
Occorrenze: 12/06/2024, 26/08/2024, 17/06/2024 (correlato)
Descrizione generale: Errore NullPointerException durante la finalizzazione di una linea OBD quando il flag "broken boxes" è attivo. Il sistema va in crash al click su "Finalizza".
Causa: Bug nel codice A176: la funzione prjCheckIfIsBrokenBoxesLD ha una condizione nulla non gestita. Check errato nella logica di finalizzazione dell'OBD.
Soluzione / Workaround consolidato: Rimozione temporanea del flag "broken boxes" per consentire la finalizzazione.
Frequenza: 3 occorrenze documentate nel 2024.
Note: Fix previsto al deploy successivo. Correlato anche a problemi con "pieces from HOST" come feature separata.
