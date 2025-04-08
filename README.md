# NLP_UniPD_2025
## Argomenti
Il corso tratterà nel corso di due giorni questi argomenti:
- (Basic) Text Processing
- Language Modeling con N-Gram
- Text Classification con Naive Bayes
  - Bag of Words
- Text Classification con Logistic Regression
- Embeddings
  - TF-IDF
  - Word2Vec
- Neural Networks per NLP
  - Neural Language Model 
  - Text classification con NN
- Recurrent Neural Network (RNN) per NLP
  - RNN Language Model
  - LSTM
  - Text classification con RNN
- Transformers
- Large Language Models (autoregressive)
  - Fine tuning
  - Prompt Engineering
- Retrieval Augmented Generation (RAG)
  - Cenni di Information Retrieval
  - Evaluation
- [cenni] Masked Large Language Models

Il corso sarà composto, per ogni sezione, di una parte teorica e di una parte pratica che condurrò tramite Jupyter Notebook. Ogni notebook verrà pushato su questo repo prima della sessione pratica. In base all'argomento e al tempo a disposizione, agli studenti verrà chiesto di fare alcuni esperimenti partendo dalla base dei miei notebook. Visti i tanti argomenti e il poco tempo a disposizione, però, tendenzialmente le parti pratiche verranno commentate direttamente da me. 

## Requisiti
Sulle vostre macchine dovete aver installato:
- Python 3
- git

## Set-up per esercitazioni
Il repository è stato creato come progetto uv (https://docs.astral.sh/uv/). uv è un tool estremamente veloce e pratico per gestire pacchetti e dipendenze in Python (un'evoluzione di pip). 

Per impostare l'ambiente in cui svolgeremo le esercitazioni, segui i seguenti step:
1. Clona questo repository in una cartella sulla tua macchina
2. Da terminale, entra nella cartella del repository (`<tua_cartella>/NLP_UniPD_2025`)
3. Installa uv: `pip install uv`
4. Esegui `uv run jupyter-lab`

L'ultimo comando aprirà una finestra del tuo browser facendo avviare Jupyter Lab. Se ciò è avvenuto, vuol dire che il setup è andato a buon fine. 

### Kaggle e Colab
I notebook sono stati testati su MacOS (M1-Pro). Dovrebbero funzionare senza grossi problemi su Linux e potenzialmente su Windows, ma non ho testato. Per evitare disastri, raccomando di utilizzare Google Colab o Kaggle. 

Alcuni dei notebook (specialmente quelli sui transformers) verrano eseguiti su Colab anche dal sottoscritto, essendo Linux l'ambiente ideale per quel tipo di dipendenze. 

Se volete clonare direttamente il repo in una vostra cartella Google Drive e visualizzare il contenuto su Colab, potete seguire queste istruzioni (non testate): https://gist.github.com/odewahn/2c0d515a838e65b0e9dcdd0c6e177c29
