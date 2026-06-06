# Programmazione di Applicazioni Data Intensive

Un progetto di analisi e classificazione multiclasse su dati genetici parentali, realizzato con un notebook Jupyter.

## Contenuti principali

- `progetto_parental_genetics_child_traits_eseguito.ipynb`: notebook principale del progetto.
- `parental_genetics_child_traits.csv`: dataset usato per l'analisi e la costruzione dei modelli.

## Descrizione

Il notebook contiene le seguenti fasi:

1. caricamento e analisi esplorativa del dataset;
2. individuazione e gestione dei valori mancanti;
3. preparazione delle feature per la classificazione;
4. confronto tra vari modelli di machine learning;
5. ottimizzazione tramite Grid Search;
6. valutazione finale con metrics bilanciate come `f1_macro`.

## Tecnologie

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- Jupyter Notebook

## Come avviare

1. Apri il repository in VS Code o Jupyter.
2. Avvia il notebook `progetto_parental_genetics_child_traits_eseguito.ipynb`.
3. Esegui le celle in ordine dalla sezione 1 alla sezione 18.

## Nota

Il repository è stato configurato per includere solo il notebook del progetto. Se vuoi eseguire il notebook localmente, assicurati di avere installate le librerie Python richieste e che il file CSV sia presente nella stessa cartella.