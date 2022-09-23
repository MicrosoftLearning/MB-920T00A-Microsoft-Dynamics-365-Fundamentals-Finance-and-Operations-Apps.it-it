---
lab:
  title: 'Lab 1: Creare un nuovo prodotto'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
ms.openlocfilehash: e8fad0a9ddf0787c57ee7b98ddc6ef8363832ffc
ms.sourcegitcommit: 178a1e5d74c3902b0514276a3daf4a24c0c4ade7
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 08/01/2022
ms.locfileid: "147444368"
---
# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>Modulo 3: Concetti fondamentali su Microsoft Dynamics 365 Supply Chain Management

## <a name="lab-1---create-a-new-product"></a>Lab 1 - Creare un nuovo prodotto

## <a name="objectives"></a>Obiettivi

In Contoso Entertainment System USA (USMF) è necessario creare un nuovo articolo per una nuova configurazione di un armadietto da acquistare dai fornitori.

## <a name="lab-setup"></a>Configurazione del lab

   - **Tempo stimato**: 10 minuti

## <a name="instructions"></a>Istruzioni

1. Nella home page Finance and Operations, in alto a destra, verificare di lavorare con la società USMF.

1. Se necessario, selezionare la società e scegliere **USMF** dal menu.

1. In alto a sinistra selezionare il menu hamburger **Espandere il pannello di navigazione**.

1. Nel riquadro di spostamento selezionare **Moduli** > **Gestione informazioni sul prodotto** e quindi nella categoria **Prodotti** selezionare **Prodotti rilasciati**.

1. Nella pagina dettagli Prodotto rilasciato, nel menu in alto selezionare **+ Nuovo**.

1. Nel riquadro Nuovo prodotto rilasciato, nel menu **Tipo di prodotto** verificare che sia selezionato **Articolo**.

1. Nel menu **Sottotipo di prodotto** verificare che sia selezionato **Prodotto**.

1. Selezionare il menu **Gruppo di dimensioni di tracciabilità**, quindi scegliere **Nessuno**.

1. In **IDENTIFICAZIONE**, nelle caselle **Numero prodotto** e **Numero articolo** immettere **GTL007**.

1. Nella casella **Nome prodotto** immettere **Cabinet 2**.

1. In **GRUPPI DI RIFERIMENTO** selezionare il menu **Gruppo di modelli di articoli**, quindi selezionare **FIFO (First-In-First-Out)** .

1. Selezionare il menu **Gruppo di articoli** e quindi scegliere **TV&Video**.

1. Selezionare il menu **Gruppo di dimensioni di immagazzinamento**, quindi scegliere **SiteWH**.

1. In **UNITÀ DI MISURA** verificare che siano impostati i valori seguenti:

    | **Impostazione**| **Valore**|
    | :--- | :--- |
    | Unità di magazzino| ea per tutti|
    | Unità di acquisto| ea per tutti|
    | Unità di vendita| ea per tutti|
    | Unità DBA| ea per tutti|

1. In **TASSAZIONE VENDITE** selezionare il menu **Fascia IVA articoli**, quindi selezionare **TUTTO**.

1. In **TASSAZIONE ACQUISTI** selezionare il menu **Fascia IVA articoli**, quindi selezionare **TUTTO**.

1. In PREZZI, nella casella Prezzo di acquisto immettere 30,00.

1. Nella casella Prezzo di vendita immettere 30,00.

1. Il nuovo prodotto rilasciato sarà simile a quanto segue:

    ![Schermata che mostra il modulo del nuovo prodotto rilasciato completato](./media/lp1-m2-new-release-product.png)

1. Selezionare **OK**.

1. Per assicurarsi che il prodotto sia finalizzato, sulla barra multifunzione in **Gestisci** selezionare **Convalida**.

    ![Schermata che mostra la barra multifunzione con il comando Convalida evidenziato](./media/lp1-m2-validate-ribbon-bar.png)

1. Verificare che venga visualizzato il banner di informazioni che conferma che tutti i valori dei campi richiesti sono stati convalidati.

    ![Schermata della notifica informativa che indica che tutti i campi richiesti sono stati convalidati](./media/lp1-m2-confirmation-of-validation.png)

1. Chiudere tutte le pagine e tornare alla home page.
