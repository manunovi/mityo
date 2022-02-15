# MITYO - May I Take Your Order

MITYO è una web-app che permette al cliente di un bar/ristorante di effettuare l'ordinazione comodamente dal telefono, scannerizzando un QR Code posto sul tavolo.

L'app è stata scritta in python, usando il micro-framework Flask, oltre a CSS, JavaScript e HTML per le pagine web. Il database utilizzato è MongoDB.

L'app prevede anche un monitor degli ordini per il personale addetto.

## Installazione

Copiare la repo
```
git clone https://github.com/zPeppOz/mityo
```
Spostarsi nella cartella mityo e creare un virtual environment per Python
```
python3 -m venv venv
```
Una volta attivato il virtual environment, installare le librerie richieste
```
pip install -r requirements.txt
```
Spostarsi nella cartella Flask e far partire il web-server
```
flask run --host 0.0.0.0
```
Così il webserver parte in modo tale da essere raggiungibile su tutta la rete locale, per farlo partire solo sul localhost:
```
flask run 
```

## Uso
Per usare la web-app, basta aprire con un browser l'indirizzo IP della macchina locale su cui è hostato il server, alla porta 5000 (es. 192.168.1.20:5000).
Andando su questo indirizzo, si aprirà una pagina contenente i reindirizzamenti alle pagine del menù, della generazione dei codici QR, e del monitor degli ordini.
---
Progetto Realizzato da Giuseppe Setaro, Emanuele Noviello e Prisco Sorgente, per l'esame di Tecnologie Web del prof. Raffaele Montella.
