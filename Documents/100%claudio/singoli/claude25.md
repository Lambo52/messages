Blocco TPO area mobile / DcMobile worker crash
Occorrenze: 17/04/2024 (x2), 16/07/2024, 10/07/2024
Descrizione generale: Tutti i TPO tramite terminale mobile smettono di funzionare. Gli utenti vengono espulsi dall'applicazione mobile. Area foiling, loading, QC bloccate. Il DcMobile worker processa transport order non più esistenti, causando crash a cascata.
Causa: (1) DcMobile worker che elabora TO già terminati. (2) LU dell'area automatica che blocca la messaging queue del mobile (DCMobile). (3) Root cause non sempre determinata.
Soluzione / Workaround consolidato: Riavvio del DcMobile worker. Spostamento fisico della LU bloccante. Auto-ripristino in alcuni casi.
Frequenza: 4 occorrenze documentate nel 2024.
Note: Il problema del 17/04/2024 si è ripresentato due volte nello stesso giorno, richiedendo doppio riavvio del DcMobile.
