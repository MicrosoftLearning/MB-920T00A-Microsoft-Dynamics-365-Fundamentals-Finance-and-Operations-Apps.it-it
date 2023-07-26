---
lab:
  title: 'Lab 2: Creare un ordine fornitore'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Modulo 3: Concetti fondamentali su Microsoft Dynamics 365 Supply Chain Management

## Lab 2: Creare un ordine fornitore

## Configurazione del lab

   - **Tempo stimato**: 15 minuti

## Obiettivo

In questo lab si ha familiarità con l'interfaccia utente e i diversi campi disponibili nel modulo di ordine di acquisto. Si apprenderà anche come creare un nuovo ordine di acquisto.


## Configurazione del lab

   - **Tempo stimato**: 10 minuti

## Istruzioni

1. Nella home page Finance and Operations ,in alto a destra, verificare di lavorare con l'azienda **USMF** . Se necessario, selezionare l'azienda e nell'elenco a discesa selezionare **USMF**.

2. In alto a sinistra selezionare **il menu Espandi il menu hamburger del riquadro di spostamento** .

3. Selezionare **Moduli** > **Approvvigionamento** > **Ordini fornitore** > **Tutti gli ordini fornitore**.

4. Nella pagina **Tutti gli ordini di acquisto** selezionare **+Nuovo** nel menu superiore.

5. Nel riquadro **Crea ordine di acquisto** selezionare l'elenco a discesa **Account fornitore** e quindi selezionare **US-101**.

> [!NOTE]
> Nota: quando si seleziona un fornitore, i dettagli del record fornitore, ad esempio l'indirizzo, l'account della fattura, le condizioni di recapito e la modalità di recapito, vengono copiati come valori predefiniti nell'intestazione dell'ordine. È possibile modificare questi valori in qualsiasi momento.

6.  Espandere la sezione **Generale** se necessario.

7. In **DIMENSIONI ARCHIVIAZIONe** selezionare l'elenco a discesa **Sito** e esaminare l'elenco dei siti.

Il campo **Sito** , insieme al campo **Warehouse** , specificare dove devono essere recapitati i beni o i servizi acquistati. L'indirizzo di consegna predefinito è il sito.  Entrambi i campi possono essere popolati con i valori configurati per il fornitore selezionato oppure è possibile specificarli manualmente.

8. In **DATE**, il campo **Data di consegna** viene usato per specificare quando devono essere recapitati beni e servizi acquistati.

    È possibile specificare una singola data di consegna per l'ordine oppure date di consegna specifiche per ogni riga ordine.  Se la data di consegna specificata qui non può essere soddisfatta per prodotti o servizi specifici perché hanno tempi di lead più lunghi, tali righe vengono create con una data di consegna successiva.

9. Espandere la sezione **Amministrazione**. La casella **Autore ordine** consente di specificare chi sta effettuando l'ordine.

    Può essere utile condividere queste informazioni con il fornitore nel caso in cui debba contattare tale persona. Il valore può essere assegnato automaticamente se l'account utente corrente è associato a un nome nella pagina **Utenti** .

10. Selezionare **OK**.

L'intestazione ordine è ora stata creata. Quando si lavora con le righe dell'ordine di acquisto, viene visualizzato solo un riepilogo delle informazioni sull'intestazione. Per visualizzare il resto delle informazioni, selezionare **Intestazione**.

