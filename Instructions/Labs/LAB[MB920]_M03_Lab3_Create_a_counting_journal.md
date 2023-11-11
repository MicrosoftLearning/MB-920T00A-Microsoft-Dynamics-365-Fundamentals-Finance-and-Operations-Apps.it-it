---
lab:
  title: 'Lab 3: Creare un journal di conteggio'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Modulo 3: Informazioni fondamentali sulla gestione della supply chain di Microsoft Dynamics 365

## Lab 3: Creare un journal di conteggio

## Configurazione del lab

   - **Tempo** stimato: 10 minuti

## Istruzioni

1.  **Nella home page Finance and Operations** , in alto a destra, verificare di lavorare con la **società USMF**. Se necessario, selezionare la società e dal menu a discesa scegliere **USMF**. 

2.  Nel modulo Gestione inventario del riquadro **di spostamento a sinistra selezionare **Voci journal Conteggio****** >  elementi.** > **** 

3.  Selezionare il **pulsante + Nuovo** nel riquadro azioni. Verrà visualizzata la **finestra di dialogo Crea giornale di registrazione** inventario. Selezionare il pulsante **OK**. 

4.  Il **modulo Giornale di registrazione** conteggio inventario verrà visualizzato con le informazioni di intestazione e riga. 

    ![Screenshot del modulo Giornale di registrazione di conteggio inventario con le informazioni di intestazione e di dettaglio compilate.](./media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5.  Nel riquadro azioni selezionare **Crea righe -&gt; A portata di mano**. 

6.  Nella finestra **di dialogo Crea giornale di registrazione** conteggio manuale impostare i **campi Magazzino**, **Stato inventario**, **Posizione** e **Targa** su **Sì**. 

    ![Screenshot del riquadro Crea giornale di registrazione di conteggio disponibilità con i campi impostati come descritto.](./media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7.  Espandere la **sezione Record da includere** e selezionare il **pulsante Filtro** . Per il **campo Numero articolo** immettere `A0001` nel **campo Criteri** e selezionare **OK**. 

8.  Selezionare **OK** nella parte inferiore della **finestra di dialogo Crea giornale di registrazione** conteggio a portata di mano. 

    Le quantità dell'articolo **A0001** verranno visualizzate nella **griglia Righe journal** con la rottura di Site, Warehouse e Location. 

9.  **Nella colonna Conteggiato** della **sezione Riga journal** trovare le corrispondenze con i numeri conteggiati per ogni sito/magazzino e località. Notare quanto segue: 

    - Se la quantità in **Disponibilità** è uguale alla quantità in **Conteggiato**, il campo **Quantità** sarà vuoto. 

    - Se il valore del campo **Conteggiato** è maggiore del campo **Disponibilità**, il campo **Quantità** conterrà un valore positivo. 

    - Se il valore del campo **Conteggiato** è minore del campo **Disponibilità**, il campo **Quantità** conterrà un valore negativo. 

10. Modificare l'anno del **campo Data** in ogni riga in modo che sia 2022. 

11. Selezionare il **pulsante Convalida** nel riquadro azioni e selezionare **OK** nel riquadro della finestra di dialogo. 

12. Selezionare il pulsante **Registra**. 

13. **Chiudere** la pagina e tornare alla home page. 

