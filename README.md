# backend.py
esercizio vacca

Questo progetto contiene un piccolo backend in Python che espone via HTTP (porta 80) il nome host della macchina su cui è in esecuzione.

Prerequisiti Python 3.6 o superiore

Git

Accesso con permessi di root o sudo per bindare la porta 8080

Installazione e configurazione Clona il repository sul tuo sistema

bash git clone git@github.com:TUO_USERNAME/hostname-backend.git cd hostname-backend Crea un ambiente virtuale

bash python3 -m venv venv Attiva l’ambiente virtuale

bash source venv/bin/activate Installa le dipendenze

bash pip install flask Avvio del server Avvia il backend sulla porta 80. Serve sudo (o root) per bindare la porta privilegiata:

bash sudo python3 backend.py
