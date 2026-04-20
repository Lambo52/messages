SRM (Stacker Crane) bloccato per problemi vari
Occorrenze: 04/01/2022 (SRM01 Fine Positioning Error), 14/09/2021 (SRM1 manual handling), 15/09/2021 (SRM08 infeed), 22/10/2021 (SRM3 dati corrotti), 26/05/2023 (SRM02 desync), 14/10/2024 (SRM4 pending event), 14/11/2024 (SRM01 sensore), 07/11/2024 (SRM2 TPO cancellato), 26/06/2025 (SRM03 x2), 07/07/2025 (SRM03 terza volta)
Descrizione generale: I crane (SRM) si bloccano per cause diverse: errori di posizionamento fine, stato "manual handling" non resettabile, pallet sulle forche che blocca l'infeed, dati corrotti, desincronizzazione dopo spostamento manuale, pending event bloccati, sensori in errore, pallet logicamente presenti ma fisicamente assenti.
Causa: Molteplici: errori hardware/sensori, stati logici inconsistenti, pending event bloccati, dati corrotti, interventi manuali senza aggiornamento logico.
Soluzione / Workaround consolidato: Reset da MFS (MF210, spesso non accessibile alla manutenzione). Cancellazione pending event. Movimentazione manuale pallet. Resume TPO. Fix manuale tramite MFS.
Frequenza: 10+ occorrenze documentate tra 2021 e 2025.
Note: MF210 deve essere reso accessibile alla manutenzione ("magic button"). SRM03 (Crane 3) ha avuto 3 blocchi nella stessa settimana nel luglio 2025 prima che il fix strutturale venisse incluso nel deploy.
