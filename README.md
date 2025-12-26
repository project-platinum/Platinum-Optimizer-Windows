# Platinum+ Optimizer 7.0

![Banner](https://images.unsplash.com/photo-1635332306526-788390760459?q=80&w=1200&h=400&fit=crop)

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg?style=for-the-badge)](https://github.com/STEFANO83223/platinum-optimizer)
[![Latest Release](https://img.shields.io/badge/release-v7.0--stable-blue.svg?style=for-the-badge)](./releases/latest)
[![Open Issues](https://img.shields.io/badge/issues-0%20open-success.svg?style=for-the-badge)](https://github.com/STEFANO83223/platinum-optimizer/issues)
[![Last Commit](https://img.shields.io/badge/last%20commit-today-lightgrey.svg?style=for-the-badge)](https://github.com/STEFANO83223/platinum-optimizer/commits/main)

---

## 1. 🚀 Cos'è Platinum+ Optimizer?

**Platinum+ Optimizer 7.0** è uno strumento avanzato di ottimizzazione del sistema Windows, sviluppato per massimizzare le prestazioni hardware attraverso tweak di basso livello del Kernel e del Registro di Sistema. 

Progettato per gamer, creativi e power user, il progetto mira a eliminare i colli di bottiglia del sistema operativo, riducendo drasticamente la latenza di input e stabilizzando il framerate attraverso un'interfaccia testuale intuitiva e potente.

---

## 2. 🛠️ Architettura dei Moduli di Ottimizzazione

Il cuore di Platinum+ Optimizer è diviso in **6 sezioni specializzate**, ognuna progettata per intervenire su un'area critica del sistema operativo. Ecco un'analisi approfondita delle funzionalità offerte:

```text
╔══════════════════════════════════════════════╗
║             PLATINUM+ OPTIMIZER              ║
║                 Version 7.0                  ║
╠══════════════════════════════════════════════╣
║                                              ║
║   [1] CPU PERFORMANCE OPTIMIZATION           ║
║   [2] GPU PERFORMANCE OPTIMIZATION           ║
║   [3] SYSTEM DEBLOATER                       ║
║   [4] SERVICES OPTIMIZER                     ║
║   [5] NETWORK OPTIMIZER                      ║
║   [6] RAM/MEMORY OPTIMIZER                   ║
║                                              ║
╠══════════════════════════════════════════════╣
║   [0] EXIT                                   ║
╚══════════════════════════════════════════════╝
```

### ⚡ [1] CPU Performance Optimization
Questo modulo agisce sulla gestione dei cicli di clock e sulla distribuzione del carico di lavoro. Implementa profili energetici personalizzati che disabilitano il **Core Parking** e regolano l'**Interrupt Moderation**, assicurando che il processore risponda istantaneamente alle richieste delle applicazioni ad alto carico (come giochi o software di rendering) senza cali di frequenza improvvisi.

### 🎮 [2] GPU Performance Optimization
Interviene direttamente sulla pipeline grafica. Oltre a ottimizzare i parametri dei driver (NVIDIA, AMD, Intel), il tool configura il sistema per dare priorità assoluta al rendering della GPU, gestisce la cache degli shader e ottimizza la modalità di gestione dell'alimentazione per garantire il massimo throughput video e ridurre il micro-stuttering.

### 🚫 [3] System Debloater
Windows include numerosi processi e applicazioni "gonfie" che consumano risorse in background. Questo modulo rimuove in modo sicuro la telemetria, disabilita il tracciamento dei dati di Microsoft e pulisce il sistema dalle app preinstallate (UWP) non necessarie, liberando cicli CPU e spazio su disco per un sistema più snello e privato.

### ⚙️ [4] Services Optimizer
Analizza e disabilita i servizi di Windows non essenziali che vengono avviati automaticamente. Riducendo il numero di servizi attivi (come l'Error Reporting, Print Spooler se non necessario, o servizi di diagnostica remota), si riduce l'overhead del kernel, migliorando drasticamente i tempi di avvio e la reattività generale del desktop.

### 🌐 [5] Network Optimizer
Ottimizza lo stack TCP/IP per ridurre la latenza di rete (Ping). Attraverso la disattivazione dell'algoritmo di Nagle e la configurazione avanzata dei parametri di ricezione/invio pacchetti, questo modulo garantisce una connessione più stabile e veloce, ideale per il gaming competitivo online e lo streaming ad alta velocità.

### 🧠 [6] RAM/Memory Optimizer
Gestisce in modo intelligente la memoria ad accesso casuale. Il modulo ottimizza la gestione del **Pagefile**, pulisce la **Standby List** (cache della RAM spesso saturata) e configura il sistema per prevenire il paging eccessivo su disco, assicurando che le applicazioni critiche abbiano sempre accesso alla memoria fisica più veloce disponibile.

---

## 3. 📋 Requisiti di Sistema

Per garantire il corretto funzionamento dei tweak del kernel, il sistema deve soddisfare i seguenti requisiti:

| Componente | Requisito Minimo | Consigliato |
| :--- | :--- | :--- |
| **Sistema Operativo** | Windows 10 (1903+) | Windows 11 (Tutte le versioni) |
| **Architettura** | x64 | x64 con supporto AVX2 |
| **RAM** | 4 GB | 16 GB+ |
| **Permessi** | Privilegi di Amministratore | Accesso Root/System |

---

## 4. 📥 Come installarlo

Il software è distribuito come script batch ultra-ottimizzato. Segui rigorosamente questi passaggi:

### 🛠️ Passaggi per l'installazione
1.  **Download**: Scarica l'ultima release ufficiale [cliccando qui](./releases/latest).
2.  **Estrazione**: Estrai il contenuto in una cartella locale (non su drive di rete).
3.  **Esecuzione**: Fai click destro sul file `PlatinumOptimizer.bat` e seleziona **"Esegui come Amministratore"**.
4.  **Sicurezza**: Inserisci la password di accesso fornita con la tua licenza quando richiesto.

### 💻 Esempio di Configurazione (`config.yaml`)
Puoi pre-configurare l'ottimizzazione per distribuzioni automatizzate:
```yaml
# Platinum+ Auto-Config
optimization_level: "aggressive"
gpu_vendor: "nvidia"
network_boost: true
debloat_telemetry: true
```

### 📸 Screenshot dell'interfaccia
![Screenshot 1](./images/screen1.png)
![Screenshot 2](./images/screen2.png)
![Screenshot 3](./images/screen3.png)

---

## 5. 👥 Crediti

Lo sviluppo e la ricerca dietro Platinum+ Optimizer sono curati da:

*   **@STEFANO83223** - Lead Developer & Engine Architect (Kernel Logic).
*   **@Aledect** - UI/UX Designer & Performance Researcher.
*   **Beta Testing Team** - Ringraziamento speciale ai tester della community.

---

## 6. 📜 Licenza

Copyright © 2024 Platinum+ Optimizer Team.
**LICENZA PROPRIETARIA.**

Questo software è protetto dalle leggi sul copyright. 
*   ❌ È vietata la ridistribuzione non autorizzata.
*   ❌ È vietata la decompilazione o modifica del codice sorgente.
*   ⚠️ L'uso del software è a rischio dell'utente. Gli autori non si assumono responsabilità per danni hardware o perdita di dati derivanti da tweak aggressivi.

---
*Progetto creato con passione per la community del PC Gaming.*
