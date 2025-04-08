# MagOn
Tool di gestione magazzino

#### 1. **Introduzione**
   - **Obiettivo del Progetto:** Descrivere l'obiettivo principale dell'applicazione.
   - **Ambito di Applicazione:** Specificare le funzionalità principali e le aree coperte dal sistema.

#### 2. **Requisiti Funzionali**
   - **Calcolo Automatico dei Pezzi:** Dettagliare come il sistema calcolerà i materiali necessari.
   - **Gestione della Distinta Base:** Descrivere la gestione delle distinte base per i vari componenti.
   - **Monitoraggio del Magazzino:** Spiegare come il sistema terrà traccia delle quantità in magazzino.
   - **Generazione di Report:** Specificare i tipi di report che il sistema genererà.
   - **Documenti di Carico e Trasporto:** Descrivere il processo di generazione dei documenti.

#### 3. **Requisiti Non Funzionali**
   - **Prestazioni:** Specificare i requisiti di performance.
   - **Sicurezza:** Dettagliare le misure di sicurezza da implementare.
   - **Scalabilità:** Considerazioni per la futura espansione del sistema.

#### 4. **Architettura del Sistema**
   - **Panoramica dell'Architettura:** Descrivere l'architettura generale (client-server, microservizi, ecc.).
   - **Tecnologie Utilizzate:** Elencare le tecnologie e i framework scelti.

#### 5. **Diagrammi**
   - **Diagramma di Flusso:** Includere un diagramma di flusso dettagliato.
   - **Diagramma ER (Entity-Relationship):** Per il database.

#### 6. **Piani di Implementazione**
   - **Timeline del Progetto:** Fasi di sviluppo e tempistiche.
   - **Risorse Necessarie:** Team e strumenti richiesti.

#### 7. **Conclusioni**
   - **Prossimi Passi:** Azioni successive per avviare il progetto.

### Diagramma di Flusso

1. **Inizio**
   - Avvio del processo di gestione del magazzino.

2. **Inserimento Dati Progetto**
   - Input delle specifiche del progetto (dimensioni, tipo di allestimento, ecc.).

3. **Calcolo Materiali Necessari**
   - Algoritmo per determinare i materiali richiesti.

4. **Verifica Disponibilità Magazzino**
   - Controllo delle quantità disponibili in magazzino.
   - **Decisione:** Materiali sufficienti? 
     - **Sì:** Procedere.
     - **No:** Generare avviso per approvvigionamento.

5. **Aggiornamento Magazzino**
   - Riduzione delle quantità in base ai materiali assegnati al progetto.

6. **Calcolo Prezzi**
   - Calcolo del costo totale basato sui materiali utilizzati e sui prezzi unitari.

7. **Generazione Report**
   - Creazione di report per la pianificazione e l'ottimizzazione.

8. **Generazione Documenti di Carico**
   - Creazione automatica dei documenti di carico e trasporto.

9. **Fine**
   - Conclusione del processo.

