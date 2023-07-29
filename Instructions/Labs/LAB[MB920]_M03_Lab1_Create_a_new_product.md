---
lab:
  title: 'Lab 1: Creare un nuovo prodotto'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Modulo 3: Concetti fondamentali su Microsoft Dynamics 365 Supply Chain Management

## Lab 1: Creare un nuovo prodotto

## Obiettivo

In Contoso Entertainment System USA (USMF), si prevede di acquistare una nuova configurazione di un armadio da un fornitore.  È necessario creare un articolo per rappresentare la nuova configurazione.  In questo lab si apprenderà come creare un nuovo elemento e le configurazioni degli elementi.

## Configurazione del lab

   - **Tempo stimato**: 10 minuti

## Istruzioni

In Contoso Entertainment System USA (USMF), si prevede di acquistare una nuova configurazione di un armadio da un fornitore.  È necessario creare un articolo per rappresentare la nuova configurazione. 

1.  Nella home page Finance and Operations ,in alto a destra, verificare di lavorare con l'azienda **USMF** . Se necessario, nell'elenco a discesa dell'azienda selezionare **USMF**.

2.  In alto a sinistra selezionare **il menu Espandi il menu hamburger del riquadro di spostamento** .

3.  Nel riquadro di spostamento selezionare **Moduli** e quindi selezionare **Gestione informazioni sul prodotto**. Quindi nel menu **Prodotti** selezionare **Prodotti**.

4.  Nella pagina **Prodotti** selezionare **+ Nuovo** nel menu in alto.

5.  Nella pagina **Nuovo prodotto** , nel campo **Tipo di** prodotto verificare che **l'elemento** sia selezionato.

6.  Nel campo **Sottotipo Prodotto** verificare che **Product** sia selezionato.

7.  In **IDENTIFICAZIONE** immettere **GTL007** nella casella **Numero prodotto**.

8.  Nella casella **Nome prodotto** immettere **Cabinet 2**.

    ![Screenshot che illustra la visualizzazione standard della nuova pagina di creazione del prodotto.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-07.png)

9.  Selezionare il pulsante **OK**.

10. Nel menu **Prodotto** nel riquadro azioni selezionare Gruppi di **dimensioni** nel gruppo **Configura** .

    ![Screenshot che illustra l'opzione di configurazione nel menu prodotto in cui è possibile aggiungere i diversi dettagli del gruppo di dimensioni.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-08.png)

11. Selezionare l'elenco a discesa **Gruppo di dimensioni di archiviazione** e selezionare **SiteWH**.

12. Selezionare l'elenco a discesa **Gruppo di dimensioni di rilevamento** e selezionare **Nessuna**.

13. Selezionare il pulsante **OK**.

14. Selezionare il pulsante **Rilascia prodotti** nel riquadro azioni per rilasciare il prodotto in un'entità legale.

15. Verrà visualizzata una pagina che visualizza il primo passaggio come **Seleziona prodotti da rilasciare.**

    ![Screenshot che illustra la visualizzazione standard della pagina dei prodotti di rilascio.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-09.png)

16. Selezionare il pulsante **Avanti** nella parte inferiore della pagina

17. Nella pagina **Seleziona società da rilasciare** nella pagina selezionare l'entità legale **USMF** in cui deve essere rilasciato il prodotto.

18. Selezionare il pulsante **Avanti** nella parte inferiore della pagina.

19. Nella pagina **Conferma selezione** impostare il valore **di Mostra infolog in caso di errore** come **Sì** ed **Esegui come batch** come **No.**

20. Selezionare il pulsante **Fine** nella parte inferiore della pagina.

21. Nel riquadro di spostamento selezionare Moduli e quindi selezionare Gestione informazioni sul prodotto. Quindi nel menu Prodotti selezionare **Prodotti rilasciati** .

22. Nella pagina **Rilascia** **prodotti** individuare il nuovo elemento **GTL007** nella griglia. 

23. Selezionare il collegamento al prodotto e passare alla pagina **Dettagli prodotto** .

24. Nella scheda **Dettaglio generale** immettere quanto segue:

    - **Gruppo di modelli di elemento**: FIFO

25. Nella scheda **Dettaglio acquisto** immettere quanto segue:

    - **Unità**: ea

    - **Gruppo di imposte sulle vendite dell'elemento**: ALL

    - **Prezzo**: 30

26. Nella scheda **Dettaglio vendere** immettere quanto segue:

    - **Unità**: ea

    - **Gruppo di imposte sulle vendite dell'elemento**: ALL

    - **Prezzo**: 35

27. Nella scheda **Dettaglio Gestione inventario** immettere quanto segue:

    - **Unità**: ea

28. Nella scheda **Dettaglio tecnico** immettere quanto segue:

    - **Unità BOM**: ea

29. Nella scheda **Dettaglio Gestione costi** immettere quanto segue:

    - **Gruppo di elementi**: audio

30. Per completare la configurazione, selezionare Product nel riquadro azioni. Selezionare il pulsante Convalida nel gruppo Gestisci

    ![Screenshot che illustra il gruppo Mantieni sotto il pulsante Product nel riquadro azioni. Il pulsante Convalida nel gruppo Mantieni è selezionato.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-10.png)

31. Verificare di aver visualizzato il banner informativo che conferma che tutti i valori di campo necessari sono stati convalidati.

    ![Screenshot che mostra il banner informativo che conferma che tutti i valori di campo necessari sono stati convalidati. ](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-11.png)

32. Chiudere tutte le pagine e tornare alla home page.
