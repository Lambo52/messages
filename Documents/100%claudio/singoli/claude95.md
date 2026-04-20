[06/09/2023, 17:46] — "Red bubbles", bug divisione per zero (CR02)
Descrizione: Numerose red bubbles. Pallet non in movimento. Reset inefficace. Causa identificata: Stock object con quantità = 0 causava divisione per zero nella logica CR02. Soluzione / Workaround: Eliminazione stock object con qty 0. Note: Ticket aperto per fixare il caso stock con qty 0.
