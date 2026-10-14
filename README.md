# 💻 Informatica - Classe Terza A.S. 2025/2026

Benvenuti nella repository ufficiale del corso di **Informatica** per la classe terza (Indirizzo Informatica e Telecomunicazioni). 

Questo spazio funge da **manuale dinamico**, **raccolta di esempi pratici** e **guida agli esercizi** svolti durante l'anno scolastico. Qui troverete tutto il materiale teorico e il codice sorgente scritto in **C++**.

---

## 📌 Indice dei Contenuti

1. [🛠️ Strumenti e Requisiti](#️-strumenti-e-requisiti)
2. [🗺️ Programma Didattico](#️-programma-didattico)
3. [📂 Struttura della Repository](#-struttura-della-repository)
4. [🚀 Linee Guida per il Codice (Style Guide)](#-linee-guida-per-il-codice-style-guide)
5. [📚 Risorse e Documentazione](#-risorse-e-documentazione)

---

## 🛠️ Strumenti e Requisiti

Per seguire il corso e completare i laboratori verranno utilizzati i seguenti strumenti:

* **Linguaggio di Programmazione:** C++ (Standard ISO C++17 / C++20)
* **IDE Consigliati:** 
  * [Visual Studio Code](https://code.visualstudio.com/) (con estensioni *C/C++* e *Code Runner*)
  * [CLion](https://www.jetbrains.com/clion/) (Licenza Education)
  * [Dev-C++](https://sourceforge.net/projects/orwelldevcpp/) (per configurazioni rapide)
* **Compilatore:** `GCC` / `MinGW` (su Windows) o `Clang` (su macOS/Linux)
* **Controllo Versione:** Git & GitHub

---

## 🗺️ Programma Didattico

Il corso si articola nei seguenti moduli:

### 🔹 Modulo 1: Fondamenti e Strutture di Controllo
* Introduzione all'algoritmica e all'ambiente C++ (`iostream`, `std::cin`, `std::cout`).
* Tipi di dato, variabili, costanti e operatori.
* **Strutture di Selezione:** `if`, `if-else`, `switch-case`.
* **Strutture Iterative:** Cicli `while`, `do-while`, `for`.

### 🔹 Modulo 2: Strutture Dati Lineari (Array e Matrici)
* **Array Monodimensionali (Vettori):** Dichiarazione, scorrimento, inserimento, cancellazione.
* **Algorithmi Fondamentali su Array:**
  * Ricerca (Lineare e Binaria).
  * Ordinamento (Bubble Sort, Selection Sort, Insertion Sort).
* **Array Bidimensionali (Matrici):** Uso dei cicli annidati, manipolazione di righe/colonne e diagonali.

### 🔹 Modulo 3: Modularizzazione (Funzioni e Procedure)
* Progettazione Top-Down e Bottom-Up.
* Definizione e chiamata di funzioni.
* Passaggio dei parametri: **per valore** vs **per riferimento** (`&`).
* Scope delle variabili (globali, locali, `static`).
* Ricorsione (concetti base ed esempi).

### 🔹 Modulo 4: Stringhe e Gestione della Memoria
* Differenza tra array di caratteri (C-strings) e `std::string`.
* Manipolazione delle stringhe con le librerie standard.
* Introduzione ai **Puntatori** e all'indirizzamento di memoria (`&`, `*`).
* Allocazione dinamica base con `new` e `delete`.

### 🔹 Modulo 5: Tipi di Dato Definiti dall'Utente
* **Strutture (`struct`):** Aggregazione di dati eterogenei.
* Array di strutture.
* Introduzione all'organizzazione dei file e alla compilazione separata (`.h` e `.cpp`).

---

## 📂 Struttura della Repository

La repository è organizzata in cartelle tematiche:

```text
3A_25-26/
├── 01_Fondamenti/
│   ├── 01_InputOutput/
│   └── 02_SelezioneIterazione/
├── 02_Array_e_Matrici/
│   ├── 01_Array_1D/
│   ├── 02_Ordinamento_Ricerca/
│   └── 03_Matrici/
├── 03_Funzioni/
│   ├── 01_Parametri_Valore_Riferimento/
│   └── 02_Ricorsione/
├── 04_Stringhe_e_Puntatori/
├── 05_Strutture/
└── README.md# terze
