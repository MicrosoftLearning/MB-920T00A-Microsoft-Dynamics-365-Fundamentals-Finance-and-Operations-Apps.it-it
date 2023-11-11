---
demo:
  title: 'Demo 2: Creare una fattura'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## Demo 2 - Creare una fattura

1. Passare all'area di lavoro  **Gestione progetti**.  
    In questa demo si esaminerà il processo di fatturazione di un singolo progetto all'interno delle operazioni del progetto. Benché sia possibile eseguire una fatturazione collettiva, a scopo dimostrativo qui ci si concentrerà su un singolo progetto di tempistica e materiali.Si osserveranno anche i risultati di registrazione e le informazioni finanziarie dettagliate all'interno del rendiconto del progetto. Iniziamo con la fatturazione del progetto. 

1. Nella selezione della società in alto a destra verificare che la persona giuridica cui si è connessi sia  **USSI**. In caso contrario, impostare la persona giuridica su  **USSI**.  
    Nell'area di lavoro  **Gestione progetti** è possibile visualizzare tutti i progetti attivi.È possibile cercare progetti usando il filtro o, come in questo esempio, selezionare un ID progetto noto. 

1. Nella tabella **Progetti attivi** nella colonna **ID progetto** selezionare **00000093 Contoso Consulting**.  

1. Aprire quindi la pagina **Proposte di fatturazione progetto** per visualizzare tutte le fatture precedenti elaborate per Contoso Consulting. 

1. Nel riquadro azioni, nella scheda **FATTURA**  selezionare **Proposte di fatturazione progetto**. 

1. Nella pagina **Proposte di fatturazione progetto** , nella barra di spostamento selezionare **Nuovo** e quindi **Proposta di fatturazione**.  
    Poiché questa è una semplice fattura di tempistica e materiali, non è necessario selezionare l'opzione Proposta di fatturazione da regola di fatturazione. 

    ![Screenshot della pagina delle proposte di fattura del progetto con la nuova proposta di fattura evidenziata.](./media/projops_invoice_1_new_invoice_proposal.png)

1. Nel riquadro **Crea proposta di fatturazione ** posizionare il puntatore sulle caselle in **Seleziona transazioni**.  
    Da qui è possibile selezionare elementi come il metodo di fatturazione, la data della fattura, la fonte di finanziamento e il progetto.È anche possibile scegliere di includere sottoprogetti, nonché di incorporare tipi di transazione, le date di inizio e di fine per le transazioni e qualsiasi dimensione finanziaria necessaria. 

    ![Screenshot del riquadro Crea proposta di fattura con la sezione seleziona transazioni evidenziata.](./media/projops_invoice_2_select_transactions.png)

1. Nel menu a discesa **Progetto** selezionare **00000093 Contoso Consulting**. 

1. Per questo esempio, assicurarsi che la **data della fattura** sia impostata su **2/1/21**, la **data di inizio** sia impostata su **2/1/21** e la data di fine sia la data odierna.  
    Dopo aver effettuato le selezioni, selezionare il pulsante di ricerca per trovare le transazioni che soddisfano tali parametri.

1. Selezionare **Cerca**.  
    Selezionare quindi l'opzione Seleziona tutto per fatturare tutte le transazioni. Verranno selezionati gli elementi scelti per spese e ore.

1. Nella scheda **Transazioni progetto** selezionare  **Seleziona tutto**.

1. Selezionare **OK**. 

1. Nella pagina **Proposta di fatturazione**  posizionare il puntatore sulla colonna **Importo riga fattura** .  
    Qui è possibile visualizzare l'importo e il riepilogo della fattura, le transazioni orarie e le spese.

    ![Screenshot della pagina della proposta di fattura con la colonna importo della riga della fattura evidenziata.](./media/projops_invoice_3_invoice_line_amount_column.png)

1. Posizionare il puntatore sulla scheda  **Ora**. 

1. Posizionare il puntatore sulla scheda **Spese**.  
    È anche possibile cambiare e esaminare la transazione di spesa.  
A questo punto, controllare il pulsante totali per vedere l'aspetto della fattura sia dal punto di vista dei costi che dei ricavi.

1. Nella barra di spostamento selezionare **Totali**.

