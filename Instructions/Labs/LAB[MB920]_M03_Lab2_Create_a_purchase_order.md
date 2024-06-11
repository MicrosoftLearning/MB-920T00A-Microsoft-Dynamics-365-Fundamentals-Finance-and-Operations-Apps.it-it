---
lab:
  title: 'Lab 2: Creare un ordine di acquisto'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Modulo 3: imparare i concetti fondamentali di Microsoft Dynamics 365 Supply Chain Management

## Lab 2: Creare un ordine di acquisto

## Configurazione del lab

   - **Tempo stimato**: 15 minuti

## Obiettivo

Questo lab serve ad acquisire familiarità con l'interfaccia utente e con i diversi campi disponibili nel modulo dell'ordine fornitore. Serve inoltre ad apprendere come creare un nuovo ordine fornitore.


## Configurazione del lab

   - **Tempo stimato:**: 10 minuti

## Istruzioni

1. Nella home page delle app per la finanza e le operazioni, in alto a destra verificare che la società in uso sia **USMF**. Se necessario, selezionare la società e dal menu a discesa scegliere **USMF**.

2. In alto a sinistra selezionare il menu a forma di hamburger **Espande il riquadro di spostamento**.

3. Selezionare **Moduli** > **Approvvigionamento** > **Ordini fornitore** > **Tutti gli ordini fornitore**.

4. Nella pagina **Tutti gli ordini fornitore**, nel menu in alto selezionare **+ Nuovo**.

5. Nel riquadro **Crea ordine fornitore** selezionare il menu a discesa **Conto fornitore**, quindi scegliere **US-101**.

> [!NOTE]
> Nota: quando si seleziona un fornitore, i dettagli del record fornitore, come indirizzo, conto fatture, termini e modalità di consegna, vengono copiati come valori predefiniti nell'intestazione dell'ordine. È possibile modificare questi valori in qualsiasi momento.

6. Espandere la sezione **Generale** se necessario.

7. In **DIMENSIONI DI IMMAGAZZINAMENTO** selezionare il menu a discesa **Sito** ed esaminare l'elenco dei siti.

Il campo **Sito** e il campo **Magazzino** specificano dove consegnare i beni o i servizi acquistati. L'indirizzo di consegna predefinito è il sito. Entrambi i campi possono essere compilati con i valori impostati per il fornitore selezionato oppure è possibile specificarli manualmente.

8. In **DATE**, il campo **Data di consegna** si usa per specificare quando i beni e i servizi acquistati devono essere consegnati.

    È possibile specificare una singola data di consegna per l'ordine oppure assegnare date di consegna individuali alle singole righe dell'ordine. Se la data di consegna specificata qui non può essere rispettata per prodotti o servizi specifici perché hanno lead time più lunghi, tali righe vengono create con una data di consegna successiva.

9. Espandere la sezione **Amministrazione**. La casella **Autore ordine** si può usare per specificare chi effettua l'ordine.

    Potrebbe essere utile condividere questa informazione con il fornitore nel caso in cui debba contattare tale persona. Il valore può essere assegnato automaticamente se l'account utente corrente è associato a un nome nella pagina **Utenti**.

10. Selezionare **OK**.

L'intestazione dell'ordine è stata creata. Quando si usano le righe dell'ordine fornitore, viene visualizzato solo un riepilogo delle informazioni di intestazione. Se è necessario visualizzare il resto delle informazioni, selezionare **Intestazione**.

![Lo screenshot mostra l'intestazione dell'ordine in cui appare il riepilogo delle relative informazioni. La parola Intestazione è evidenziata.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-17.png)

11. In **Righe ordine fornitore** selezionare **Riga ordine fornitore** dal menu.

