# CobolDj

## Descrizione del progetto
Un semplice bot per la riproduzione della musica in un canale Discord.

## Installazione

### Prerequisiti:
- Python==3.12.0rc3
- asyncio==3.4.3
- discord.py==2.3.2
- PyNaCl==1.5.0
- python-dotenv==1.0.1
- yt-dlp==2024.4.9

Inoltre, dovrai creare un bot Discord. Per maggiori informazioni, controlla il sito ufficiale di Discord Developer.

### Clonazione del repository
Apri un terminale sul PC e digita il seguente codice per scaricare il progetto:
```bash 
git clone https://github.com/luca-francalacci/discord_cobolDj.git
```
#### Creazione dell'ambiente virtuale
Su **Windows** digita:
```bash
py -m venv .venv
```
Su **iOS/Linux** digita:
```bash 
python3 -m venv .venv
```
#### Attivazione dell'ambiente virtuale
Su **Windows** digita:
```bash
.venv\Scripts\activate
```
Su **iOS/Linux** digita:
```bash 
source .venv/bin/activate
```
#### Installazione delle dipendenze
Sul terminale digita:
```bash 
pip install -r requirements.txt
``` 
Nella cartella principale del progetto, crea un file `.env` e all'interno scrivi:
```DISCORD_TOKEN=la_tua_chiave```
Sostituisci *la_tua_chiave* con la chiave del tuo bot Discord.

## Guida rapida
### Avviare il bot
Attiva l'ambiente virtuale.
Per avviare il bot ti basterà digitare:
**Con Windows**
```bash
py main.py
```
**Con Linux/iOS**
```bash
python3 main.py
```
Aspetta la scritta "*nome del bot* pronto".
Ricordati di abilitare i permessi opportuni al bot.
### Comandi
Connettiti a una chat vocale.
In una chat testuale (dove il bot è abilitato) sarà ora possibile eseguire un comando in base alle necessità.
#### Play
```bash
?play *url_desiderato*
```
La canzone verrà riprodotta in loop.
#### Pausa
```bash
?pause
```
#### Ripartire
```bash
?resume
```
#### Interrompere
```bash
?stop
```

## Licenza
Il bot è utilizzabile da tutta la comunità Discord senza scopo di lucro.

## Miglioramenti
Se desideri contribuire al bot, sarò lieto di accogliere migliorie.

## Contatti
Nome autore: Luca Francalacci  
Email: luca.francalacci@yahoo.it