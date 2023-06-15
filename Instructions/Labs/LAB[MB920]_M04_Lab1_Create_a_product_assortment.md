---
lab:
  title: 'Lab 1: Creare un assortimento di prodotti'
  module: 'Module 4: Learn the Fundamentals of Microsoft Dynamics 365 Commerce'
---

# Modulo 4. Concetti fondamentali su Microsoft Dynamics 365 Commerce

## Lab 1: Creare un assortimento di prodotti

## Obiettivo

È necessario creare un assortimento di prodotti correlati assegnati a un canale di Commerce specifico che verrà reso disponibile in una data futura. 

## Configurazione del lab

   - **Tempo stimato**: 10 minuti

## Istruzioni

1.  Nella home page **Finance and Operations** ,in alto a destra, verificare di lavorare con l'azienda **USMF** . 

1.  Se necessario, selezionare la società e scegliere **USMF** dal menu. 

1.  Nel riquadro di spostamento a sinistra selezionare **Cataloghi e assortimenti** >  nel modulo **Retail and Commerce**.**** 

1.  Nella pagina **Assortimenti** selezionare **+ Nuovo**. 

1.  Nel modulo **Nuovo record** , se necessario, espandere la scheda **dettaglio Generale** . 

1.  Selezionare il campo **Data effettiva** e quindi selezionare una data in futuro.  

1.  Nel campo **Nome assortimento** immettere un nome per il nuovo assortimento. Ad esempio, usare `New Spring Season`

    > **Nota:** La **data di scadenza** può essere usata per disattivare automaticamente un assortimento pubblicato. 

1.  Espandere la scheda Dettagli **canali Commerce** . 

1.  Nella barra degli strumenti **Canali commerce** selezionare **+ Aggiungi riga**. 

1.  Nel riquadro **Scegli nodi organizzazione** selezionare **Negozi al dettaglio per tipo (Fabrikam)**.**** 

1.  Nell'elenco NODI ORGANIZZAZIONE DISPONIBILI selezionare Online e quindi selezionare l'icona Aggiungi ![Icona freccia DESTRA](./media/d365-fo-add-org-node-icon.png) per l'aggiunta in **NODI ORGANIZZAZIONE SELEZIONATI**.

    In questo modo verranno aggiunti il nodo padre e tutti i nodi figlio. 

1.  Aggiungere il nodo padre **Mall** e quindi selezionare **OK**. 

1.  Verificare che i due nodi siano stati aggiunti alla scheda **Dettaglio canali commerce** . 

1.  Espandere la scheda Dettagli **prodotti** . 

1.  Nella barra degli strumenti **Prodotti** selezionare **+Aggiungi riga**. 

1.  Per il campo **Categoria** espandere **Team Sports (Team Sports)** e quindi selezionare **OK**.

    In questo modo verranno aggiunti tutti gli articoli figlio della categoria padre.

1.  Esaminare l'ultima colonna denominata **Tipo di riga**. Per impostazione predefinita, verranno inclusi tutti gli articoli.

1.  Selezionare **+ Aggiungi riga**, selezionare il menu **Categoria**, espandere **Team Sports (Team Sports)** , selezionare **Baseball** e quindi selezionare **OK**. 

1.  Per escludere un elemento da una categoria di dimensioni maggiori già incluse, in questo caso Team Sports, nella colonna **Tipo linea** modificare il valore su `Exclude` 

1.  Usando la riga della categoria Baseball, selezionare il menu **Prodotti**. 

1.  Quando vengono definiti i prodotti di una categoria, è possibile selezionare un prodotto specifico da includere o escludere. Selezionare **AdultBaseballInfield** o immettere `0013` 

    > **Nota:** Per rimuovere un prodotto aggiunto, eliminare il contenuto del campo **Product** e quindi premere Tab o selezionare un'altra area della pagina. 

1.  Nel riquadro azioni selezionare **Salva** e selezionare **Pubblica**. 

1.  Selezionare **Sì** nella finestra di dialogo di conferma. L'assortimento di prodotti appena creato diventerà disponibile nella **data effettiva** selezionata. 

