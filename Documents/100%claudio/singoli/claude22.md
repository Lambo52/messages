EMS (monorail) si ferma / problemi con safety door e loop
Occorrenze: 31/07/2021 (stop a mezzanotte venerdì, 2 occorrenze), 21/01/2022, 11/02/2022, 30/06/2025, 28/07/2025
Descrizione generale: Il sistema monorail EMS si ferma o diventa non disponibile. Tutte le picking station collegate si bloccano. L'apertura della safety door di un singolo loop blocca tutti i veicoli su tutti i loop.
Causa: (1) Pattern di stop a mezzanotte del venerdì (possibile "controlled stop" per evacuazione antincendio, porta aperta). (2) EMS configurato come un unico device controller in MFS: l'apertura di una door invia emergency stop a tutto l'EMS. (3) Problemi specifici ai veicoli (EMS VE006).
Soluzione / Workaround consolidato: Stop/start EMS + impulso manuale su veicolo. Per il problema safety door: forzamento del flag emergency stop a zero nel messaggio TT1636 (workaround temporaneo per lavori agosto 2025). Soluzione definitiva: split EMS in 3 device controller separati (CR necessaria, issue G02 aperta dal 28/01/2022).
Frequenza: 6 occorrenze documentate tra 2021 e 2025.
Note: L'issue G02 (split EMS) è stata aperta nel gennaio 2022 ma al luglio 2025 non era ancora implementata. Il workaround con forzamento del flag è stato confermato accettabile per il periodo dei lavori di agosto 2025 ma non risolve il problema strutturale.
