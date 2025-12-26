# Platinum+ Optimizer 7.0

![Banner](https://images.unsplash.com/photo-1635332306526-788390760459?q=80&w=1200&h=400&fit=crop)

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg?style=for-the-badge)](https://github.com/platinum-plus/optimizer)
[![Latest Release](https://img.shields.io/badge/release-v7.0--stable-blue.svg?style=for-the-badge)](./releases/latest)
[![Open Issues](https://img.shields.io/badge/issues-0%20open-success.svg?style=for-the-badge)](https://github.com/platinum-plus/optimizer/issues)
[![Last Commit](https://img.shields.io/badge/last%20commit-today-lightgrey.svg?style=for-the-badge)](https://github.com/platinum-plus/optimizer/commits/main)

## 💎 Il Massimo Potenziale del Tuo Sistema

**Platinum+ Optimizer 7.0** è uno strumento di ottimizzazione di sistema di livello enterprise, progettato da **@STEFANO83223** e **@Aledect**. A differenza dei tool commerciali, Platinum+ opera direttamente a livello di **Registro di Sistema** e **Kernel**, applicando tweak avanzati utilizzati dai professionisti dell'overclocking e della bassa latenza.

Il core del software è un motore batch ultra-ottimizzato che bypassa le limitazioni standard di Windows per garantire frame rate stabili, latenza di input nulla e una gestione intelligente della memoria RAM.

---

## 📥 Installazione e Accesso

L'optimizer è protetto per prevenire l'esecuzione accidentale. Segui questi passaggi:

### ⚙️ Prerequisiti
1. Scarica l'ultima versione: [Scarica qui](./releases/latest)
2. Esegui il file come **Amministratore**.
3. Inserisci la chiave di accesso quando richiesto dal prompt PowerShell sicuro.

### 💻 Esecuzione Rapida (CLI)
Puoi installare le dipendenze kernel tramite terminale:
```powershell
# Esegui per preparare i driver grafici
reg add "HKLM\SYSTEM\CurrentControlSet\Control\GraphicsDrivers" /v "ForceDirectFlip" /t REG_DWORD /d 1 /f
```

---

## 🔥 Funzionalità Principali

*   **⚡ CPU Extreme Optimization**: Profili dedicati per **Intel** e **AMD**. Include la disabilitazione del Core Parking, l'ottimizzazione del cache kernel e il boost forzato della priorità Win32.
*   **🎮 GPU Performance Module**: Supporto completo per NVIDIA, AMD e Intel.
    *   *Safe Mode*: Ottimizzazioni stabili per uso quotidiano.
    *   *Aggressive Mode*: Tweak estremi come la disabilitazione del Dynamic P-State e l'attivazione del polling MSI (Message Signaled Interrupts).
*   **🧠 RAM/Memory Master**: Pulizia profonda delle cache di sistema, gestione del Pagefile e ottimizzazione del throughput I/O per prevenire lo stuttering.
*   **🌐 Network Latency Killer**: Ottimizzazione dei parametri TCP/IP, disabilitazione dell'algoritmo di Nagle e flush DNS automatico per il gaming competitivo.
*   **🚫 System Debloater**: Rimozione aggressiva della telemetria Microsoft, disattivazione di servizi superflui (Print Spooler, Bluetooth, WiFi se non necessari) per liberare cicli CPU.

---

## 🛠️ Configurazione Avanzata

Personalizza l'esperienza modificando il file `config.yaml` o utilizzando i flag CLI integrati.

### Esempio di config.yaml
```yaml
# Platinum+ Core Config
system:
  cpu_architecture: "intel" # o "amd"
  aggressive_gpu: true
  force_max_power: true
  
cleanup:
  clear_temp_on_start: true
  disable_telemetry: true
```

### Comandi Avanzati
```bash
# Applica solo l'ottimizzazione RAM
platinum-opt --ram-only

# Ripristina i servizi di sistema originali
platinum-opt --restore-defaults
```

---

## 📸 Screenshots

![Main Menu](https://picsum.photos/seed/platinum1/800/450)
*Interfaccia testuale v7.0 con menu di selezione moduli.*

![GPU Tweaks](https://picsum.photos/seed/platinum2/800/450)
*Pannello di controllo per le ottimizzazioni NVIDIA e AMD.*

![System Analysis](https://picsum.photos/seed/platinum3/800/450)
*Monitoraggio delle risorse post-ottimizzazione.*

---

## 📋 Compatibilità e Requisiti

| Componente | Requisito Minimo | Consigliato |
| :--- | :--- | :--- |
| **Sitema Operativo** | Windows 10 (Build 1903+) | Windows 11 (Tutte le versioni) |
| **Processore** | Qualsiasi Intel/AMD x64 | Supporto AVX2 abilitato |
| **Permessi** | Privilegi di Amministratore | Controllo Account Utente (UAC) disattivato |

---Personalizza l'esperienza modificando il file config.yaml o 

## 👥 Crediti e Sviluppo

Il progetto è attivamente mantenuto da:
*   **@STEFANO83223** - Lead Engine Developer & Kernel Logic.
*   **@Aledect** - UI/UX Batch Designer & Optimization Researcher.

---

## 📜 Licenza e Note Legali

Copyright © 2024 Platinum+ Optimizer Team.
**PROPRIETARY SOFTWARE.** Tutti i diritti riservati.

Questo software viene fornito "così com'è". Gli autori non sono responsabili per eventuali danni causati da un uso improprio dei tweak aggressivi. La ridistribuzione non autorizzata del codice è vietata.
