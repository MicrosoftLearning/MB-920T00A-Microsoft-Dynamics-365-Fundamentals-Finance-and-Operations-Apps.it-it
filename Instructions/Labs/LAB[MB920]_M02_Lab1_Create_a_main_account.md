---
lab:
  title: 'Lab 1: Creare un account principale'
  module: 'Module 2: Learn the Fundamentals of Microsoft Dynamics 365 Finance'
---

# Modulo 2: Informazioni sui concetti fondamentali di Microsoft Dynamics 365 Finance

## Lab 1: Creare un account principale

## Configurazione del lab

   - **Tempo** stimato: 5 minuti

## Istruzioni


1.  Nella **home page delle app per la finanza e le operazioni**, in alto a destra verificare che la società in uso sia **USMF**.

2.  Se necessario, selezionare la società e dal menu scegliere **USMF**.
3.  Nel riquadro di spostamento a sinistra selezionare **Moduli > Contabilità generale > Calendari > Calendari** fiscali.
4.  Selezionare Calendario **fiscale**
5.  Se l'anno di calendario corrente è già stato creato, uscire dalla **pagina Calendari** fiscali.
6. Se l'anno di calendario corrente non viene creato, selezionare il **pulsante Nuovo anno** nel riquadro azione e immettere l'anno corrente come visualizzato nello screenshot seguente. Selezionare il **pulsante** Crea per creare il calendario dell'anno corrente.

![Lo screenshot illustra come creare il nuovo anno nel calendario fiscale](./media/lab-create-a-main-account-04.png)


4.  Nel riquadro di spostamento a sinistra selezionare **Moduli** > **Contabilità generale** > **Piano dei conti** > **Conti** > **Conti principali**.

5.  Nel riquadro Azioni selezionare **+ Nuovo**.

6.  Immettere i seguenti valori nella pagina **Conto principale**:

    - Conto principale: **601510**

    - Nome: **Spese per chiamate internazionali**

    - Tipo di conto principale: **Spese**

    - Categoria di conti principali: **TANDEEXP**

    - Valori dare/avere predefiniti: **Dare**

    ![Lo screenshot mostra la pagina Conti principali - piano dei conti: Condiviso, in cui è necessario aggiungere valori diversi.](./media/lab-create-a-main-account-01.png)

7.  Passare a **Moduli &gt; Contabilità generale &gt; Scritture contabili &gt; Giornali di registrazione generali**.

8.  Nel riquadro Azioni selezionare **+ Nuovo**.

9.  Immettere il seguente valore nella pagina **Giornali di registrazione generali** e selezionare **Righe** nel riquadro Azioni:

    - Nome: GenJrn

10.  Immettere i seguenti valori nella pagina **Giustificativo giornale di registrazione**:

    - Tipo di conto: **CoGe**

    - Conto principale: **601510**

    - Dare: **10,00** 

    - Tipo di conto di contropartita: **CoGe**

    - Numero del conto di contropartita: **110180** 

11. Selezionare il pulsante **Salva** nel riquadro Azioni.

12. Selezionare **Convalida &gt; Simula registrazione**. 

13. Selezionare il pulsante **Registra** nel riquadro Azioni. La registrazione del giornale dovrebbe essersi verificata.
