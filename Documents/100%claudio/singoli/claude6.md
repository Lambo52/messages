## 6. OBD / discharge / finalizzazione / quantità disallineate / carico truck

**Occorrenze principali:**  
2021: 02/07, 19/10, 15/12  
2022: 30/05, 16/09  
2023: 22/06, 14/09, 23/10, 08/11, 28/12  
2024: 08/01, 19/01, 29/02, 12/04, 12/06, 13/06, 26/08, 24/10  
2025: 30/05, 03/07, 04/06  

**Descrizione generale:**  
OBD che non cambiano stato, discharge bloccati o errati, quantità planned/delivered/loaded non allineate, finalizzazioni manuali necessarie, errori Java durante finalize/discharge, broken boxes, load/truck non chiudibili.

**Causa ricorrente:**  
Quantità errate; bug su broken boxes; stati OBD incoerenti; flag di loading/wholeLU; consolidamento stock da buffer a non buffer; azioni manuali; ordini splittati; mancata finalizzazione di linee.

**Soluzione / Workaround consolidato:**  
Correzione manuale quantità; finalizzazione manuale OBD/linee; rimozione flag broken boxes; ricreazione/reimport OBD; rilascio/relink LU; modifica stato loading; workaround su discharge.

**Frequenza:**  
Alta: circa 22 occorrenze, tutti gli anni.

**Note:**  
Il problema è trasversale: comprende sia bug applicativi sia errori operativi. Più volte è stato necessario intervenire manualmente sugli stati ordine.
