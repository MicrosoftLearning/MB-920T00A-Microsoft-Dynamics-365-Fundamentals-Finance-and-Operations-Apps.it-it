---
lab:
  title: 'Lab 2: Integrazione di Excel'
  module: 'Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps'
---

# Modulo 1. Esplorare le funzionalità principali delle app per la finanza e le operazioni di Dynamics 365

## Lab 2: Integrazione di Excel

## Obiettivo

In questo lab si apprenderà come copiare i dati dalle operazioni e dalle finanze a Excel usando il componente aggiuntivo office di Dynamics Data Connector. Si apprenderà anche come è possibile usare la stessa app per inserire i dati in Dynamics 365 Finance e operazioni. 

## Configurazione del lab

   - **Tempo stimato**: 5 minuti

## Istruzioni

Ora che è stata acquisita familiarità con le app per la finanza e le operazioni, dedicare del tempo a esplorare lo scenario di integrazione di Excel. 

1.  Nella home page **Finance and Operations** ,in alto a destra, verificare di lavorare con l'azienda **USMF** . 

2.  Passare ad **Approvvigionamento** > **Imposta** > **Fornitori** > **Gruppi di fornitori**.

3.  Nel riquadro azioni selezionare **Apri in Microsoft Office e in Apri in** **Excel** selezionare **Gruppi fornitore (usmf).**

4.  Nel riquadro **Apri in Excel** selezionare **Scarica**. 

5.  Il file modello di Excel verrà scaricato e salvato. **Aprire** il file modello di Excel scaricato, ignorare o consentire altre richieste di sicurezza standard, se necessario, chiudere l'attivazione e selezionare **Abilita modifica**. Selezionare **Attendibilità di questo componente aggiuntivo** e quindi accedere (usando le stesse credenziali, se richiesto). 

    Una volta eseguito l'accesso, l'app Data Connector aggiorna i dati esistenti dalla tabella **Gruppo fornitore** e viene visualizzato nel foglio di calcolo di Excel. 

6.  Per creare un nuovo record, immettere `100` nel campo **Gruppo fornitore** , `Insurance vendor` nel campo **Descrizione** e `Net10` nel campo **Condizioni di pagamento** . 

7.  Selezionare il pulsante **Pubblica** nel riquadro attività Microsoft Dynamics Data Connector. 

8.  Aggiornare l'elenco **Gruppi di fornitori** in Dynamics 365 Finance e operazioni per verificare che il nuovo record sia stato aggiunto correttamente. 

