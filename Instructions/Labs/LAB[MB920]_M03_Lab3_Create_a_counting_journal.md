---
lab:
  title: 'Lab 3: Creare un giornale di registrazione di conteggio'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Modulo 3: Concetti fondamentali su Microsoft Dynamics 365 Supply Chain Management

## Lab 3: Creare un giornale di registrazione di conteggio

## Configurazione del lab

   - **Tempo stimato**: 10 minuti

## Istruzioni

1.  Nella home page **Finance and Operations** ,in alto a destra, verificare di lavorare con l'azienda **USMF** . Se necessario, selezionare l'azienda e nell'elenco a discesa selezionare **USMF**. 

2.  Nel riquadro di spostamento a sinistra, nel modulo **Gestione inventario** selezionare **Conteggio voci** > **** >  journal **.** 

3.  Selezionare il pulsante **+ Nuovo** nel riquadro azioni. Verrà visualizzata la finestra di dialogo **Crea journal di inventario** . Selezionare il pulsante **OK**. 

4.  Il modulo **Di conteggio inventario** verrà visualizzato con le informazioni sull'intestazione e sulla riga. 

    ![Screenshot del modulo del giornale di registrazione conteggio scorte con informazioni di intestazione e dettagliate compilate.](./media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5.  Nel riquadro azioni selezionare **Crea righe -&gt; A mano**. 

6.  Nel riquadro Finestra di dialogo **Crea journal di conteggio a mano** impostare i campi **Warehouse**, **Inventario**, **Posizione** e **Piatto di licenza** su **Sì**. 

    ![Screenshot del riquadro della finestra di dialogo Crea giornale di registrazione di conteggio disponibilità con i campi impostati come descritto.](./media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7.  Espandere la sezione **Record per includere** e selezionare il pulsante **Filtro** . Per il campo **Numero elemento** immettere `A0001` nel campo **Criteri** e selezionare **OK**. 

8.  Selezionare **OK** nella parte inferiore della finestra di dialogo **Crea journal di conteggio a mano** . 

    Le quantità dell'elemento **A0001** verranno visualizzate nella griglia righe **Journal** con l'interruzione di Site, Warehouse e Location. 

9.  Nella colonna **Conteggiata** della sezione Riga **journal** corrisponde ai numeri conteggiati per ogni sito/magazzino e posizione. Tenere presente quanto segue: 

    - Se la quantità **Disponibilità** corrisponde alla quantità **Conteggiata**, il campo **Quantità** sarà vuoto. 

    - Se il valore del campo **Conteggiata** è maggiore del campo **Disponibilità**, il campo **Quantità** conterrà un valore positivo. 

    - Se il valore del campo **Conteggiata** è minore del campo **Disponibilità**, il campo **Quantità** conterrà un valore negativo. 

10. Modificare l'anno del campo **Date** in ogni riga come 2022. 

11. Selezionare il pulsante **Convalida** nel riquadro azioni e selezionare **OK** nel riquadro della finestra di dialogo. 

12. Selezionare il pulsante **Post** . 

13. **Chiudere** la pagina e tornare alla home page. 

