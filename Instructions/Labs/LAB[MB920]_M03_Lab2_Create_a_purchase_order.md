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

In genere, gli ordini fornitore vengono creati automaticamente come risultato di una pianificazione generale, una consegna diretta e altri processi. Quando la creazione avviene manualmente, in genere un ordine fornitore viene creato da un addetto acquisti. Creare un ordine di acquisto usando l'azienda USMF. 

## Configurazione del lab

   - **Tempo stimato**: 10 minuti

## Istruzioni

1.  Nella home page **Finance and Operations** ,in alto a destra, verificare di lavorare con l'azienda **USMF** . 

1.  Se necessario, selezionare la società e scegliere **USMF** dal menu. 

1.  In alto a sinistra selezionare il menu hamburger **Espandere il pannello di navigazione**. 

1.  Nel modulo **Approvvigionamento e origine** selezionare **Ordini****di acquisto Tutti gli ordini** >  di acquisto. 

1.  Nella pagina **Tutti gli ordini di acquisto** selezionare **+ Nuovo** nel riquadro azioni. 

1.  Nel riquadro **Crea ordine di acquisto** selezionare il campo **Account fornitore** e immettere o selezionare `US-101`

1.  Quando si seleziona un fornitore, i dettagli del record fornitore, ad esempio indirizzo, account di fattura, termini di recapito e modalità di recapito, verranno copiati come valori predefiniti nell'intestazione dell'ordine di acquisto. Se necessario, è possibile modificare questi valori. 

1.  Espandere la sezione **Generale**. 

1.  In **DIMENSIONI DI IMMAGAZZINAMENTO** selezionare il menu **Sito** ed esaminare l'elenco di siti. 

    > **Nota:** Il campo **Sito** , insieme al campo **Warehouse** , specifica dove devono essere recapitati i beni o i servizi acquistati. L'indirizzo di recapito predefinito viene preso dal **sito**. Entrambi i campi possono essere popolati con i valori configurati per il fornitore selezionato oppure è possibile specificarli manualmente. 

1.  Per **Warehouse** immettere o selezionare `13`

1.   In **DATE** il campo **Data di consegna** consente di specificare quando devono essere consegnati i beni o i servizi approvvigionati.

    > **Nota:** È possibile specificare una singola data di consegna per l'ordine oppure è possibile specificare le singole righe di recapito univoche. Se la data di consegna specificata non può essere rispettata per determinati prodotti o servizi a causa di lead time più lunghi, tali righe verranno create con una data di consegna successiva.

1.  Espandere la sezione **Amministrazione**. Il campo **Orderer** può essere usato per specificare chi sta inserendo l'ordine. 

    > **Nota:** Può essere utile condividere con il fornitore nel caso in cui debbano contattare tale persona. Il valore può essere assegnato automaticamente se l'account utente corrente è associato a un record **Person** nella pagina **Utenti** . 

1.  Selezionare **OK**. 

1.  L'intestazione ordine è ora stata creata. Quando si lavora con le righe ordine fornitore, viene visualizzato solo un riepilogo delle informazioni dell'intestazione.  Se è necessario visualizzare il resto delle informazioni, selezionare la scheda **Intestazione** . 

    ![Schermata che mostra la posizione del menu Intestazione](./media/lp1-m3-purchase-order-header-option.png)

