OBD bloccati in "release in progress" / "approval in progress"
Occorrenze: 16/09/2022, 20/04/2023, 10/05/2023, 19/05/2023, 04/12/2023, 30/04/2024, 29/04/2025
Descrizione generale: Decine o centinaia di OBD restano bloccati in stato "release in progress" o "approval in progress" per ore. Il processo di release impiega 40+ minuti invece dei normali 5-40 secondi. Impossibile processare release ordini e post-picking. Impatto operativo critico su spedizioni.
Causa: Job di release OBD che si blocca per: (1) query lente su tabelle enormi (OG002/OG025 con alto retention time). (2) Errori JdbcResourceBusyException / ORA-00054 per risorse DB bloccate. (3) Cambio del piano di esecuzione Oracle post-gather stats. (4) Volume crescente di dati "garbage" nelle tabelle.
Soluzione / Workaround consolidato: (1) Esecuzione gather statistics DB. (2) Forzamento del piano di esecuzione Oracle. (3) Riavvio istanza Oracle nei casi più gravi. (4) Aggiunta di log diagnostici sul punto di blocco del job.
Frequenza: 7 occorrenze documentate tra 2022 e 2025.
Note: Strettamente correlato al problema A1 (CPU WAMASDB elevata) e A6 (archiviazione bloccata). La soluzione definitiva richiederebbe il History Server e una gestione strutturale della crescita dei dati.
