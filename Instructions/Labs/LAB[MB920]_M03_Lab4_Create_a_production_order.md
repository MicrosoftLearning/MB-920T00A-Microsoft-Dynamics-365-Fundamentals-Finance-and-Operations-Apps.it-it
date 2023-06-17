---
lab:
  title: 'Lab 4: Creare un ordine di produzione'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Modulo 3: Concetti fondamentali su Microsoft Dynamics 365 Supply Chain Management

## Lab 4: Creare un ordine di produzione

## Obiettivo

L'ordine di produzione contiene informazioni su ciò che verrà prodotto, sulla quantità da produrre e sulla data di fine pianificata. Contiene inoltre informazioni sui materiali da usare e sul processo da seguire per la produzione dell'articolo.

È necessario creare un nuovo ordine di produzione per la società.

## Configurazione del lab

   - **Tempo stimato**: 5 minuti

## Istruzioni

1.  Nella home page **Finance and Operations** , in alto a destra, verificare di lavorare con la società **USMF** . 

1.  Se necessario, selezionare la società e scegliere **USMF** dal menu. 

1.  Nel riquadro di spostamento sinistro, nel modulo **Controllo produzione** selezionare **Ordini** >  di**produzione Tutti gli ordini di produzione**. 

1.  Nel riquadro azioni selezionare **Nuovo ordine di produzione**. 

1.  In **IDENTIFICAZIONE** immettere e selezionare l'elemento **MidRangeSpeaker** nel campo `D0001` **Numero** elemento. 

1.  In **PRODUZIONE**, nel campo **Consegna** selezionare una data di un mese dalla data odierna. 
   
    > **Nota:** La data **di** consegna indica quando l'ordine di produzione deve terminare per consegnare in tempo. Questa data può essere usata nel processo di pianificazione.  Ad esempio, è possibile pianificare l'ordine a ritroso dalla data di consegna. 

1.  Nel campo **Quantità** immettere `20.00` 

    > **Nota:** In **BOM/ROUTE**, il campo **Numero DBA** visualizza automaticamente il numero di qualsiasi BOM attivo per l'articolo corrente, ma è possibile modificare la distinta base per questo ordine di produzione selezionando un BOM attivo dall'elenco delle versioni DBA approvate. Il campo **Numero** di route visualizza automaticamente il numero di route attive per l'elemento corrente, ma è possibile modificare la route per questo ordine di produzione selezionando una route attiva dall'elenco delle versioni di route approvate. 

    ![Schermata che mostra il riquadro Crea ordine di produzione completo](./media/lp1-m4-new-production-order-pane.png)

1.  Selezionare **Crea**. 

1.  **Chiudere** la pagina e tornare alla home page. 

