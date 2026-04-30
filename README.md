# Analisi delle Recensioni degli Hotel Europei 🏨📊

Questo progetto analizza oltre 515.000 recensioni di hotel in 6 capitali europee per estrarre insight sulla soddisfazione dei clienti provenienti da tutto il mondo e sulle performance del mercato.

## 📂 Struttura del Progetto
Il lavoro è suddiviso in due fasi principali per garantire la pulizia e la riproducibilità del codice:

🧹 01_EDA_CLEANING.IPYNB: Pulizia dati e feature engineering:
   - Pulizia del dataset originale
   - Gestione dei valori mancanti (latitudine/longitudine)
   - Feature Engineering: creazione di indici di Sentiment e analisi della lunghezza dei testi
   
📈 02_ANALYSIS_PANDAS_PLOTS.IPYNB: Analisi descrittiva e visualizzazioni:
   - Riproduzione di analisi SQL complesse tramite Pandas
   - Creazione di 8 grafici statistici (Line, Bar, BoxPlot, Heatmap)
   - Generazione di una mappa geografica interattiva con Folium

🗄️ CREATE_TABLES.SQL: Schema del database relazionale e popolamento delle tabelle
   - Creazione struttura db e tabelle
   - Popolamento delle tabelle
   - Query

## 🛠️ Tecnologie Utilizzate:
- **Database**: MySQL (gestito tramite Devilbox)
- **Linguaggio**: Python 3.13
- **Librerie**: Pandas, SQLAlchemy, Matplotlib, Seaborn, Folium

## 📈 Risultati Principali:
- Identificata una correlazione inversa (-0.38) tra punteggio e lunghezza della recensione negativa
- Ranking delle città per qualità media: Vienna e Barcellona risultano i mercati più stabili.
- Analisi della stagionalità delle recensioni: nei mesi di maggiore picco incidenza basso score su servizi poco efficienti


*Per una lettura approfondita dei risultati e dei suggerimenti strategici per gli investitori, consultare il **Report Finale in PDF** presente nel repository.
