# Wi-Fi Spoofing – Simulazione di un attacco Man in the Middle

## Descrizione del progetto

Il progetto, realizzato nell'ambito di un'attività accademica di Cybersecurity, approfondisce il funzionamento degli attacchi **Man in the Middle (MiTM)**, con particolare attenzione alle tecniche di Wi-Fi Spoofing e all'intercettazione del traffico di rete.

L'obiettivo è comprendere come un attaccante possa inserirsi nella comunicazione tra un client e un server, intercettando informazioni potenzialmente sensibili, e analizzare le principali contromisure per proteggere le comunicazioni.

Il lavoro combina una parte teorica di approfondimento sulle tecniche di attacco con una dimostrazione pratica condotta in un ambiente controllato.

## Obiettivi

- Comprendere il funzionamento dell'autenticazione HTTP Basic.
- Approfondire il concetto di attacco Man in the Middle.
- Analizzare le tecniche di ARP Spoofing e DNS Spoofing.
- Simulare uno scenario di Wi-Fi Spoofing in ambiente controllato.
- Osservare e analizzare il traffico di rete.
- Individuare le vulnerabilità legate alla trasmissione di credenziali tramite HTTP.
- Approfondire le principali strategie di protezione.

## Metodologia e dimostrazione pratica

Il progetto si è articolato in diverse fasi:

### 1. Preparazione dell'ambiente

Creazione di un sito web locale tramite **XAMPP**, utilizzato come ambiente di prova per la dimostrazione pratica.

### 2. Simulazione dell'attacco

Realizzazione di una simulazione di Wi-Fi Spoofing attraverso un hotspot, con accesso al sito precedentemente creato.

### 3. Intercettazione e analisi del traffico

Utilizzo di **Wireshark** per monitorare il traffico di rete e individuare i pacchetti HTTP generati durante la comunicazione.

In particolare, è stato analizzato un pacchetto GET contenente credenziali di accesso codificate in Base64.

### 4. Decodifica delle credenziali

Utilizzo di **CyberChef** per decodificare la stringa Base64 e visualizzare le credenziali in chiaro, evidenziando i rischi associati alla trasmissione di informazioni tramite HTTP non cifrato.

## Strumenti utilizzati

- **XAMPP** – creazione e gestione del server web locale.
- **Wireshark** – intercettazione e analisi del traffico di rete.
- **CyberChef** – decodifica di stringhe Base64.
- **Hotspot Wi-Fi** – ambiente utilizzato per la simulazione.

## Contromisure e sicurezza

Il progetto approfondisce inoltre alcune strategie per prevenire o ridurre i rischi legati agli attacchi di rete:

- **HTTPS:** cifratura delle comunicazioni tra client e server.
- **VPN:** protezione del traffico attraverso una connessione cifrata.
- **Autenticazione a più fattori (MFA):** maggiore protezione degli account.
- **Monitoraggio della rete:** individuazione di attività sospette e dispositivi non autorizzati.
- **Firewall:** controllo degli accessi alla rete.
- **DNSSEC:** verifica dell'autenticità delle risposte DNS.

## Materiali del progetto

All'interno del repository sono disponibili:

- Documentazione del progetto in formato PDF.
- Video dimostrativi della preparazione dell'ambiente
