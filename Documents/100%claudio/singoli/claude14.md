Issue N44: LU con TPO ma senza missione su Cway / AGV non consegna
Occorrenze: 10/07/2024, 16/07/2024, 08/01/2025, 24/07/2025
Descrizione generale: Una LU ha un TPO attivo in WAMAS ma nessuna missione corrispondente su Cway. La LU rimane bloccata per ore sulla stazione o nella posizione di partenza. Le picking station si bloccano in attesa.
Causa: (1) Il sistema genera 2 richieste AGV per lo stesso pallet; quando l'AGV riceve la prima, la seconda viene eliminata. (2) Ordini HIVE presenti ma non trasmessi a Rocla (issue lato Rocla). (3) Empty request residue dai test CR che occupano slot nella sequenza.
Soluzione / Workaround consolidato: Cancellazione del TPO e ricreazione, forzando le missioni HIVE. Cancellazione ordini HIVE vecchi. Riavvio pick station.
Frequenza: 4 occorrenze documentate tra 2024 e 2025. Classificata come issue ricorrente (N44).
Note: Root cause parzialmente identificata. Nel luglio 2025 trovati 6 ordini HIVE vecchi (da aprile) mai trasmessi a Rocla. Operatori informati di segnalare tempestivamente mancate consegne.
