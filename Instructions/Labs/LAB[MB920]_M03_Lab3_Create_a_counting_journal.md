---
lab:
  title: 'Lab 3: Creare un giornale di registrazione di conteggio'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>Modulo 3: Concetti fondamentali su Microsoft Dynamics 365 Supply Chain Management

## <a name="lab-3---create-a-counting-journal"></a>Lab 3 - Creare un giornale di registrazione di conteggio

1. Nella home page Finance and Operations, in alto a destra, verificare di lavorare con la società **USMF**. Se necessario, selezionare la società e selezionare **USMF** nell'elenco a discesa.

2. Nel riquadro di spostamento sinistro selezionare **Moduli** > **Gestione inventario** > **Inserimenti nel giornale di registrazione** > **Conteggio articoli** > **Conteggio**.

3. Selezionare il pulsante **+Nuovo** nel riquadro azioni. Verrà visualizzato il modulo della finestra di dialogo **Crea giornale di registrazione inventario** con il pulsante **OK** nella parte inferiore. Selezionare il pulsante **OK**.

4. Il modulo del giornale di registrazione conteggio scorte verrà visualizzato con informazioni di intestazione e dettagliate

    ![Screenshot del modulo del giornale di registrazione conteggio scorte con informazioni di intestazione e dettagliate compilate.](./media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5. Selezionare **Crea righe -&gt; Disponibilità** nel riquadro azioni.

6. Nel riquadro della finestra di dialogo **Crea giornale di registrazione di conteggio disponibilità** impostare i campi **Magazzino**, **Stato inventario**, **Posizione** e **Targa** su **Sì**. 

    ![Screenshot del riquadro della finestra di dialogo Crea giornale di registrazione di conteggio disponibilità con i campi impostati come descritto.](./media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7. Espandere la sezione **Record da includere** e selezionare il collegamento **Filtro**. Per il campo **Numero articolo** digitare **A0001** in Criteri e quindi selezionare **OK**.

8. Selezionare **OK** nella parte inferiore della finestra di dialogo **Crea giornale di registrazione di conteggio disponibilità**.

La quantità disponibile dell'articolo A0001 verrà visualizzata nella sezione **Righe giornale di registrazione** con l'indicazione di Sito, Magazzino, Posizione e Targa.

9. Nella colonna **Conteggiata** della sezione **Righe giornale di registrazione** immettere i numeri conteggiati in ogni Sito/Magazzino/Posizione/Targa. Tenere presente quanto segue:

    - Se la quantità **Disponibilità** corrisponde alla quantità **Conteggiata**, il campo **Quantità** sarà vuoto.

    - Se il valore del campo **Conteggiata** è maggiore del campo **Disponibilità**, il campo **Quantità** conterrà un valore positivo.

    - Se il valore del campo **Conteggiata** è minore del campo **Disponibilità**, il campo **Quantità** conterrà un valore negativo.

10. Selezionare il pulsante **Convalida** nel riquadro azioni e quindi selezionare il pulsante **Registra**.

11. Chiudere la pagina e tornare alla home page.
