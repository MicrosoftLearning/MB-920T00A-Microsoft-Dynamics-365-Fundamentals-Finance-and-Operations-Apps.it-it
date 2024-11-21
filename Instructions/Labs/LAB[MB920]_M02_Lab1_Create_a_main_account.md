---
lab:
  title: 'Lab 2.1: Creare un account principale'
  module: 'Learning Path 2: Learn the fundamentals of Microsoft Dynamics 365 Finance'
---

# Percorso di apprendimento 2: Concetti fondamentali di Microsoft Dynamics 365 Finance
# Modulo 2: Descrivere i ledgger generali

## Lab 2.1: Creare un account principale

## Configurazione del lab

   - **Tempo stimato:** 5 minuti

## Obiettivo

In questo lab verranno eseguite le attività seguenti:

1. Creare una persona giuridica.

2. Creare un calendario fiscale.

3. Creare un grafico di account.

4. Creare account principali nel grafico degli account.

5. Creare un'unità operativa di tipo reparto e centro di costo.

6. Creare una struttura di contabilità usando i principali conti e centri di costo.

7. Configurare il libro mastro.

# Passaggi del lab

## Creazione di una persona giuridica

1. Nel riquadro di spostamento sinistro di Dynamics 365 Finance selezionare **Moduli** ****&gt;** Amministrazione organizzazione **&gt;** Organizzazioni &gt; entità** legali.

2. Nella **pagina Entità** legali selezionare il **pulsante Nuovo** nel riquadro azioni per creare una nuova persona giuridica e immettere le informazioni seguenti:

    - Nome: **Contoso Demo Systems**

    - Società: **CDS**

    - Paese/area geografica: **Stati Uniti**

3. Selezionare **OK** nella parte inferiore.

## Creare un calendario fiscale

1. Nel riquadro di spostamento sinistro di Dynamics 365 Finance selezionare **Moduli&gt;******** Calendari contabili **&gt;** generali Calendari &gt;** fiscali. 

2. **Nella pagina Calendario fiscale selezionare il **pulsante Nuovo calendario**** nel riquadro azioni per creare un nuovo calendario fiscale e immettere le informazioni seguenti:

    - Calendario: **CDS**

    - Descrizione: **Calendario dei sistemi demo**

    - Inizio anno fiscale: **30/9/2024**

    - Fine anno fiscale: **10/1/2025**

    - Nome anno fiscale: **2024-25**

    - Lunghezza del periodo: **1**

    - Unità: **Mesi**

3. Selezionare il pulsante **Crea**.

Il sistema genererà 14 periodi, tra cui un'apertura e un periodo di chiusura e 12 periodi per 12 mesi.

## Creazione di un piano dei conti

1. Nel riquadro di spostamento sinistro di Dynamics 365 Finance selezionare **Modules**** > General ledger****&gt;**** Chart of accounts Chart of accounts Chart of accounts &gt; (Grafico contabilità generale degli account).** **&gt;**

2. **Nella pagina Grafico di account** selezionare il **pulsante Nuovo** nel riquadro azioni per creare un nuovo grafico di account e immettere le informazioni seguenti:

    - **Grafici degli account**: Sistemi demo

    - **Descrizione**: Sistemi demo Contoso

3. Selezionare il **pulsante Nuovo** nella **scheda dettaglio Account principali** per creare account principali con i valori seguenti:

    - Account principale: **1000**

    - Nome: **Cash**

    - Tipo di conto principale: **bilancio**

    - Categoria di conto principale: **CASH**

    - Valori dare/avere predefiniti: **Dare**

4. Creare un altro account principale:

    - Account principale: **3000**

    - Nome: **Ricavi**

    - Tipo di account principale: **Ricavi**

    - Categoria di account principale: **REV**

    - Db/CR default: **Credit**

5. Creare un altro account principale:

    - Account principale: **6000**

    - Nome: **Spese di viaggio**

    - Tipo di conto principale: **Spese**

    - Categoria di account principale: **EXP**

    - Valori dare/avere predefiniti: **Dare**

##  Creare un'unità operativa

1. Passare a **Moduli**** ****&gt;Amministrazione **&gt;** organizzazione Unità operative delle organizzazioni.&gt;**

2. Nel riquadro azioni selezionare il **pulsante Nuovo** seguito dal **tipo di unità operativa** Reparto e immettere il valore seguente:

    - Nome: **CDS_Training**

