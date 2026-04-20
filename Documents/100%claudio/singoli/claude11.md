Inventory block su LU / Issue D223 ricorrente
Occorrenze: 29/11/2021 (D189), 01/06/2023, 22/06/2023, 26/04/2023
Descrizione generale: Uno stock object ha il flag "block for inventory" attivo, impedendo la creazione di TPO e bloccando le picking station. Il TPO di ritorno automatico in HBW non viene creato. L'operatore non può proseguire.
Causa: Flag "block for inventory" applicato a livello di stock object (non di LU) senza causa chiara. Bug recidivante (D189, poi D223).
Soluzione / Workaround consolidato: Rimozione manuale dell'inventory block da parte del supporto SSI.
Frequenza: 4 occorrenze documentate tra 2021 e 2023.
Note: Issue classificata come ricorrente (D223). La causa dell'applicazione automatica del flag non è mai stata completamente determinata.