1. Nella pagina **Totali** posizionare il puntatore sulla colonna **CONTABILITÀ GENERALE**, sulla colonna **CLIENTE** e sulla colonna **Sconto riga**.  
    Nella schermata dei totali è possibile vedere quale sarà l'impatto sul libro mastro generale, tutte le informazioni sui clienti, ad esempio limiti di credito, eventuali sconti, imposte sulle vendite e l'impatto netto della fattura. 

1. Sul lato destro della schermata selezionare la **X** per chiudere la pagina.  
    È ora possibile creare un'anteprima di stampa per garantire che tutte le informazioni di fatturazione siano accurate. Alcune organizzazioni usano l'anteprima durante le riunioni di revisione dei progetti per assicurarsi che tutti concordino sui totali prima che la fattura venga finalizza. 

1. Nella pagina **Proposta di fatturazione** selezionare **Anteprima di stampa** sulla barra di spostamento. 

1. Nella finestra di dialogo selezionare **Anteprima di stampa**.  
    Qui è possibile visualizzare un esempio dell'anteprima di stampa per una fattura proforma. 

1. Selezionare la **X** per chiudere la pagina.  
    Dopo aver convalidato tutte le informazioni e aver soddisfatto l'anteprima stampa della fattura, è possibile pubblicare la proposta di fattura.

1. Sulla barra di spostamento selezionare **Registra**.

1. Selezionare la scheda  **Parametri**.

1. In **PARAMETRO** impostare **Registrazione** su **Sì**.

1. In **OPZIONI DI STAMPA** impostare **Stampa fattura** su **Sì**.

1. Selezionare **OK**.

1. Nella pagina **Fattura** posizionare il puntatore sul numero di **fattura**.  
    Ora è disponibile un numero di fattura generato.  
    Una volta registrata la fattura, è possibile esaminare le informazioni nel giornale di registrazione fatture ed eseguire il drill-down delle transazioni del libro mastro.

1. Passare all'area di lavoro  **Gestione progetti**.

1. Nella tabella **Progetti attivi** selezionare progetto **00000093** **Contoso consulting**.

1. Nel riquadro azioni selezionare **Giornali di registrazione fatture** nella scheda **FATTURA**.

1. Nella barra delle azioni della pagina **Giornale di registrazione fatture** selezionare **Giustificativo**.

1. Nella pagina **Transazioni giustificativo** posizionare il puntatore del mouse sulla colonna  **Conto CoGe**.  
    Qui è possibile visualizzare i risultati registrati nella contabilità generale. I conti CoGe sono determinati dall'impostazione dei conti e dalle dimensioni finanziarie applicate a ogni progetto.

1. Passare all'area di lavoro  **Gestione progetti**. 

1. Nella tabella **Progetti attivi**  selezionare il **progetto 00000093 Contoso Consulting**.

1. Nella barra di spostamento della pagina **Contoso Consulting**  selezionare **Controllo**.  
    Qui è possibile visualizzare tutti i dettagli del progetto.  
    Esaminiamo quindi i dati finanziari del progetto in un rendiconto di progetto.

1. Selezionare **Rendiconti progetto**.

1. Nella pagina **Rendiconti progetto** posizionare il puntatore del mouse sulla sezione **DATA PROGETTO** .  
È possibile creare un'istruzione per qualsiasi intervallo di date desiderato.

1. Selezionare la casella **Data iniziale** e immettere **1/2/2021**.
1. 
1. Selezionare la casella **Data finale** e immettere la data odierna.

1. Al termine, selezionare **Calcola**.

    ![Screenshot della pagina delle istruzioni del progetto con l'opzione calculate evidenziata.](./media/projops_invoice_4_calculate.png)

1. Posizionare il puntatore del mouse su **Transazioni**.  
    Dopo aver aggiornato i dati, un manager di progetto può scegliere di eseguire ulteriormente il drill-down nei dettagli delle transazioni per prendere decisioni sul progetto o apportare le modifiche necessarie.In questa dimostrazione è stata elaborata una fattura di tempo e materiale con transazioni orarie e spese. L'abbiamo esaminata in anteprima, quindi abbiamo pubblicato la fattura, esaminato il libro mastro e infine esaminato l'impatto finanziario tramite questo rendiconto di progetto.
