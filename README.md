# UHI-Analyzer-for-QGIS
Plugin QGIS per l'analisi delle isole di calore urbane sviluppato come progetto di tesi.

Descrizione del progetto

UHI Analyzer for QGIS è un plugin sviluppato per il software QGIS come parte di un progetto di tesi di laurea dedicato allo studio delle isole di calore urbane (Urban Heat Islands, UHI).
L’obiettivo è fornire uno strumento intuitivo e open source per individuare e visualizzare le aree urbane caratterizzate da elevati valori di temperatura superficiale, favorendo una migliore comprensione dei fenomeni microclimatici e delle loro implicazioni ambientali.
Il plugin consente di applicare una soglia di temperatura o indice termico (ad esempio ≥ 0.45 in un intervallo normalizzato da 0 a 1) su un layer vettoriale contenente dati di temperatura superficiale o valori normalizzati.
Realizzato con il supporto dell’intelligenza artificiale (AI), questo progetto rappresenta un esempio concreto di integrazione tra conoscenza scientifica, strumenti GIS e automazione intelligente dello sviluppo software.

Funzionalità principali
- Selezione del layer vettoriale da analizzare
- Scelta del campo attributo contenente i valori termici o normalizzati
- Impostazione di una soglia personalizzata (es. 0.45)
- Creazione di un nuovo layer vettoriale denominato UHI_045
- Conservazione di tutti gli attributi originali
- Interfaccia grafica semplice e integrata in QGIS

🧩 Come installarlo

Scaricare il file .zip del plugin dalla sezione Download
In QGIS, aprire Plugin → Gestisci e Installa Plugin → Installa da ZIP
Selezionare il file scaricato e cliccare Installa Plugin
Dopo l’installazione, il plugin sarà visibile nel menu Plugin → UHI Analyzer for QGIS

🧭 Come utilizzarlo

Caricare un layer vettoriale con dati di temperatura superficiale o valori normalizzati
Dal menu del plugin:
- Selezionare il layer desiderato
- Scegliere il campo attributo (es. LST_norm)
- Impostare la soglia desiderata (es. 0.45)
- Cliccare su Esegui analisi
Il plugin creerà un nuovo layer chiamato UHI_045 contenente solo le aree che superano la soglia impostata

📊 Risultati e applicazioni

Il plugin consente di identificare e mappare le aree più calde della città, facilitando:
- l’analisi della vulnerabilità climatica urbana
- la pianificazione di interventi di mitigazione (es. aree verdi, superfici riflettenti)
- lo studio comparativo di diverse aree o periodi temporali
Grazie alla sua semplicità e rapidità, può essere utilizzato sia in ambito accademico che professionale, diventando un valido supporto alla pianificazione territoriale sostenibile.

🤖 Sviluppo assistito da Intelligenza Artificiale

Il progetto è stato sviluppato con l’ausilio dell’intelligenza artificiale, utilizzando ChatGPT (modello GPT-5) come strumento di co-progettazione.
L’AI ha supportato la generazione del codice Python, la creazione dell’interfaccia grafica, il debugging e la stesura della documentazione.
Questo processo rappresenta un caso concreto di uso etico e costruttivo dell’AI nella ricerca scientifica, dove l’intelligenza artificiale non sostituisce il ricercatore, ma ne potenzia la produttività e la capacità creativa.

📁 Struttura del progetto
UHI_Analyzer/
├── metadata.txt
├── __init__.py
├── uhi_analyzer.py
├── uhi_analyzer_dialog.py
├── uhi_analyzer_dialog_base.ui
├── icon.png
├── resources.qrc

📥 Download

👉 Scarica il Plugin [isole_calore_analyzer.zip](https://github.com/user-attachments/files/22997949/isole_calore_analyzer.zip)

🧑‍💻 Autore

Progetto realizzato nell’ambito della Tesi di Laurea Triennale di
Carmine Imperato,
Università degli Studi di Napoli Federico II, 2025.

🌍 Licenza

Distribuito con licenza MIT Open Source, per incoraggiare la condivisione e la collaborazione all’interno della comunità scientifica e accademica GIS.

🎯 Visione finale

“Trasformare i dati in conoscenza e la conoscenza in azione, per città più resilienti e sostenibili.”

💡 Per ulteriori informazioni o per contribuire al progetto, è possibile aprire una Issue o un Pull Request direttamente su GitHub.
