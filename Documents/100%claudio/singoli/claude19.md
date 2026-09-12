## 19. Permessi / utenti / profili / diritti di accesso

**Occorrenze principali:**  
2021: 23/08, 22/12  
2022: 23/09  
2023: 06/02, 01/08  
2024: 22/01, 19/03, 21/03, 17/06, 18/09, 24/09  

**Descrizione generale:**  
Utenti senza accesso a dialog/tabelle; profili non abilitati; utenti non visibili dopo deploy; impossibilità di assegnare utente Desktop; differenze tra utenti; permessi insufficienti dopo migrazioni/deploy.

**Causa ricorrente:**  
Grants non generati dopo deploy; ruoli mancanti; configurazione stazione/utente errata; bug su assegnazione utente; profili non aggiornati.

**Soluzione / Workaround consolidato:**  
Assegnazione grants; attivazione utente su stazione; correzione ruolo; workaround con utente mobile locked; fix software; verifica permessi.

**Frequenza:**  
Media: circa 11 occorrenze.

**Note:**  
Ricorre spesso dopo deploy o modifiche DB. È un punto debole della procedura di rilascio.
