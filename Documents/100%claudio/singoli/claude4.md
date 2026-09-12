## 4. Performance DB / CPU WAMASDB / lentezza applicativa / execution plan

**Occorrenze principali:**  
2022: 05/05, 20/07, 22/07, 25/07, 08/08, 16/09, 29/09, 22/12  
2023: 29/03, 31/03, 20/04, 10/05, 12/05, 19/05, 30/08, 04/12, 07/12, 08/12  
2024: 30/04, 08/04, 12/04  
2025: 22/01, 23/01, 27/01, 29/04, 07/05  

**Descrizione generale:**  
CPU WAMASDB alta o oltre 90-96%, WAMAS lento, desktop inutilizzabile, ordini in “release in progress” o “approval in progress”, query in timeout, sessioni bloccate, tablespaces pieni, mobile terminal lenti. Impatto operativo: rallentamento generale o blocco potenziale.

**Causa ricorrente:**  
Tabelle enormi, retention troppo lunga, activity protocol/archiving non dimensionati, execution plan Oracle cambiati, statistiche non aggiornate, sessioni/session lock, carichi da query massive, tablespaces quasi pieni.

**Soluzione / Workaround consolidato:**  
Kill sessioni; restart DB/istanza; gather statistics; forzare execution plan; aggiungere datafile; ridurre retention; cleanup/truncate pianificati; rollback se causato da deploy; monitoraggio DBA.

**Frequenza:**  
Alta: circa 25-27 occorrenze, soprattutto 2022-2025.

**Note:**  
Fortemente correlato con archiving e tabelle di protocollo. Più volte è stato citato il bisogno di un history server o di una politica di retention più corta.
