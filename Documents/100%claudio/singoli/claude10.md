Memoria WAMASAPP critica / spike di utilizzo
Occorrenze: 19/10/2021, 27/06/2022, 19/07/2022, 29/08/2022, 19/04/2023
Descrizione generale: La memoria fisica disponibile su WAMASAPP scende sotto il 4% (soglia warning critico), o sale al 50%+ dopo deploy. I terminali mobili mostrano dialoghi inaccessibili, le pick station rallentano, i pallet si fermano per secondi tra un conveyor e l'altro.
Causa: (1) Script di pulizia memoria non funzionante. (2) Firefox con Lighthouse aperto che consuma RAM. (3) Picchi di avvio post-deploy. (4) Processi non necessari attivi.
Soluzione / Workaround consolidato: Chiusura dei processi non necessari (Firefox, MS Access). Riabilitazione manuale del DB constraint e riavvio servizi replenishment/reporting. Attesa del rientro progressivo post-deploy.
Frequenza: 5 occorrenze documentate tra 2021 e 2023.
Note: Il problema si è presentato con minore frequenza dopo il 2023, probabilmente per migliore gestione dei processi attivi sulla macchina.
