---
lab:
  title: 'Lab 3.1: Creare un nuovo prodotto'
  module: 'Learning Path 3: Learn the fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Percorso di apprendimento 3: Concetti fondamentali di Microsoft Dynamics 365 Supply Chain Management
# Modulo 2: Descrivere il processo di vendita e approvvigionamento

## Lab 3.1: Creare un nuovo prodotto

Nell'organizzazione si prevede di creare un nuovo elemento, che è una camicia. La camicia avrà colori e dimensioni differenti. In questo lab si apprenderà come creare un nuovo elemento con più varianti e rilasciarlo nella entità giuridica USMF.

## Passaggi del lab

1. Nel riquadro di spostamento Dynamics 365 Supply Chain Management selezionare Moduli e quindi selezionare **Configurazione dimensione > ****e gruppi** varianti di Gestione**** > informazioni prodotto.**** Aprire la **pagina Gruppi di colori** e creare un nuovo record.

    - Gruppo di colori: **ShirtColor**

    - Descrizione: **colore camicia**

2. **Nella scheda dettaglio Righe gruppo** colori immettere i tre record seguenti:

    | **Color** | **Nome colore** |
    |-----------|----------------|
    | Blu      | Blu           |
    | Bianco     | Bianco          |
    | Nero     | Nero          |


3. Selezionare Salva per salvare i record.

4. Selezionare **Product information management > ****Setup Dimension and variant groups (Configurazione > ****dimensione e gruppi** varianti). Aprire la **pagina Gruppi di dimensioni** e creare un nuovo record.

    - Gruppo di dimensioni: **ShirtSize**

    - Descrizione: **Dimensioni camicia**

5. **Nella scheda dettaglio Dimensioni righe** gruppo immettere i tre record seguenti

    | **Dimensione** | **Nome dimensione** |
    |----------|---------------|
    | S        | Piccolo         |
    | M        | Medio        |
    | L        | Grande         |


6. Salvare i record

7. Nel riquadro di spostamento Dynamics 365 Supply Chain Management selezionare **Moduli** e quindi selezionare **Gestione** delle informazioni sul prodotto. Scegliere quindi Master** prodotto dal **menu **Prodotti**.

8. **Nella pagina Master** prodotto, nel menu superiore, selezionare **+ Nuovo**.

9. **Nella pagina Nuovo prodotto, nel **campo Tipo di** prodotto**, verificare che **l'elemento** sia selezionato.

10. Nel campo Sottotipo** prodotto verificare che **l'opzione **Product** **master** sia selezionata.

11. **Nella scheda Identificazione** immettere **SH001** nella **casella Numero** prodotto.

12. **Nel campo Nome** prodotto immettere **Shirt**.

13. **Nel campo Gruppo di dimensioni** Prodotto immettere **ColorSize**.

14. Selezionare il pulsante **OK**.

15. **Nel menu Prodotto** nel riquadro azioni selezionare **Gruppi di dimensioni** nel **gruppo Configura**.

16. Nell'elenco **a discesa Gruppo** di dimensioni di archiviazione selezionare **SiteWH**.

17. Nell'elenco **a discesa Gruppo di dimensioni** di rilevamento selezionare **** Nessuno.

18. Selezionare il pulsante **OK**.

19. Selezionare **ShirtColor** nell'elenco **Gruppo** colori.

20. Selezionare **ShirtSize** nell'elenco **Gruppo dimensioni** .

21. Selezionare il **pulsante Varianti** prodotto nel riquadro azioni.

22. **Nella pagina Varianti** prodotto selezionare il **pulsante Suggerimenti** varianti nel riquadro azioni.

23. Selezionare il **pulsante Suggerisci tutto** nella **pagina Suggerimenti** varianti.

24. Selezionare le varianti suggerite selezionando il **pulsante Seleziona tutto** seguito dal **pulsante Crea** .

Le varianti verranno create nella pagina Varianti prodotto.

25. Selezionare il **pulsante Rilascia prodotti** nel riquadro azioni per rilasciare il prodotto in una persona giuridica.

26. Viene visualizzata una pagina che mostra il primo passaggio come **Seleziona i prodotti da rilasciare**.

27. Selezionare il pulsante **Avanti** nella parte inferiore della pagina.

28. Selezionare le varianti da rilasciare nella persona giuridica e selezionare il **pulsante Avanti** .

29. **Nella pagina Seleziona società da rilasciare** selezionare la **persona giuridica USMF** in cui rilasciare il prodotto.

30. Selezionare il pulsante **Avanti** nella parte inferiore della pagina.

31. **Nella pagina Conferma selezione** impostare il valore di **Mostra infolog in caso di errore** su **Sì** e **Esegui come batch** su **No**.

32. Selezionare il pulsante **Fine** nella parte inferiore della pagina.

33. In alto a destra passare a **USMF** come persona giuridica.

34. Nel riquadro di spostamento selezionare **Moduli**, quindi scegliere **Gestione informazioni sul prodotto**. Nel menu **Prodotti** selezionare **Prodotti rilasciati**.

33. Nella **pagina Rilascio prodotti** individuare il nuovo elemento **SH001** nella griglia.

34. Selezionare il collegamento del prodotto e passare alla **pagina Dei dettagli** del prodotto rilasciato.

35. **Nella scheda dettaglio Generale** immettere quanto segue:

    - Gruppo di modelli di elementi: **FIFO**

36. **Nella scheda dettaglio Acquista** immettere quanto segue:

    - Unità: **ea**

    - Gruppo iva articolo: **ALL**

    - Prezzo: **30**

37. Nella scheda dettaglio Sell (Vendi **) **immettere quanto segue:

    - Unità: **ea**

    - Gruppo iva articolo: **ALL**

    - Prezzo: **35**

38. **Nella scheda dettaglio Gestisci inventario** immettere quanto segue:

    - Unità: **ea**

39. Nella scheda dettaglio Engineer (Ingegnere **) **immettere quanto segue:

    - Unità bom: **ea**

40. **Nella scheda dettaglio Gestisci costi** immettere quanto segue:

    - Gruppo di elementi: **Audio**

41. Per completare la configurazione, selezionare **Prodotto** nel riquadro azioni. Selezionare il **pulsante Convalida** sotto il **gruppo Mantieni** .

42. Chiudere tutte le pagine e tornare alla **home** page.

 
