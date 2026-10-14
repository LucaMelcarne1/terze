# 💻 Informatica - Classe Terza A.S. 2025/2026

Benvenuti nella repository ufficiale del corso di **Informatica** per la classe terza (Indirizzo Informatica e Telecomunicazioni). 

Questo spazio funge da **manuale dinamico**, **raccolta di esempi pratici** e **guida agli esercizi** svolti durante l'anno scolastico. Tutti gli esempi e i codici sorgente sono scritti in **C++** e testati per l'ambiente di laboratorio.

---

## 📌 Indice dei Contenuti

1. [🛠️ Ambiente di Sviluppo (IDE)](#️-ambiente-di-sviluppo-ide)
2. [📖 Manuale e Documentazione di Riferimento](#-manuale-e-documentazione-di-riferimento)
3. [🗺️ Programma Didattico](#️-programma-didattico)
4. [📂 Struttura della Repository](#-struttura-della-repository)
5. [🚀 Regole di Scrittura del Codice](#-regole-di-scrittura-del-codice)

---

## 🛠️ Ambiente di Sviluppo (IDE)

In laboratorio e a casa utilizzeremo **Dev-C++** come ambiente di sviluppo integrato (IDE) di riferimento.

* **IDE Ufficiale:** Dev-C++ (Embarcadero release o Orwell Dev-C++)
* **Compilatore:** GCC / MinGW (incluso nell'installazione dell'IDE)
* **Configurazione Consigliata:** Impostare il compilatore per supportare lo standard **C++11** o superiore:
  > *Strumenti (Tools) ➔ Opzioni del Compilatore (Compiler Options) ➔ Aggiungi i seguenti comandi quando si chiama il compilatore: `-std=c++11`*

---

## 📖 Manuale e Documentazione di Riferimento

Il nostro principale punto di riferimento teorico e pratico per la sintassi del linguaggio sarà la guida di **W3Schools**:

* 📘 **Guida Principale:** [Libro di testo - W3Schools C++ Tutorial](https://www.w3schools.com/cpp/)
* 📚 **Approfondimenti:** [CppReference (Italiano)](https://it.cppreference.com/)

Consultate regolarmente la documentazione su W3Schools per verificare sintassi, esempi e funzioni integrate della libreria standard.

---

## 🗺️ Programma Didattico

Il percorso formativo dell'anno è suddiviso nei seguenti moduli:

### 🔹 Modulo 1: Fondamenti e Strutture di Controllo
* Struttura base di un programma C++ e flusso I/O (`iostream`, `cin`, `cout`).
* Tipi di dato base, variabili, costanti e operatori aritmetici/logici.
* **Selezione:** `if`, `else`, `switch-case`.
* **Iterazione (Cicli):** `while`, `do-while`, `for`.

### 🔹 Modulo 2: Strutture Dati Lineari (Array e Matrici)
* **Array Monodimensionali (Vettori):** Dichiarazione, inizializzazione, scorrimento e manipolazione degli elementi.
* **Algoritmi Fondamentali:** Ricerca (sequenziale/binaria) e ordinamento (Bubble Sort, Selection Sort).
* **Array Bidimensionali (Matrici):** Uso di cicli annidati, scansione per righe/colonne e diagonali.

### 🔹 Modulo 3: Modularizzazione e Funzioni
* Progettazione top-down e riuso del codice.
* Definizione e chiamata di funzioni, valori di ritorno.
* Passaggio dei parametri: **per valore** vs **per riferimento** (`&`).
* Ambito (scope) delle variabili: locali e globali.

### 🔹 Modulo 4: Stringhe e Puntatori
* Gestione dei testi: `std::string` e principali metodi associati.
* Introduzione all'indirizzamento di memoria: operatori `&` (indirizzo) e `*` (dereferenziazione).
* Puntatori e passaggio di indirizzi alle funzioni.

### 🔹 Modulo 5: Strutture Dati Personalizzate
* Le Strutture (`struct`): aggregazione di dati eterogenei.
* Vettori di strutture e gestione di piccoli archivi dati.

---

## 📂 Struttura della Repository

La repository è organizzata in cartelle corrispondenti ai vari argomenti del corso:

```text
3A_25-26/
├── 01_Fondamenti/
│   ├── InputOutput/
│   └── Selezione_E_Iterazione/
├── 02_Array_e_Matrici/
│   ├── Array1D/
│   ├── Ordinamento_E_Ricerca/
│   └── Matrici/
├── 03_Funzioni/
├── 04_Stringhe_e_Puntatori/
├── 05_Strutture/
└── README.md
