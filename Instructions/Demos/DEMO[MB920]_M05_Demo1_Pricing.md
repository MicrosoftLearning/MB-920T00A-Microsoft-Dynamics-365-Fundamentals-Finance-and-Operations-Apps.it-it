---
demo:
  title: 'Demo 1: Determinazione dei prezzi in Project Operations'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## Demo 1: Determinazione dei prezzi in Project Operations

1. Passare all'area di lavoro **Gestione progetti**.  
    In questa demo, verranno configurati i prezzi delle vendite e dei costi all'interno di Project Operations. E vedremo come i costi e i prezzi vengono derivati da una fattura registrata in precedenza.

1. Nella selezione della società in alto a destra, verificare che la persona giuridica alla quale si è connessi sia **USSI**.  
    In caso contrario, modificare l'organizzazione in **USSI**.

1. Nella tabella **Progetti attivi**, selezionare il progetto **00000093 Contoso Consulting**. Verrà visualizzata la vista dei dettagli del progetto.

    ![Screenshot dell'area di lavoro della gestione dei progetti con Contoso Consulting evidenziato nella tabella dei progetti attivi.](./media/projops_prices_1_selecting_contoso_consulting.png)

1. Nella pagina **Contoso Consulting**, selezionare la scheda **Gestisci** nella barra di spostamento.

1. Nel menu **Gestisci**, selezionare **Giornali di registrazione fatture**.  
    Qui è stata individuata una fattura in cui sono state applicate le ore.

1. In **Transazioni fattura**, nella colonna **Prezzo di vendita**, scegliere **350,00**.  
    In questa vista è possibile notare che il prezzo di vendita della risorsa Aaron Con, project manager di USSI, ha un costo di 350 dollari. Adesso verrà esaminata l'impostazione dei prezzi per vedere come è stata determinata la tariffa.

    ![Screenshot di un giornale di registrazione fatture con il valore 350 evidenziato nella colonna del prezzo di vendita.](./media/projops_prices_2_point_to_350.png)  

    Anche se è possibile esaminare i prezzi dal singolo progetto, si inizierà dall'area di lavoro **Gestione progetti** in modo da poter vedere tutti i prezzi impostati.

1. Passare all'area di lavoro **Gestione progetti**.

1. Sul lato destro della schermata, nella sezione **Collegamenti**, nel sottomenu **Configurazione**, selezionare **Prezzo di vendita (ora)**.

1. Nella pagina **Prezzo di vendita: ora**, nella colonna **Prezzi** della tabella, scegliere **350,00**.  
Da questa vista, è possibile vedere dove è stato impostato il prezzo di vendita di 350 dollari di Aaron Con.

1. Scegliere l'intera prima riga.  
    Se si osserva l'intera riga, è possibile notare che Aaron è impostato come Project Manager e, più precisamente, che la tariffa è associata a un ID progetto specifico per Contoso Consulting.

1. Nella colonna **Risorsa**, scegliere tutte le altre righe con risorse assegnate.  
    In questa tabella, è possibile vedere che ci sono anche altri Project Manager, ma non sono assegnati in modo specifico agli ID del progetto e quindi le loro tariffe riguardano solo la categoria e le risorse assegnate.

    ![Screenshot della pagina Prezzo di vendita: ora con tutte le righe con risorse assegnate evidenziate nella tabella.](./media/projops_prices_3_resources_table.png)  

    Questa matrice è sufficientemente flessibile da supportare il livello di dettaglio osservato con Contoso Consulting e Aaron Con, oltre a supportare un modello di prezzo più generico, come il prezzo di 300 dollari mostrato qui.

1. Per Il progetto Contoso, passare alla pagina **Giornali di registrazione fatture**.  
    Ritornando alla fattura registrata, verrà esaminata la stessa transazione delle ore registrate e i costi associati ad Aaron Con selezionando l'ID della transazione sulla riga della transazione della fattura.

1. Nella sezione **Transazioni fatture**, selezionare la scheda **Ora**. Nella tabella visualizzata, nella colonna **ID transazione**, selezionare un ID transazione.

    ![Screenshot della pagina del giornale di registrazione fatture con la colonna ID transazione evidenziata.](./media/projops_prices_4_select_a_transaction_id.png)

1. Nella pagina **Transazioni orarie**, selezionare la scheda **Panoramica**. Nella tabella visualizzata, nella colonna **Prezzo di costo**, scegliere **200,00**.  
    Dalla vista delle transazioni orarie, è possibile visualizzare la voce relativa ad Aaron Con e il prezzo di costo associato di 200 dollari. Torniamo indietro ed esaminiamo l'impostazione del prezzo di costo per vedere come è stata ricavata la tariffa di costo.

1. Passare all'area di lavoro **Gestione progetti**.

1. Sul lato destro della schermata, nella sezione **Collegamenti**, nel sottomenu **Configurazione**, selezionare **Prezzo di costo (ora)**.

1. Nella pagina **Vista standard Prezzo di costo: ora**, nella tabella, scegliere la riga con il valore **01/01/2014** nella colonna **Data effettiva**, **PM** nella colonna **Categoria**, **200,00** nella colonna **Prezzo di costo** e nessun valore nelle altre colonne.  
    Da questa vista, è possibile visualizzare un prezzo di costo di 200 dollari che è stato impostato specificamente per la categoria di PM, ma non ci sono altre righe specifiche per Aaron o per il progetto Contoso Consulting. Anche questa è una pratica comune, poiché molte organizzazioni di servizi applicano tariffe di costo standard per tutte le categorie, in questo caso identificate come ruolo di progetto. Questo costo è spesso un tasso combinato in cui la tariffa di retribuzione della singola risorsa sarà memorizzato solo all'interno del sistema di retribuzioni o delle risorse umane. Il tasso di costo standard verrà poi adeguato periodicamente, man mano che i costi delle retribuzioni vengono analizzati per garantire la precisione e il rispetto dei margini.

    ![Screenshot della tabella dei prezzi di costo: ora con la riga evidenziata relativa ai prezzi PM.](./media/projops_prices_5_cost_price_hour_table.png)

1. Passare all'area di lavoro **Gestione progetti**.

1. Sul lato destro della schermata, nella sezione **Collegamenti**, nel sottomenu **Imposta**, scegliere **Prezzo di costo (ora)** e **Prezzo di vendita (ora)**.  

In questa demo è stato illustrato come vengono configurati i prezzi standard delle vendite e dei costi in Project Operations. Abbiamo esaminato il relativo impatto rispetto a una fattura registrata per ottenere informazioni su come la configurazione di questi prezzi influisce direttamente sul tempo e sulla fattura materiale presentata.
