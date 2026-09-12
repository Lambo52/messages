## 14. MFS down / code bloccate / mfsPalQueue / blocchi area automatica

**Occorrenze principali:**  
2022: 05/01, 21/01, 27/06  
2023: 28/02, 12/04, 13/12, 20/12  
2024: 26/01, 14/05, 11/07  
2025: 20/01, 28/04, 29/04  

**Descrizione generale:**  
MFS non disponibile o apparentemente spento; code mfsPal/mfArea bloccate; area automatica ferma; messaggi in coda che bloccano TPO; necessità di restart o sincronizzazione manuale dopo outage.

**Causa ricorrente:**  
Messaggi/pending event bloccati; problemi di avvio MFS; perdita comunicazione con device controller; DB/network; restart non coordinati; queue sature.

**Soluzione / Workaround consolidato:**  
Restart MFS; pulizia code/pending; sincronizzazione manuale device controller; reset ordini; riavvio servizi; intervento coordinato con PLC/Rocla.

**Frequenza:**  
Media-alta: circa 14 occorrenze.

**Note:**  
Spesso correlato a riavvii, deploy, outage o pending event. L’impatto è elevato perché blocca l’area automatizzata.
