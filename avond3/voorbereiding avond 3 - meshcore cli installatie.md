
# Installatie meshcore cli
Onderstaand heb je al gedaan op avond 1 van de workshops.
Maar als je nu een andere (Windows) laptop meebrengt, gebruik dan de snelstartgids om je Heltec device te koppelen aan je laptop en te testen. Doe dit voordat je verder gaat met de installatie van python hieronder.

Snelstartgids: https://github.com/VughtseProgrammeerclub/MeshCore_workshop/blob/main/Snelstartgids%20MeshCore%20v01092026.pdf

Download en install python: [https://www.python.org/](https://www.python.org/) 

Kies de python install manager als je nieuw bent met python. (zoniet, dan weet je zelf het beste hoe jouw Python omgeving eruit ziet)

Maak een virtuele omgeving voor Meshcore testen:

cmd.exe : 
- python -m venv meshcore-cli
- cd meshcore-cli
- Scripts\\activate.bat
- pip install meshcore-cli
- testen met: meshcli -V

Krijg je iets terug als "meshcore-cli: command line interface to MeshCore companion radios v1.6.9" dan ben je klaar voor de workshop van avond 3.


Zo ga je weer terug naar de normale Python omgeving:
- deactivate