![Screenshot che illustra l'intestazione dell'ordine in cui viene visualizzato il riepilogo delle informazioni sull'ordine. La parola Intestazione è evidenziata.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-17.png)

11. In **Linee ordine di acquisto** selezionare **Riga ordine acquisto**.

![Screenshot che illustra le righe dell'ordine di acquisto.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-18.png)

12. In **VISUALIZZAZIONE** selezionare **Dimensioni**.

    I prodotti possono essere in varianti differenziate per dimensioni, ad esempio colore, dimensioni o stile. È anche possibile impostare i prodotti per usare le dimensioni di immagazzinamento, ad esempio sito e magazzino.  Sono disponibili anche altre dimensioni di tracciabilità opzionali, ad esempio numeri di batch e di serie.  Per migliorare l'efficienza di una registrazione ordine, è possibile aggiungere i campi delle dimensioni usati comunemente direttamente nella griglia dell'ordine.

13.  Nel pannello **Visualizzazione dimensioni**, in **DIMENSIONI PRODOTTO** selezionare la casella di controllo **Colore**.

Facoltativo: se si seleziona l'opzione **Salva interruttore di impostazione** , le dimensioni selezionate verranno visualizzate anche nella griglia della riga dell'ordine la prossima volta che si apre la pagina dell'ordine di acquisto.

14. Selezionare **OK**.

15. Selezionare l'elenco a discesa **Numero di elemento** e quindi **selezionare T0004**.

Tenere presente che è anche possibile digitare nella casella di filtro anziché scorrere l'elenco.

Le righe ordine vengono create per i prodotti e i servizi specificando un numero di articolo oppure come spese specificando una categoria di approvvigionamento.

La categoria di approvvigionamento viene usata per aggiungere righe quando gli articoli approvvigionati vengono contabilizzati direttamente invece che essere inseriti nell'inventario. Se è necessario effettuare un acquisto, è possibile farlo creando una riga di ordine di acquisto che specifica una categoria di approvvigionamento, anziché creare una riga con un numero di articolo. Gli elementi possono anche essere associati a una categoria di approvvigionamento e, in questo caso, la categoria di approvvigionamento viene visualizzata solo come informazioni.

16. Selezionare l'elenco a discesa **Colore** , esaminare le opzioni disponibili e quindi selezionare una delle combinazioni di colori o colori.

17. **Il sito** e **il warehouse** vengono in genere popolati con valori dall'intestazione dell'ordine, ma è possibile eseguire l'override dei campi se alcune righe devono essere recapitate in posizioni diverse.

18. Nella casella **Quantità** immettere **10**.

    La **quantità** viene popolata automaticamente con la quantità minima di ordine per il prodotto se viene configurata o con il valore **1**.

19. Alcune informazioni aggiuntive:

- **Unità**: indica l'unità di misura per la quantità ordinata. In genere, questa unità viene fornita automaticamente dall'unità di acquisto nei dati master del prodotto.

- **Prezzo unitario**: contiene un valore derivato da un contratto di acquisto o da un accordo commerciale. È possibile modificare il prezzo unitario su singole righe di ordine, ad esempio se un prezzo univoco viene negoziato con il fornitore.

- **Sconto**: rappresenta l'importo dello sconto per unità. Questo sconto riduce quindi il prezzo unitario dell'importo corrispondente. Lo sconto viene in genere fornito automaticamente dai contratti di acquisto o dagli accordi commerciali, ma è possibile sostituire l'importo in singole righe se sono stati negoziati sconti specifici con il fornitore.

- **Percentuale sconto**: quando viene immessa, l'importo netto della riga viene ridotto di conseguenza. La percentuale di sconto viene spesso fornita automaticamente da contratti di acquisto o contratti commerciali, ma è possibile eseguire l'override sulle singole righe se una percentuale di sconto univoca è stata negoziata con il fornitore.

- **Importo netto**: calcolato in base ad altri campi della riga, tra cui Quantità, Prezzo unitario, Sconto e Percentuale sconto. È possibile modificare l'importo netto, ma quindi i campi Unit Price, Sconto e Percentuale sconto sono vuoti. Quando si pubblica verso la riga, l'importo registrato sarà proporzionale all'importo netto. Il campo Importo netto viene usato solo per visualizzare l'importo netto della riga.

20. Sotto alle righe ordine fornitore, nella parte inferiore della pagina, selezionare **Dettagli riga**.

21. Selezionare la scheda **Consegna**.

    È possibile assegnare una data di consegna univoca a ogni riga dell'ordine. La data viene ereditata dal campo nell'intestazione dell'ordine di acquisto, ma è possibile modificarla.

22.  Chiudere la pagina **Riga ordine fornitore**.

23.  Nella pagina **Tutti gli ordini fornitore** usare la funzionalità di filtro e cercare il nuovo ordine fornitore.

24. Al termine, chiudere la pagina **Tutti gli ordini di acquisto** e tornare alla home page.

