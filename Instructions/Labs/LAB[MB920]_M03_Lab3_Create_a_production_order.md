---
lab:
  title: 'Lab 3.2: Creare un ordine di produzione'
  module: 'Learning Path 3: Learn the fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Percorso di apprendimento 3: Concetti fondamentali di Microsoft Dynamics 365 Supply Chain Management
# Modulo 4: Descrivere il processo di produzione

## Lab 3.2: Creare un ordine di produzione

## Obiettivo

Gli ordini di produzione semplificano l'avvio del processo di produzione in Supply Chain Management. In questo lab si acquisirà familiarità con l'interfaccia utente e con le funzionalità del modulo dell'ordine di produzione. Si apprenderà anche come creare ed elaborare un ordine di produzione entro la fine dell'esercizio.

## Passaggi del lab

1. Nella home** page di Dynamics 365 **Supply Chain Management, in alto a destra, verificare di lavorare con la **società USMF**.

2. Se necessario, selezionare la società e dal menu scegliere **USMF**.

3. Nel riquadro di spostamento a sinistra selezionare **Moduli** > **Controllo produzione** > **Ordini di produzione** > **Tutti gli ordini di produzione**.

4. Nel menu in alto selezionare **Nuovo ordine** di produzione e immettere i dati seguenti.

    - Numero articolo: **D0002**

    - Quantità: **10**

    - Sito: **1**

    - Magazzino: **11**

    - Consegna: [selezionare una data di un mese dalla data odierna]

    - Numero DBA: **D0002BOM**

    - Numero di route: **000004**

5. Selezionare il pulsante **Crea**.

Viene creato un nuovo ordine di produzione per 10 quantità dell'articolo D0002.

6. Selezionare **Ordine di produzione (menu riquadro azioni) &gt; Stima processo &gt; .**

7. **Nella finestra di dialogo Stima** selezionare **Standard nel **campo Profit-setting** (Impostazione** profitto), selezionare il **campo** Riferimenti e selezionare il **pulsante OK**.

Lo **stato** dell'ordine di produzione verrà modificato in **Stimato**.

8. Selezionare **Pianifica (menu del riquadro azioni) &gt; Operazioni di pianificazione ordine di &gt; produzione.**

9. Nella **finestra di dialogo Pianificazione** operazioni selezionare **Inoltra da oggi** nel **campo Direzione pianificazione** e selezionare il **pulsante OK** .

10. Selezionare **Visualizza (menu del riquadro azioni) &gt; Prenotazione** della capacità delle informazioni &gt; correlate.

11. Verificare i nuovi record creati nella pagina Prenotazione capacità****.

12. Tornare alla **pagina Tutti gli ordini di** produzione. Si noti che lo **stato** dell'ordine di produzione cambia in **Pianificato**.

13. Selezionare **Ordine di produzione (menu del riquadro azioni) &gt; Rilascio** processo&gt;.

14. **Nella finestra di dialogo Rilascio** selezionare il **campo** Riferimenti e selezionare il **pulsante OK**.

15. Lo **stato** dell'ordine di produzione passerà a **Rilasciato**.

16. Selezionare **Ordine di produzione (menu del riquadro azioni) &gt; Processo &gt; start**.

17. **Nella finestra di dialogo Start** selezionare la **scheda Generale**.

18. **Nella scheda Generale** immettere quanto segue.

    - Data: **data odierna**

    - Quantità: **10**

    - Avviare la produzione: **SÌ**

    - Post route card now: **NO**

    - Dopo la selezione ora: **NO**

19. Selezionare il pulsante **OK**.

Lo **stato** dell'ordine di produzione cambia in **Avviato**.

20. Selezionare **Visualizza (menu riquadro azioni) &gt; Elenco di prelievo &gt;** journal.

Viene creato un nuovo giornale di registrazione elenco di prelievo con tre righe.

21. Pubblicare il giornale di registrazione della lista di prelievo.

22. Tornare alla **pagina Tutti gli ordini di** produzione e selezionare **Visualizza (menu riquadro azioni) &gt; Scheda** route journals&gt;.

Viene creato un nuovo giornale di registrazione carte di route con tre righe.

23. Selezionare il **campo Operazione completata** in tutte e tre le righe e inserire il journal della scheda di route.

24. Tornare alla **pagina Tutti gli ordini di** produzione e selezionare **Produzione ordini (menu riquadro azioni) &gt; Report processo &gt; al termine**.

25. **Nella finestra di dialogo Report come completato** immettere **10** nel **campo Quantità valida**. Selezionare il **campo Fine processo** e selezionare **OK**.

Lo **stato** dell'ordine di produzione passa a **Terminato**. Il magazzino dell'articolo **D0002** aumenta di 10 nel sito 1 e magazzino 11.

26. Selezionare **Gestisci costi (menu riquadro azioni) &gt; Calcoli &gt; Visualizza dettagli** calcolo.

Si noti il costo finale dell'articolo prodotto nella **scheda Panoramica costi** .

 
