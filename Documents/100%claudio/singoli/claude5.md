Coda mfsPalQueue / mfArea bloccata — blocco totale TPO
Occorrenze: 25/01/2024, 14/05/2024, 20/06/2024, 11/07/2024, 28/12/2023, 29/04/2025
Descrizione generale: Un messaggio si blocca nella coda mfsPalQueue o mfArea, impedendo l'avvio di qualsiasi nuovo TPO. Tutte le picking station si fermano, le sorgenti non possono lasciare le stazioni, l'area automatica e manuale si bloccano completamente.
Causa: (1) Interruzioni della connessione al database (JdbcConnectionException) causate da brevi operazioni IT sul DB. (2) Messaggi con problemi che bloccano la coda di elaborazione. (3) Root cause spesso non determinata con precisione.
Soluzione / Workaround consolidato: Sblocco manuale della coda da parte del supporto SSI. In alcuni casi auto-ripristino notturno.
Frequenza: 6 occorrenze documentate tra 2023 e 2025.
Note: In almeno 2 casi il blocco è avvenuto durante la notte e si è risolto autonomamente. La causa radice strutturale non è mai stata completamente identificata. Workaround da implementare per evitare l'interruzione della comunicazione WMS-MFS è stato incluso in deploy successivi.
