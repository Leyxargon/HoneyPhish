# HoneyPhish Platform

Infrastruttura che individua proattivamente campagne di spam attraverso email honeypot.

## Step di realizzazione

1. Realizzazione di profili fake che saranno oggetto di spam
2. Individuazione dei servizi (tramite fonti di threat intelligence) ai quali registrare le mail fake da utilizzare per la ricezione dello spam
3. Verificare gli IoCs che risultano già stati segnalati come malevoli su fonti OSINT
4. Ricerca automatizzata su piattaforme social (Twitter/Facebook/ecc...) per l'individuazione delle campagne in corso
5. Esplodere eventuali allegato/url su sandbox e recuperarne lo stato, se risultanti malevoli inserirli all'interno di un file di blacklist
6. Realizzazione di un modello per la verifica preliminare della probabilità di spam

## Output previsto

1. Copia dell'infrastruttura implementata
2. Documentazione relativa all'installazione
3. Documentazione per il run

## Piattaforme e software presumibilmente richiesti

- Linux
- Python
- SOAR
- Sandboxing
- Machine Learning
- Protocollo SMTP
