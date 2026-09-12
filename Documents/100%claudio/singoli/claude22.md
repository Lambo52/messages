## 22. Configurazione flussi / FOG / optimum LU / replenishment / OG area / transport area

**Occorrenze principali:**  
2021: 28/06, 15/12  
2023: 10/03, 15/03  
2025: 13/01, 14/01, 15/01, 16/01, 03/02, 17/02  

**Descrizione generale:**  
TPO o replenishment creati verso aree errate; optimum LU basato su FOG invece di item/batch; shipping LU verso MAV invece di aree corrette; transport area/location staging non configurate; loading aid non abilitati.

**Causa ricorrente:**  
Configurazione OG area/transport area; logica optimum legata a FOG; master data loading aid mancante; location non staging; assegnazione area Azienda non definita.

**Soluzione / Workaround consolidato:**  
Configurazione OG area assignment; modifica transport area; rimozione FOG dal calcolo optimum; fix configurazioni; TPO manuali temporanei; test locale.

**Frequenza:**  
Media: circa 10-12 occorrenze, con picco nel 2025.

**Note:**  
Nel 2025 è stato affrontato organicamente il tema optimum LU/replenishment da Azienda, proponendo logiche basate su item/batch e replenishment prioritario da aree manuali.
