
# Installatie meshcore cli
Onderstaand heb je al gedaan op avond 1 van de workshops.
Maar als je nu een andere (Windows) laptop meebrengt, gebruik dan de [Snelstartgids](../Snelstartgids%20MeshCore%20v01092026.pdf) om je Heltec device te koppelen aan je laptop en te testen. Doe dit voordat je verder gaat met de installatie van python hieronder.

Download en install python: [https://www.python.org/](https://www.python.org/) 

Kies de python install manager als je nieuw bent met python. (zoniet, dan weet je zelf het beste hoe jouw Python omgeving eruit ziet)
En installeer python.

Maak een virtuele omgeving voor Meshcore testen:

Druk op Windows Toets + R en type `cmd`, druk op Enter. Type in dit Command window: 
1. `python -m venv meshcore-cli`
2. `cd meshcore-cli`
3. `Scripts\\activate.bat`
4. `pip install meshcore-cli`
5. testen met: `meshcli -V`

Krijg je iets terug als "meshcore-cli: command line interface to MeshCore companion radios v1.6.9" dan ben je klaar voor de workshop van avond 3.


Zo ga je weer terug naar de normale Python omgeving:
- `deactivate`
