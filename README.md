# Tecniche probabilistiche per il riconoscimento di argomenti latenti: il modello PLSA

Progetto di tesi per il corso di laurea in **Matematica** presso l'**Università degli Studi di Bari Aldo Moro**.

---

## 📄 Descrizione del Progetto
Questa tesi analizza in dettaglio il modello **Probabilistic Latent Semantic Analysis (PLSA)**, una tecnica statistica avanzata per l'estrazione di conoscenza semantica da grandi volumi di dati testuali. 

Il lavoro esplora il passaggio dai modelli algebrici tradizionali, come la **Latent Semantic Analysis (LSA)** basata sulla decomposizione ai valori singolari (SVD), verso approcci probabilistici basati sul principio di massima verosimiglianza.

### Obiettivi principali:
* Mappare documenti e termini in uno **spazio semantico latente** a bassa dimensionalità.
* Risolvere i limiti linguistici della **polisemia** e della **sinonimia**.
* Valutare l'efficienza computazionale tramite implementazioni parallele su **GPU**.

---

## 📊 Struttura della Tesi
La tesi è suddivisa in tre capitoli fondamentali:

1.  **Capitolo 1 - Fondamenti**: Introduzione al **Natural Language Processing (NLP)**, al **Vector Space Model (VSM)** e agli strumenti di algebra lineare e probabilità necessari (SVD, distribuzioni multinomiali).
2.  **Capitolo 2 - Il Modello PLSA**: Analisi dell'**Aspect Model**, dell'algoritmo **Expectation-Maximization (EM)** e della sua variante **Tempered EM (TEM)** per il controllo dell'overfitting.
3.  **Capitolo 3 - Applicazioni e Risultati**: Confronti sperimentali su dataset standard (MED, CRAN, CACM, CISI) e applicazioni in **Computer Vision** e calcolo parallelo via **CUDA**.

---

## 📈 Risultati Chiave
* **Miglioramento Precisione**: Il modello **Probabilistic Latent Semantic Indexing (PLSI)** ha mostrato incrementi di *average precision* fino al **+49.7%** sul dataset CRAN e **+58.3%** sul dataset CISI rispetto ai metodi baseline.
* **Riduzione Perplexity**: PLSA riduce la perplexity (incertezza predittiva) in modo significativamente più robusto rispetto a LSA all'aumentare della dimensionalità latente.
* **Accelerazione GPU**: L'utilizzo di architetture GPU ha permesso uno **speedup** notevole dei tempi di calcolo per le classi latenti, rendendo il modello scalabile su dataset complessi.

---

## 🛠️ Modello Matematico
Il processo generativo alla base della PLSA si fonda sull'equazione di probabilità congiunta:

$$P(d, w) = P(d) \sum_{z \in Z} P(w|z)P(z|d)$$

Dove:
* $d$ rappresenta il documento.
* $w$ rappresenta il termine (parola).
* $z$ è la variabile latente (argomento o topic).

---

## 👨‍🎓 Informazioni Accademiche
* **Laureando:** Angelo Gabriele Lapacciana 
* **Relatrice:** Prof.ssa Nicoletta Del Buono 
* **Materia:** Metodi Numerici in Data Science 
* **Anno Accademico:** 2024-2025 

---

## 📚 Bibliografia Essenziale
* Hofmann, T. (1999). *Probabilistic latent semantic indexing*.
* Hofmann, T. (2001). *Unsupervised learning by probabilistic latent semantic analysis*.
* Eckart, C., & Young, G. (1936). *The approximation of one matrix by another of lower rank*.

---

## 📜 Licenza
Questo progetto è distribuito per fini accademici e di consultazione.