3. Nel riquadro azioni selezionare il **pulsante Nuovo** seguito dal **tipo di unità operativa** Centro di costo e immettere il valore seguente:

    - Nome: **CDS_Purchase**

4. Aggiungere altri due centri di costo: **CDS_IT** e **CDS_Admin**.

## Creare una struttura di contabilità

1. **Nella home page Finance and Operations** , in alto a destra, verificare di lavorare con la **società CDS**.

2. Se necessario, selezionare l'azienda e dal menu selezionare **CDS**.

3. Nel riquadro di spostamento sinistro di Dynamics 365 Finance selezionare **Moduli** > **Grafico mastro&gt;****** **generale degli account &gt; Strutture &gt; Configura strutture** account.

4. Nel riquadro azioni selezionare il **pulsante Nuovo** per creare una nuova struttura di account con i valori seguenti:

    - Struttura dell'account: **CDS_BS**

    - Descrizione: **Bilancio CDS**

    - Aggiungere l'account principale: **SÌ**

5. Selezionare il pulsante **Crea**.

6. **Nella scheda Dettaglio Segmenti e valori** consentiti selezionare il **pulsante Aggiungi** per aggiungere **l'intervallo account principale 1000...2999**.

7. Selezionare il **pulsante Attiva** nel riquadro azioni seguito dal **pulsante Attiva** nella finestra di dialogo di elaborazione batch.

8. Nel riquadro azioni della **pagina Strutture** account selezionare il **pulsante Nuovo** per creare un'altra struttura di account con i valori seguenti:

    - Struttura dell'account: **CDS_Revenue**

    - Descrizione: **Ricavi CDS**

    - Aggiungere l'account principale: **SÌ**

9. Selezionare il pulsante **Crea**.

10. **Nella scheda Dettaglio Segmenti e valori** consentiti selezionare il **pulsante Aggiungi** per aggiungere **l'intervallo di account principale 3000...5999**.

11. Selezionare il **pulsante Attiva** nel riquadro azioni seguito dal **pulsante Attiva** nella finestra di dialogo di elaborazione batch.

12. Nel riquadro azioni della **pagina Strutture** account selezionare il **pulsante Nuovo** per creare un'altra struttura di account con i valori seguenti:

    - Struttura dell'account: **CDS_Expense**

    - Descrizione: **Spese CDS**

    - Aggiungere l'account principale: **SÌ**

13. Selezionare il pulsante **Crea**.

14. **Nella scheda dettaglio Segmenti e valori** consentiti selezionare il **pulsante Aggiungi** per aggiungere **l'intervallo account principale 6000...9999**.

15. Selezionare il **pulsante Aggiungi segmento** nella **scheda dettaglio Segmenti e valori** consentiti

16. **Nella finestra di dialogo Aggiungi segmento** selezionare **CostCenter** e quindi il **pulsante Aggiungi segmento**.

17. **Nel campo CostCenter** immettere **253..255**. 

18. Selezionare il **pulsante Attiva** nel riquadro azioni seguito dal **pulsante Attiva** nella finestra di dialogo di elaborazione batch.

## Configurare la contabilità generale

1. **Nella home page Finance and Operations** , in alto a destra, verificare di lavorare con la **società CDS**.

2. Se necessario, selezionare l'azienda e dal menu selezionare **CDS**.

3. Nel riquadro di spostamento sinistro di Dynamics 365 Finance selezionare **Moduli**** > Generali contabilità &gt; pagina &gt;** e configurare quanto segue:

    - Grafico degli account: **Sistemi demo**

    - Calendario fiscale: **CDS**

    - Valuta contabile: **USD**

    - Valuta per la creazione di report: **USD**

    - Tipo di tasso di cambio valuta contabile: **predefinito**

    - Tipo di tasso di cambio del budget: **Budget**

4. **Nella scheda dettaglio Struttura** account selezionare il **pulsante Aggiungi** per aggiungere la struttura **dell'account CDS_BS**.

> Se obbligatorio, selezionare **Sì** per Aggiunta di una struttura di account.

5. Aggiungere altre due strutture di account: **CDS_Revenue** e **CDS_Expense**.

Questa operazione completa la configurazione di base del modulo Contabilità generale. È ora possibile pianificare la configurazione del journal per pubblicare i journal. 

 
