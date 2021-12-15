# ![HoneyPhish Platform](./static/img/logo_nero.png)

Infrastruttura XSOAR che individua proattivamente campagne di spam attraverso email honeypot.

## Installazione

Una volta installata la piattaforma XSOAR, seguire i passaggi:

1. Scaricare l'integration _Mail Listener_ dal marketplace;
2. Nella sezione _integrations_, creare un'istanza inserendo la mail civetta e associare **Phishing (HoneyPhish)** come _Incident type_;
3. Importare il pacchetto ``HoneyPhish Platform.gz`` nella sezione _troubleshooting_;
4. Nella sezione _integrations_, creare un'istanza inserendo una OTI key per _SlashNext_;
5. Creare un job temporale a cadenza giornaliera (_recurring_), associando il playbook **Download URL phishing**;
6. Nella homepage, importare il file ``Dashboard.gz`` per inserire la dashboard;

OPZIONALE

7. Nella sezione troubleshooting, importare il file ``logo_full.png`` in _Full-size logo_ e il file ``logo.png`` in _Minimized logo_.