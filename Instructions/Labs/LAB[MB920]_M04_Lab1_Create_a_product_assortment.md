---
lab:
  title: 'Lab 1: Creare un assortimento di prodotti'
  module: 'Module 4: Learn the Fundamentals of Microsoft Dynamics 365 Commerce'
---

# Modulo 4: imparare i concetti fondamentali di Microsoft Dynamics 365 Commerce

## Lab 1: Creare un assortimento di prodotti

## Obiettivo

È necessario creare un assortimento di prodotti correlati assegnati a uno specifico canale di commercio che sarà reso disponibile in una data futura. 

## Configurazione del lab

   - **Tempo stimato:** 10 minuti

## Istruzioni

1.  Nella home page delle app per la finanza e le operazioni, in alto a sinistra selezionare il menu a forma di hamburger **Espande il riquadro di spostamento**.

2.  Nel riquadro di spostamento selezionare **Vendita al dettaglio e commercio** > **Cataloghi e assortimenti** > **Assortimenti**.

3.  Attendere il caricamento della pagina.

4.  Nella pagina **Assortimenti** selezionare **+ Nuovo**.

5.  Nel riquadro **Nuovo record** espandere **Generale**.

6.  Selezionare la casella **Data di validità** e quindi scegliere una data futura.

7.  Nella casella **Nome assortimento** immettere un nome per il nuovo assortimento. Ad esempio, **Nuova stagione primaverile**.

8.  Impostare la **Data di scadenza** su **Mai**.

    La data di scadenza consente di disattivare automaticamente un assortimento pubblicato.

9.  Espandere **Canali Commerce**.

10. Nel menu **Canali Commerce** selezionare **+ Aggiungi riga**.

11. In **Scegli nodi organizzazione** selezionare il menu **Gerarchia organizzativa** e quindi **Punti vendita al dettaglio per tipo (Fabrikam)**.

12. Nell'elenco **NODI ORGANIZZAZIONE DISPONIBILI**, selezionare **Online** e quindi selezionare l'icona **Aggiungi**![Immagine 15](./media/04-learn-the-fundamentals-of-dynamics-365-commerce-17.png) per l'aggiunta in **NODI ORGANIZZAZIONE SELEZIONATI**.

    In questo modo si aggiungono il nodo padre e tutti i nodi figlio.

13. Aggiungere il nodo padre **Centro commerciale** e scegliere **OK**.

14. Verificare che i due nodi siano stati aggiunti ai canali Commerce.

15. Espandere **Prodotti**.

16. Nel menu **Prodotti** selezionare **+ Aggiungi riga**.

17. Selezionare il menu **Categoria**, quindi **Sport di squadra (Sport di squadra)** e scegliere **OK**.

    Ciò aggiunge tutti gli elementi figlio della categoria padre.

18. Esaminare l'ultima colonna denominata **Tipo riga**. Per impostazione predefinita sono inclusi tutti gli elementi.

19. Selezionare **+ Aggiungi riga**, scegliere il menu **Categoria**, espandere **Sport di squadra (Sport di squadra)**, selezionare **Baseball** e quindi fare clic su **OK**.

20. Per escludere un elemento da una categoria più ampia già inclusa, in questo caso **Sport di squadra**, nella colonna **Tipo riga** modificare il valore in **Escludi**.

21. Dalla riga della categoria **Baseball** selezionare il menu **Prodotti**.

22. Quando vengono definiti i prodotti appartenenti a una categoria, è possibile selezionare un prodotto specifico da includere o escludere. Selezionare **AdultBaseballInfield**.

23. Per rimuovere un prodotto aggiunto, eliminare il contenuto della casella di prodotti e quindi premere il tasto **TAB** sulla tastiera oppure selezionare un'altra area della pagina.

24. Selezionare **Salva** nel menu in alto.

25. Selezionare **Pubblica** nel menu in alto.

26. Controllare le informazioni presenti nella finestra di dialogo, quindi scegliere **Sì**.

    L'assortimento di prodotti appena creato diventa disponibile dalla data di validità.

