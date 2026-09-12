## 16. Inventory block / inventory order / GTP Inventory

**Occorrenze principali:**  
2021: 29/11  
2022: 22/12  
2023: 07/03, 26/04, 01/06, 22/06  
2024: 08/01, 10/10, 19/12  
2025: 08/03  

**Descrizione generale:**  
LU o stock object bloccati da inventory block; inventory order duplicati; workstation che non ripartono; stazioni impostate erroneamente in GTP Inventory; ordini inventory creati su LU con TPO storage.

**Causa ricorrente:**  
Flag inventory residui; ordini inventory duplicati; station kind errato; creazione inventory da area non idonea; constraint DB.

**Soluzione / Workaround consolidato:**  
Rimozione inventory block; cancellazione righe/order inventory; correzione station kind; completamento TPO; creazione inventory solo da storage.

**Frequenza:**  
Media: circa 12 occorrenze.

**Note:**  
Il problema è ricorrente soprattutto su LU/source bloccate. In più casi è bastato rimuovere il flag, ma sono servite anche regole operative più precise.
