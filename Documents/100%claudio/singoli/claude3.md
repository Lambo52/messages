## 3. Disallineamento fisico/logico pallet, ghost pallet, occupation without transport order

**Occorrenze principali:**  
2021: 28/06, 29/06, 02/07, 12/07, 19/07, 23/08, 10/08, 11/08, 16/09, 22/09, 29/09, 03/08, 27/07, 26/10, 30/12  
2022: 05/01, 21/01, 06/04, 18/01  
2023: 22/01, 28/02, 20/06  
2024: 14/11, 18/10  
2025: 28/01, 26/06  

**Descrizione generale:**  
Pallet fisicamente presenti ma logicamente assenti o posizionati altrove; pallet logici senza pallet fisico; ghost pallet; occupation senza transport order; Lighthouse e WAMAS non allineati; conveyor o SRM che vedono occupato dove non c’è pallet o viceversa. Impatto: pallet bloccati, crane/AGV fermi, pick station in attesa.

**Causa ricorrente:**  
Disallineamento tra WAMAS, MFS, PLC e sensori; interventi manuali; restart PLC/MFS; messaggi o annunci PLC persi; occupazioni residue; dati corrotti; mismatch dopo riavvii.

**Soluzione / Workaround consolidato:**  
Rebooking posizione; cancellazione occupazioni errate con CTOP; refresh/reset; book to lost and found/black hole; cancellazione ghost/temp; reset MFS; verifica sensori; intervento PLC quando necessario.

**Frequenza:**  
Alta: circa 25-27 occorrenze, tutti gli anni.

**Note:**  
Problema strutturale e ricorrente. Spesso risolto manualmente. Non risulta una soluzione definitiva unica; molte occorrenze dipendono da eventi diversi ma con stessa sintomatologia.
