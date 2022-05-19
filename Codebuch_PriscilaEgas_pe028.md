# Codebuch

Erhoben wurde die Transfers der Spieler im aktuellen Kader des VfB zum Verein.
Quelle: https://www.transfermarkt.de/vfb-stuttgart/startseite/verein/79
Grundregeln: keine Sonderzeichen, keine Leerzeichen, etc.

## Edgelist

Für Transfer:
from = vorheriger Verein
to = Rückennummer
weight = Transfersumme in 100.000 Euro
season = Transferfenster

Für Nationalität:
from = Rückennummer
to = Land
weight = 0
season = leer


## Nodelist
id = Rückennumer oder Vereinsname
name = Spieler oder Vereinsname
country = Land
type 1 = Spieler, 2 = Verein, 3 = Land
