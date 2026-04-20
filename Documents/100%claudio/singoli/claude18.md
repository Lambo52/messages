Lighthouse down / non funzionante / anomalie visive
Occorrenze: 29/12/2021, 21/07/2022, 22/07/2022 (post-riavvio), 29/01/2024, 13/12/2023, 20/12/2023
Descrizione generale: Lighthouse non è accessibile (login failed) o non mostra i pallet. Il sistema è "cieco" sullo stato dell'impianto. In alcuni casi le anomalie sono solo visive (cache del browser).
Causa: (1) Problemi generali del sistema (crash WAMAS, riavvio VM). (2) Cache del browser non aggiornata. (3) WAMAS tentava di eliminare un LU con attività di picking ancora attiva (race condition).
Soluzione / Workaround consolidato: Restart di Lighthouse. Pulizia cache browser. In un caso classificato come "one in a lifetime" race condition.
Frequenza: 6 occorrenze documentate tra 2021 e 2024.
Note: Il team raccomanda di fare sempre clear cache come prima azione in caso di anomalie visive su Lighthouse.
