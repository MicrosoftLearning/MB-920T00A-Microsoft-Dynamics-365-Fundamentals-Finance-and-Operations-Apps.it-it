---
lab:
  title: 'Lab 2: Integrazione di Excel'
  module: 'Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps'
ms.openlocfilehash: e5929571477cfcdbb1b2e81c72ebc566a96c56a4
ms.sourcegitcommit: 8e5a278c6e08abdcc3fb719796f79842e868606b
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 07/14/2022
ms.locfileid: "147116295"
---
# <a name="module-1-explore-the-core-capabilities-of-dynamics-365-finance-and-operations-apps"></a>Modulo 1. Esplorare le funzionalità principali delle app per la finanza e le operazioni di Dynamics 365

## <a name="lab-2---excel-integration"></a>Lab 2 - Integrazione di Excel

Ora che è stata acquisita familiarità con le app per la finanza e le operazioni, dedicare del tempo a esplorare lo scenario di integrazione di Excel.

### <a name="task-1-create-template"></a>Attività 1: Creare il modello

1. Aprire la home page Finance and Operations. 

2. Passare a **Moduli** > **Comune** > **Comune** > **Integrazione Office** > **Cartella di lavoro di Excel** **Progettazione**. Si noti che la maggior parte degli spostamenti avviene tramite Moduli, pertanto questo passaggio non viene in genere specificato.

3. Cercare **VendorGroup** nel filtro.

4. Nell'elenco dei campi disponibili selezionare i campi **Gruppo di fornitori**, **Descrizione** e **Condizioni di pagamento** e spostarli nella casella di campo selezionata usando la freccia destra.

5. Nel riquadro azioni selezionare il pulsante **Crea cartella di lavoro**.

6. A destra, nel pannello **Salva in**, selezionare il pulsante **Scarica**.

7. Scaricare il file selezionando **Salva con nome** e archiviarlo nella cartella **Download**.

8. Passare a **Comune** > **Integrazione Office** > **Modelli di** **documento**.

9. Selezionare **Nuovo**.

10. Nel pannello di destra, nella sezione **Carica modello**, selezionare il pulsante **Sfoglia** e selezionare il file scaricato in precedenza (se è stato usato il nome predefinito, è DynamicsWorkbook).

11. Nel campo **Nome modello** immettere **CustomVendorGroup**.

12. Selezionare **OK** e quindi **Salva**.

### <a name="task-2-open-in-excel"></a>Attività 2. Aprire in Excel

1. Passare ad **Approvvigionamento** > **Imposta** > **Fornitori** > **Gruppi di fornitori**.

2. Selezionare **Apri in Microsoft Office** > **Apri in Excel** per trovare il nuovo modello, CustomVendorGroup, caricato.

3. Selezionare **CustomVendorGroup** e scaricare il modello di Excel.

4. Salvare e quindi aprire il modello di Excel scaricato, consentirne l'uso se necessario, chiudere l'attivazione e selezionare **Abilita modifica**. Impostare come attendibile questo componente aggiuntivo e quindi eseguire l'accesso (usando le stesse credenziali, se richiesto).

Tutti i dati esistenti della tabella Gruppo di fornitori verranno visualizzati nel foglio di calcolo di Excel.

5. Immettere un nuovo record.

6. Immettere **100** nel campo **Gruppo di fornitori**, **Fornitore assicurazione** nel campo **Descrizione** e **Net10** nel campo **Condizioni di pagamento**.

7. Selezionare il pulsante **Pubblica** nell'app del componente aggiuntivo Office di Microsoft Dynamics.

8. Aprire il modulo **Gruppo di fornitori** per verificare che il nuovo record sia stato aggiunto.

