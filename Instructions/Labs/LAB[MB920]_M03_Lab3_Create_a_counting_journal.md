---
lab:
  title: 'Lab 3: Creare un giornale di registrazione di conteggio'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Modulo 3: imparare i concetti fondamentali di Microsoft Dynamics 365 Supply Chain Management

## Lab 3: Creare un giornale di registrazione di conteggio

## Configurazione del lab

   - **Tempo stimato:** 10 minuti

## Istruzioni

1.  Nella pagina **Home di Finance and Operations**, in alto a destra, verificare di lavorare con l'a società **USMF**. Se necessario, selezionare la società e dal menu a discesa scegliere **USMF**. 

2.  Nel pannello di navigazione a sinistra, nel modulo **Gestione inventario**, selezionare **Voci del giornale di registrazione** > **Conteggio articoli** > **Conteggio**. 

3.  Selezionare il pulsante **+ Nuovo** nel riquadro Azioni. Verrà visualizzato il riquadro della finestra di dialogo **Crea giornale di registrazione inventario**. Selezionare il pulsante **OK**. 

4.  Il modulo del **Giornale di registrazione conteggio scorte** verrà visualizzato con le informazioni di intestazione e dettagliate. 

    ![Screenshot del modulo Giornale di registrazione di conteggio inventario con le informazioni di intestazione e di dettaglio compilate.](./media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5.  Nel riquadro Azioni selezionare **Crea righe -&gt; Disponibili**. 

6.  Nel riquadro della finestra di dialogo **Crea giornale di registrazione conteggio disponibilità** impostare i campi **Magazzino**, **Stato inventario**, **Posizione** e **Targa** su **Sì**. 

    ![Screenshot del riquadro Crea giornale di registrazione di conteggio disponibilità con i campi impostati come descritto.](./media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7.  Espandere la sezione **Record da includere** e selezionare il pulsante **Filtro**. Per il campo **Numero articolo** digitare `A0001` nel campo **Criteri** e quindi selezionare **OK**. 

8.  Selezionare **OK** nella parte inferiore del riquadro della finestra di dialogo **Crea giornale di registrazione conteggio disponibilità**. 

    La quantità disponibile dell'articolo **A0001** verrà visualizzata nella griglia **Righe giornale di registrazione** con la suddivisione di Sito, Magazzino e Ubicazione. 

9.  Nella colonna **Conteggiata** della sezione **Righe giornale di registrazione** far corrispondere i numeri conteggiati in ciascun Sito/Magazzino e Ubicazione. Notare quanto segue: 

    - Se la quantità in **Disponibilità** è uguale alla quantità in **Conteggiato**, il campo **Quantità** sarà vuoto. 

    - Se il valore del campo **Conteggiato** è maggiore del campo **Disponibilità**, il campo **Quantità** conterrà un valore positivo. 

    - Se il valore del campo **Conteggiato** è minore del campo **Disponibilità**, il campo **Quantità** conterrà un valore negativo. 

10. Modificare l'anno del campo **Data** in ogni riga in modo che sia 2022. 

11. Selezionare il pulsante **Convalida** nel riquadro Azioni, quindi selezionare **OK** nel riquadro della finestra di dialogo. 

12. Selezionare il pulsante **Registra**. 

13. **Chiudere** la pagina e tornare alla home page. 