![Lo screenshot mostra le righe dell'ordine fornitore.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-18.png)

12. In **VISUALIZZAZIONE** selezionare **Dimensioni**.

    I prodotti possono avere varianti che si differenziano per dimensioni, come colore, taglia o stile. I prodotti possono anche essere impostati per usare le dimensioni di immagazzinamento, come sito e magazzino. Esistono inoltre dimensioni di tracciabilità facoltative, ad esempio batch e numeri di serie. Per migliorare l'efficienza della registrazione degli ordini, è possibile aggiungere i campi dimensione usati abitualmente direttamente nella griglia dell'ordine.

13. Nel pannello **Visualizzazione dimensioni**, in **DIMENSIONI PRODOTTO** selezionare la casella di controllo **Colore**.

Facoltativo: se si seleziona l'interruttore **Salva impostazione**, le dimensioni scelte verranno visualizzate anche nella griglia della riga dell'ordine alla successiva apertura della pagina dell'ordine fornitore.

14. Seleziona **OK**.

15. Selezionare il menu a discesa della cella **Numero articolo** e scegliere **T0004**.

È anche possibile digitare nella casella del filtro invece di scorrere l'elenco.

Le righe dell'ordine vengono create per prodotti e servizi specificando un numero di articolo o come spese specificando una categoria di approvvigionamento.

La categoria di approvvigionamento si usa per aggiungere righe in cui gli articoli acquistati vengono considerati direttamente come spese, anziché essere inseriti nell'inventario. Se si deve effettuare un acquisto, è possibile farlo creando una riga ordine fornitore che specifichi una categoria di approvvigionamento, anziché creare una riga con un numero di articolo. Anche gli articoli possono essere associati a una categoria di approvvigionamento e, in questo caso, la categoria di approvvigionamento viene visualizzata solo a scopo informativo.

16. Selezionare il menu a discesa **Colore**, esaminare le opzioni disponibili, quindi selezionare uno dei colori o delle combinazioni di colori.

17. **Sito** e **Magazzino** in genere presentano i valori dell'intestazione dell'ordine, ma è possibile sostituire i campi se alcune righe devono essere consegnate in ubicazioni differenti.

18. Nella casella **Quantità** immettere **10**.

    In **Quantità** viene automaticamente inserita la quantità minima dell'ordine del prodotto, se questa impostazione è configurata, oppure il valore **1**.

19. Alcune informazioni supplementari:

- **Unità**: indica l'unità di misura per la quantità ordinata. Normalmente, l'unità viene fornita automaticamente dall'unità di acquisto nei dati di rappresentazione generale del prodotto.

- **Prezzo unitario**: contiene un valore da un contratto di acquisto o un accordo commerciale. È possibile modificare il prezzo unitario in singole righe dell'ordine, ad esempio se viene negoziato un prezzo speciale con il fornitore.

- **Sconto**: rappresenta un importo di sconto per unità. Questo sconto riduce quindi il prezzo unitario in base allo sconto. Questo sconto viene generalmente fornito automaticamente da contratti di acquisto o accordi commerciali, ma è possibile sostituirlo su singole righe se sono stati negoziati sconti speciali con il fornitore.

- **Percentuale di sconto**: se inserita, riduce di conseguenza l'importo netto per la riga. La percentuale di sconto viene spesso fornita automaticamente da contratti di acquisto o accordi commerciali, ma è possibile sostituirla su singole righe se è stata negoziata una percentuale di sconto speciale con il fornitore.

- **Importo netto**: calcolato da altri campi della riga, inclusi quantità, prezzo unitario, sconto e percentuale di sconto. È possibile modificare l'importo netto, ma in tal caso i campi Prezzo unitario, Sconto e Percentuale sconto restano vuoti. Quando si effettuerà la registrazione rispetto alla riga, l'importo registrato sarà proporzionale all'importo netto. Il campo Importo netto viene usato solo per visualizzare l'importo netto della riga.

20. Sotto le righe dell'ordine fornitore, in fondo alla pagina, selezionare **Dettagli riga**.

21. Selezionare la scheda **Consegna**.

    È possibile assegnare una data di consegna univoca a ciascuna riga dell'ordine. La data viene ereditata dal campo nell'intestazione dell'ordine fornitore, ma è possibile modificarla.

22. Chiudere la pagina **Riga ordine fornitore**.

23. Nella pagina **Tutti gli ordini fornitore** usare la funzionalità Filtro e trovare il nuovo ordine fornitore.

24. Al termine, chiudere la pagina **Tutti gli ordini fornitore** e tornare alla home page.

