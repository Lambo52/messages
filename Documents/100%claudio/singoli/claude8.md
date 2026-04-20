Blocco area automatica per pending event / TPO bloccato in coda
Occorrenze: 06/02/2024, 28/12/2023, 11/01/2024, 16/01/2024, 14/10/2024, 29/04/2025, 26/06/2025
Descrizione generale: Un pending event o un TPO bloccato in una coda (SRM, MFS, o area automatica) impedisce il progresso di tutti gli altri TPO. L'area automatica si ferma, le picking station si bloccano, i crane non si muovono.
Causa: (1) Pending event per LU/TU inesistenti nel sistema. (2) Violazioni di database quando MFS tenta di eliminare LU ancora connesse a ordini attivi. (3) TPO con source=destination (creati erroneamente) che bloccano la coda. (4) Pallet con dati corrotti che causano crash del controller SRM.
Soluzione / Workaround consolidato: Eliminazione manuale dei pending event o dei TPO bloccanti da parte del supporto SSI. Cancellazione delle connessioni LU-ordine residue. Sblocco della coda.
Frequenza: 7 occorrenze documentate tra 2023 e 2025.
Note: Il problema delle LU fantasma da destacker (ticket 01339505) è stato segnalato come ricorrente quotidiano nel gennaio 2024, richiedendo eliminazione manuale dei pending event ogni giorno.
