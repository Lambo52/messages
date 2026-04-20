Labeler Foiling "no printing data" / Stampante irraggiungibile post-deploy
Occorrenze: 16/11/2021, 24/02/2022, 28/08/2023, 17/10/2023, 04/12/2023, 27/12/2023
Descrizione generale: I labeler mostrano "no printing data" o il print server risulta irraggiungibile. L'area Foiling e le uscite si bloccano. I pallet in transito generano errori a cascata ("print server unreachable or specified printer does not exist"). In un caso il sistema appariva "come un albero di Natale" per gli errori.
Causa: (1) Configurazione stampante non inclusa nel pacchetto di deploy (TT08PC028_LEFT e RIGHT). (2) IP statico della stampante modificato. (3) Stampante fisicamente irraggiungibile. (4) Il servizio di stampa genera blocchi a catena sul sistema.
Soluzione / Workaround consolidato: (1) Aggiunta manuale della configurazione stampante mancante. (2) Reset del labeler. (3) Blocco temporaneo della corsia. (4) Spegnimento stampanti Foiling problematiche.
Frequenza: 6 occorrenze documentate tra 2021 e 2023.
Note: La configurazione delle stampanti Foiling è stata dimenticata in almeno 2 deploy successivi (agosto e ottobre 2023), segnalata come gap nel processo di packaging del deploy. Proposto monitoraggio IP delle stampanti critiche.
