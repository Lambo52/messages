AGV bloccati / non in sistema dopo riavvio o deploy
Occorrenze: 25/06/2021 (AGV 7), 27/07/2021, 27/08/2021, 10/08/2021, 27/12/2023, 02/01/2024, 07/02/2024, 22/04/2024, 28/04/2025
Descrizione generale: Dopo riavvii del sistema, deploy o problemi specifici, gli AGV risultano "NOT IN SYSTEM", non ricevono missioni, o restano bloccati. In alcuni casi tutti gli AGV sono fermi contemporaneamente. In altri, un singolo AGV fuori sistema blocca gli altri per "ghost presence".
Causa: (1) Servizi Rocla non riavviati correttamente o rimasti in modalità manuale. (2) Porta di comunicazione HIVE→Rocla bloccata (50032, 50011). (3) Bug nel comportamento GTP inspection order durante cancellazione TPO (A58). (4) Refresh MFS/WMS interrotto da Transport problematico. (5) Power outage sui server.
Soluzione / Workaround consolidato: (1) Riavvio dei servizi Rocla e impostazione modalità automatica. (2) Riavvio del server AGV. (3) Sincronizzazione manuale MFS tramite MF210 dopo power outage. (4) Cancellazione dei Transport problematici.
Frequenza: 9 occorrenze documentate tra 2021 e 2025.
Note: Dopo il primo episodio del 27/12/2023, è stata data indicazione di assicurarsi che i servizi Rocla siano attivi e in modalità automatica prima di ogni riavvio. La sincronizzazione manuale MFS-device controller è necessaria dopo ogni power outage.
