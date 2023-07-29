---
lab:
  title: 'Lab 1: Creare un conto principale'
  module: 'Module 2: Learn the Fundamentals of Microsoft Dynamics 365 Finance'
---

# Modulo 2. Learn the Fundamentals of Microsoft Dynamics 365 Finance

## Lab 1: Creare un conto principale

## Configurazione del lab

   - **Tempo stimato**: 5 minuti

## Istruzioni


1.  Nella home page **Finance and Operations** , in alto a destra, verificare di lavorare con la società **USMF** .

2.  Se necessario, selezionare la società e scegliere **USMF** dal menu.

3.  Nel riquadro di spostamento a sinistra selezionare **Moduli** > **Contabilità generale** > **Piano dei conti** > **Conti** > **Conti principali**.

4.  Nel riquadro azioni selezionare **+ Nuovo**.

5.  Immettere i valori seguenti nella pagina **Account principale** :

    - Conto principale: **601510**

    - Nome: **International call expense**

    - Tipo di spesa principale: **Spesa**

    - Categoria di conto principale: **TANDEEXP**

    - Valori dare/avere predefiniti: **Dare**

    ![Screenshot che illustra gli account principali- grafico degli account: pagina condivisa in cui è necessario aggiungere valori diversi.](./media/lab-create-a-main-account-01.png)

6.  Passare a **Modules &gt; General ledger Journalntries &gt; General journals (Registrazioni generali del libro mastro&gt;).**

7.  Nel riquadro azioni selezionare **+ Nuovo**.

8.  Immettere il valore seguente nella pagina **Journal generali** e selezionare **Righe** nel riquadro azioni:

    - Nome: GenJrn

9.  Immettere i valori seguenti nella pagina **del voucher journal** :

    - Tipo di account: **Libro mastro**

    - Conto principale: **601510**

    - Debito: **10,00** 

    - Tipo di conto offset: **Libro mastro**

    - Numero conto offset: **110180** 

10. Selezionare il pulsante **Salva** nel riquadro azioni.

11. Selezionare **Convalida simula &gt; registrazione**. 

12. Selezionare il pulsante **Pubblica** nel riquadro azioni. Il giornale di registrazione dovrebbe essere pubblicato.
