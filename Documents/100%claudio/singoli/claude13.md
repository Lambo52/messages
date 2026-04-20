WAIT FOR CAPACITY ZONE SLAVING — deadlock Wunderwuzzi
Occorrenze: 27/07/2021, 06/08/2021
Descrizione generale: Tutti i pallet destinati alla zona SLAVING (ingresso Wunderwuzzi) mostrano "WAIT FOR CAPACITY ZONE SLAVING" anche con la zona fisicamente libera. 4-9 stazioni su 12 impattate.
Causa: TPO per pallet non esistenti (create per intervento manuale errato o inviate erroneamente) che occupavano capacità logica della zona SLAVING.
Soluzione / Workaround consolidato: Eliminazione delle TPO fantasma da parte di SSI. Capacità zona SLAVING aumentata a 2. Fix pianificato per prossimo build: pallet in NOK con MD occupato → bufferizzazione automatica in S46.
Frequenza: 2 occorrenze documentate nel 2021 (segnalato come ripetuto anche successivamente).
Note: Il Wunderwuzzi è il punto centrale di smistamento; un blocco qui paralizza l'intera automazione.
