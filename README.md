# Tecniche probabilistiche per il riconoscimento di argomenti latenti: il modello PLSA 📚

Questo repository ospita la mia tesi di Laurea Triennale in Matematica (110/110 con Lode), un'analisi teorica approfondita sul **Probabilistic Latent Semantic Analysis (PLSA)** e sulla sua applicazione nel recupero dell'informazione.

## 🎯 Obiettivo della Ricerca
Lo studio analizza l'evoluzione dai modelli deterministici (LSI - Latent Semantic Indexing) a quelli probabilistici, focalizzandosi sulla capacità del modello **PLSI/PLSA** di identificare relazioni semantiche latenti tra documenti e termini tramite variabili non osservabili.

## 🧠 Pilastri Matematici Analizzati

### 1. L'Aspect Model
Analisi del modello generativo basato sull'assunzione di indipendenza condizionale, dove la co-occorrenza di termini e documenti è mediata da variabili latenti (argomenti).

### 2. Algoritmo EM (Expectation-Maximization)
Studio dettagliato del processo iterativo per la stima della massima verosimiglianza:
- **E-step**: Calcolo delle probabilità a posteriori delle variabili latenti.
- **M-step**: Aggiornamento dei parametri del modello per massimizzare la log-verosimiglianza attesa.

### 3. Overfitting e Tempered EM
Analisi delle problematiche di generalizzazione del modello e studio delle tecniche di **Tempering** (basate sull'entropia) per migliorare le performance su dati non ancora osservati.

## 🛠️ Perché questo lavoro è rilevante per la Data Science?
Sebbene la tesi sia puramente teorica, i concetti trattati costituiscono le fondamenta matematiche per:
- **Natural Language Processing (NLP)**: Topic modeling e analisi semantica.
- **Sistemi di Raccomandazione**: Modellazione di preferenze latenti.
- **Unsupervised Learning**: Comprensione profonda di algoritmi di clustering probabilistico.

## 📄 Documento Integrale
- [Download Tesi PDF](Angelo_Lapacciana_Tesi_PLSA.pdf)

---
*Lavoro supervisionato dalla Professoressa Nicoletta Del Buono presso l'Università degli Studi di Bari Aldo Moro.*