1.  In **Linee di ordine di acquisto**, nella barra degli strumenti selezionare il menu **Della riga di ordine di acquisto** . 

    ![Schermata che mostra la posizione dell'opzione di menu Riga ordine fornitore](./media/lp1-m3-purchase-order-purchase-order-line-menu.png)

1.  In **VISUALIZZAZIONE** selezionare **Dimensioni**. 

    > **Nota:** I prodotti possono essere in varianti differenziate in base alle dimensioni, ad esempio colore, dimensioni o stile. È anche possibile impostare i prodotti per usare le dimensioni di immagazzinamento, ad esempio sito e magazzino.  Sono disponibili anche altre dimensioni di tracciabilità opzionali, ad esempio numeri di batch e di serie.  Per migliorare l'efficienza di una registrazione ordine, è possibile aggiungere i campi delle dimensioni usati comunemente direttamente nella griglia dell'ordine. 

1.  Nel riquadro **Visualizzazione Dimensioni** in **DIMENSIONI PRODOTTO** selezionare **Colore**. 

1.  *Opzionale:* Se si seleziona l'opzione **Salva impostazione** attiva, le dimensioni scelte verranno visualizzate anche nella griglia della riga dell'ordine alla successiva apertura della pagina dell'ordine. 

1.  Selezionare **OK**. 

1.  In **Linee ordine acquisto** selezionare il campo **Numero elemento** e selezionare **T0004**. 

    > **Nota:** Tenere presente che è anche possibile immettere `T0004` nel **filtro** anziché scorrere l'elenco. 

    > **Nota:** Le righe di ordine vengono create per i prodotti e i servizi specificando un **numero di voce** o come spese specificando una **categoria di approvvigionamento**.
    > 
    > **La categoria di approvvigionamento** viene usata per l'aggiunta di righe in cui gli elementi acquistati vengono spese direttamente, anziché passare all'inventario. Ciò significa che se è necessario spese per un acquisto, è possibile farlo creando una riga di ordine di acquisto che specifica una **categoria di approvvigionamento**, anziché creare una riga con un **numero di elemento**. Gli articoli possono anche essere associati a una categoria di approvvigionamento e in questo caso la categoria viene visualizzata solo a scopo informativo. 

1.  Selezionare il menu **Colore**, esaminare le opzioni disponibili e quindi selezionare uno dei colori o delle combinazioni di colori. 

    > **Nota:** **il sito** e **il warehouse** vengono in genere popolati con valori dall'intestazione Dell'ordine di acquisto, ma è possibile eseguire l'override dei campi se alcune righe devono essere recapitate in posizioni diverse. 

1.  Nel campo **Quantity** immettere `10` 

    > **Nota:** La **quantità** viene popolata automaticamente con la **quantità di ordine minima** per il **prodotto** se viene configurata o con un valore **pari a 1**. 

    > **Nota:** Altri campi dettagli riga disponibili: 
    >
    >    - **Unità**: indica l'unità di misura per la quantità ordinata. In genere, questa unità viene fornita automaticamente dall'unità di acquisto nei dati master del prodotto. 
    >
    >    - **Prezzo unitario**: contiene un valore derivato da un contratto di acquisto o da un accordo commerciale. È possibile modificare il prezzo unitario per singole righe ordine, ad esempio se viene negoziato un prezzo specifico con il fornitore. 
    >
    >    - **Sconto**: rappresenta l'importo dello sconto per unità. Questo sconto riduce quindi il prezzo unitario dell'importo corrispondente. Lo sconto viene in genere fornito automaticamente dai contratti di acquisto o dagli accordi commerciali, ma è possibile sostituire l'importo in singole righe se sono stati negoziati sconti specifici con il fornitore. 
    >
    >    - **Percentuale sconto**: quando viene immessa, l'importo netto della riga viene ridotto di conseguenza. La percentuale di sconto viene in genere fornita automaticamente dai contratti di acquisto o dagli accordi commerciali, ma è possibile sostituire il valore in singole righe se è stata negoziata una percentuale di sconto specifica con il fornitore. 
    >
    >    - **Importo netto**: calcolato in base ad altri campi della riga, tra cui Quantità, Prezzo unitario, Sconto e Percentuale sconto. È possibile modificare il valore di Importo netto, ma in questo caso i campi Prezzo unitario, Sconto e Percentuale sconto saranno vuoti e quando si esegue una registrazione in base alla riga l'importo registrato sarà proporzionale all'importo netto. In genere, il campo Importo netto viene usato solo per visualizzare l'importo netto della riga. 

1.  Nella scheda Dettagli **riga** espandere se necessario e selezionare la scheda **Recapito** . 

    > **Nota:** È possibile assegnare una **data di consegna** univoca a ogni riga di ordine. La data viene ereditata dal campo **Data di consegna** nell'intestazione Dell'ordine di acquisto, ma è possibile modificarla qui. 

1.  Prendere nota del **numero di ordine acquisto** e **chiudere** la pagina. 

1.  Nella visualizzazione **Elenco Tutti gli ordini di acquisto** usare **il filtro** per trovare il nuovo ordine di acquisto. 

1.  Al termine, **chiudere** la pagina **Tutti gli ordini di acquisto** e tornare alla Home page. 

