# Analisi Sanremo 1951–2023 per Genere
Questo progetto è stato realizzato come esercitazione finale per il corso di Data Analyst (W16D8). L'obiettivo principale è analizzare la rappresentanza di genere tra gli artisti, conduzione, co-conduzione e direzione artistica partecipanti al Festival di Sanremo dal 1951 al 2023.

🔗 Dashboard Looker Studio:
[Visualizza l’analisi interattiva](https://lookerstudio.google.com/reporting/f04a22ae-8c24-4406-b2d6-6bc52d7806ce)

# 📊 Obiettivo
Esplorare l’evoluzione della partecipazione maschile, femminile e mista (duetti, band, gruppi) nel corso dei anni.

Visualizzare i cambiamenti nella rappresentanza di genere nel tempo.

Costruire una dashboard interattiva per facilitare l'esplorazione dei dati.

# 🗂️ Dataset Utilizzati
Sono stati creati e organizzati 4 file Excel tramite Python, Excel e Power Query:

dati-artisti-conduzioni-sanremo-1951-2023

dati-classifica-sanremo-1951-2023

dati-edizioni-sanremo-1951-2023

dati-festival-sanremo-1951-2023

e utilizzato un file Excel dal dataset fornito per la esercitazione:

dati-canzoni-spotify-sanremo-1951-2023

I dati sono stati ottenuti tramite webscraping da Wikipedia alle pagine:
https://it.wikipedia.org/wiki/Festival_di_Sanremo_{anno} d
Lo scraping è stato effettuato con Python. Dove lo scraping automatico non era possibile, i dati sono stati completati con Excel per ogni anno.

# 🛠️ Strumenti Utilizzati
Python:

Web scraping da Wikipedia

Pulizia e trasformazione dei dati (pandas)

Identificazione del genere degli artisti tramite l’API genderize (libreria genderize)

Excel:

Integrazione e completamento dei dati

Operazioni di pulizia aggiuntive

Power Query (in Excel):

Trasformazione dati e gestione delle tabelle

Google Looker Studio:

Visualizzazione interattiva della dashboard finale

# 📈 Contenuti della Dashboard
La dashboard contiene:

Numero di artisti maschili, femminili e misti per anno

Grafici interattivi con filtri per decennio ed edizione

Andamento della rappresentanza di genere nel tempo

Analisi dei Partecipanti al Festival di Sanremo per Decennio e p<span>opolarità su spotify
