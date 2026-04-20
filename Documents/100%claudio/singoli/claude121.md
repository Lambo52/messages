[19/03/2024, 08:52] — Post-deploy: TPO senza missione AGV / double empty requests
Descrizione: Pallet restano alle stazioni per ore senza missioni. Sistema lento. Causa identificata: Pallet con PO cancellata dall'AGV pool. Le doppie empty request erano comportamento atteso della CR Report as Full. Soluzione / Workaround: TPO resettato manualmente. Bug CR "Allocate User" identificato. Note: —
[21/03/2024] — CR Allocate User: Bug condizione assegnazione PPLU
Descrizione: Con nessun utente assegnato, il sistema assegnava anche PPLU allocati alla stazione sbagliata. Causa identificata: Condizione errata nel codice. Soluzione / Workaround: Fix implementato e testato. Deploy 25/03. Note: Workaround: creare utenti con doppi permessi Desktop+Mobile.
