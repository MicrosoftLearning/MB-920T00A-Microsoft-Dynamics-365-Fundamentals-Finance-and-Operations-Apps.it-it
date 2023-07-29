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

1.  Nella home page Finance and Operations selezionare il menu **Hamburger del riquadro di spostamento** in alto a sinistra.

2.  Nel pannello di navigazione selezionare **Vendita al dettaglio e commercio** > **Cataloghi e assortimenti** > **Assortimenti**.

3.  Attendere il caricamento della pagina.

4.  Nella pagina **Assortments (Assortimenti** ) selezionare **+ New (+ Nuovo**).

5.  Nel riquadro **Nuovo record** espandere **Generale**.

6.  Selezionare la casella **Data di validità** e quindi selezionare una data futura.

7.  Nella casella **Nome assortimento** immettere un nome per il nuovo assortimento. Ad esempio, **New Spring Season**.

8.  Impostare **Data di scadenza** su **Mai**.

    La data di scadenza può essere usata per disattivare automaticamente un assortimento pubblicato.

9.  Espandere **Commerce channels** (Canali di Commerce).

10. Nel menu **Canali commerciali** selezionare **+ Aggiungi riga**.

11. In **Scegli nodi dell'organizzazione** selezionare il menu **Gerarchia organizzazione** e quindi selezionare **Punti vendita al dettaglio per tipo (Fabrikam)**.

12. Nell'elenco **NODI ORGANIZZAZIONE DISPONIBILI** selezionare **Online** e quindi selezionare l'icona **Aggiungi** ![immagine 15](./media/04-learn-the-fundamentals-of-dynamics-365-commerce-17.png) per aggiungerla ai **NODI ORGANIZZAZIONE SELEZIONATI**.

    Viene aggiunto al nodo padre e a tutti i nodi figlio.

13. Aggiungere il nodo padre **Mall** e quindi selezionare **OK**.

14. Verificare che siano stati aggiunti due nodi ai canali di Commerce.

15. Espandere **Prodotti**.

16. Scegliere **+ Aggiungi riga** dal menu **Prodotti**.

17. Selezionare il menu **Categoria** , selezionare **Sport di squadra (Sport di squadra)** e quindi selezionare **OK**.

    In questo modo vengono aggiunti tutti gli elementi figlio della categoria padre.

18. Esaminare l'ultima colonna denominata **Tipo di riga**. Per impostazione predefinita, vengono inclusi tutti gli elementi.

19. Selezionare **+ Aggiungi riga**, selezionare il menu **Categoria**, espandere **Team Sports (Team Sports)** , selezionare **Baseball** e quindi selezionare **OK**.

20. Per escludere un elemento da una categoria più grande già inclusa, in questo caso **Team Sports**, nella colonna **Tipo di linea** modificare il valore in **Escludi**.

21. Usando la riga **Categoria Baseball** , selezionare il menu **Prodotti** .

22. Quando vengono definiti i prodotti di una categoria, è possibile selezionare un prodotto specifico da includere o escludere. Selezionare **AdultBaseballInfield**.

23. Per rimuovere un prodotto aggiunto, eliminare il contenuto della casella del prodotto e quindi premere **TAB** sulla tastiera o selezionare un'altra area della pagina.

24. Nel menu in alto selezionare **Salva**.

25. Nel menu in alto selezionare **Pubblica**.

26. Esaminare le informazioni nella finestra di dialogo e quindi selezionare **Sì**.

    L'assortimento di prodotti appena creato diventa disponibile alla data di validità.

