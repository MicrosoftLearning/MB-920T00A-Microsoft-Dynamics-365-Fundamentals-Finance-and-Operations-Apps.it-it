---
demo:
  title: 'Demo 1: Prezzi di Project Operations'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## Demo 1 - Prezzi di Project Operations

1. Passare all'area **di lavoro Gestione** progetti.  
    In questa demo verranno configurati i prezzi delle vendite e dei costi all'interno delle operazioni di progetto. E vedremo come i costi e i prezzi derivano da una fattura registrata in precedenza.

1. Nella selezione dell'azienda in alto a destra verificare che la persona giuridica a cui si è connessi sia **USSI**.  
    In caso contrario, modificare l'organizzazione in **USSI**.

1. Nella **tabella Progetti** attivi selezionare progetto **00000093 Contoso Consulting**. Verrà visualizzata la visualizzazione dei dettagli del progetto.

    ![Screenshot dell'area di lavoro di gestione dei progetti con Contoso Consulting evidenziata nella tabella Progetti attivi.](./media/projops_prices_1_selecting_contoso_consulting.png)

1. Nella barra di spostamento della **pagina Contoso Consulting** selezionare la **scheda Gestisci** .

1. **Nel menu Gestisci** selezionare **Registrazioni** fatture.  
    Qui è stata individuata una fattura in cui sono state applicate le ore.

1. Nella **colonna Sales price** (** Transazioni** fattura) fare riferimento a **350,00**.  
    Possiamo vedere in questa vista che il prezzo di vendita per la risorsa Aaron Con, un project Manager per USSI, ha una tariffa di addebito di 350 dollari. Si esaminerà ora la configurazione dei prezzi per vedere come è stata determinata tale tariffa.

    ![Screenshot di un giornale di registrazione fatture con il valore 350 evidenziato nella colonna prezzo di vendita.](./media/projops_prices_2_point_to_350.png)  

    Anche se è possibile esaminare i prezzi del singolo progetto, si inizierà dall'area **di lavoro Gestione** progetti in modo da poter visualizzare tutti i prezzi configurati.

1. Passare all'area **di lavoro Gestione** progetti.

1. Sul lato destro della schermata, nella sezione Collegamenti **, nel **sottomenu Setup (Setup**), selezionare **Sales price (hour)**.**

1. Nella **pagina Sales price – hour (Prezzo vendite - ora** ) nella **colonna Pricing (Prezzi** ) della tabella fare riferimento a **350,00**.  
Da questa vista, possiamo vedere dove è stato impostato il prezzo di vendita di Aaron Con di 350 dollari.

1. Puntare all'intera prima riga.  
    Se si esamina l'intera riga, è possibile notare che Aaron è configurato come Project Manager e, in particolare, che la frequenza è associata a un ID di progetto specifico per Contoso Consulting.

1. **Nella colonna Risorsa** puntare a tutte le altre righe con risorse assegnate.  
    In questa tabella è possibile osservare che sono stati configurati anche altri project manager, ma non vengono allocati in modo specifico agli ID progetto e pertanto le loro tariffe sono specifiche solo per la categoria e le risorse assegnate.

    ![Screenshot della pagina sales price - hour con tutte le righe con le risorse assegnate evidenziate nella tabella.](./media/projops_prices_3_resources_table.png)  

    Questa matrice è abbastanza flessibile per supportare il livello di dettaglio visto con Contoso Consulting e Aaron Con, oltre a supportare un modello di prezzi più generico, ad esempio il prezzo di $ 300 mostrato qui.

1. Per Il progetto Contoso passare alla **pagina Registrazioni** fatture.  
    Tornando alla fattura registrata, esamineremo la stessa transazione delle ore registrate e esamineremo i costi associati a Aaron Con selezionando l'ID transazione nella riga della transazione di fattura.

1. **Nella sezione Transazioni** fatture selezionare la **scheda Ora**. Nella tabella visualizzata, nella **colonna ID** transazione, selezionare un ID transazione.

    ![Screenshot della pagina journal della fattura con la colonna ID transazione evidenziata.](./media/projops_prices_4_select_a_transaction_id.png)

1. Nella **pagina Transazioni** orarie selezionare la **scheda Panoramica** . Nella tabella visualizzata, nella **colonna Costo prezzo** , puntare a **200,00**.  
    Dalla visualizzazione delle transazioni orarie, è possibile vedere la voce per Aaron Con e c'è il prezzo di costo associato di $ 200. Torniamo indietro e esaminiamo la configurazione dei prezzi dei costi per vedere come è stata derivata tale tariffa di costo.

1. Passare all'area **di lavoro Gestione** progetti.

1. Sul lato destro della schermata, nella **sezione Collegamenti** , nel **sottomenu Configura** selezionare **Prezzo costo (ora)**.

1. **Nella pagina Cost price – hour Standard view** ,nella tabella fare riferimento alla riga con **1/1/2014** nella **colonna Data** effettiva, **PM** nella **colonna Categoria**, **200,00** nella **colonna Prezzo di costo** e nessun valore nelle altre colonne.  
    Da questa vista è possibile vedere un prezzo di costo di $ 200 che è stato configurato specificamente per la categoria di PM, ma non ci sono altre righe specifiche per Aaron o il nostro progetto di consulenza Contoso. Anche questa è una pratica comune poiché molte organizzazioni di servizi applicano tariffe di costo standard tra le categorie, in questo caso identificate qui come ruolo di progetto. Questo costo è spesso una tariffa combinata in cui la tariffa di pagamento delle singole risorse verrà archiviata solo all'interno del sistema di retribuzioni o risorse umane. La tariffa di costo standard verrà quindi rettificata periodicamente, in quanto i costi delle retribuzioni vengono analizzati per garantire che siano accurati e vengano soddisfatti i margini.

    ![Screenshot della tabella cost price - hour con la riga relativa ai prezzi pm evidenziata.](./media/projops_prices_5_cost_price_hour_table.png)

1. Passare all'area **di lavoro Gestione** progetti.

1. Sul lato destro della schermata, nella **sezione Collegamenti** , nel **sottomenu Imposta** , scegliere **Prezzo costo (ora)** e **Prezzo vendite (ora)**.  

In questa dimostrazione è stato illustrato come vengono configurati i prezzi standard delle vendite e dei costi in Project Operations. Abbiamo esaminato il loro impatto rispetto a una fattura registrata per ottenere informazioni su come la configurazione di questi prezzi influisce direttamente sul tempo e sulla fattura materiale presentata.
