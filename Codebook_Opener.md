## Codebook: Opener

**edgelist**
from:	Opener
to: Headliner
relationship:	1 = war Opener auf Konzert  / 2 = auf Tour / 3 = früheres Bandmitglied
tour:	1= nationale / 2 = internationale 
stops:	Anzahl der Tourstops

**nodelist**
id:	Die ersten zwei Buchstaben jeweils eines Namens (Bruno Mars: Brma); bei einem Namen die ersten vier (Shakira: shak)
name:	aktueller Künstlername
listeners:	monatliche Hörer*innenzahl auf Spotify zum Zeitpunkt der Datenerhebung
alive:	1 = Ja / 2 = Nein
nationality:	Herkunft der Künstlerin/des Künstlers
band:	1 = Ja / 2 = Nein
genre:	1 = Pop / 2 = Hiphop / 3 = Rock / 4 = Country / 5 = Latin / 6 = Sonstiges
grammy wins:	Wie viele Grammys (egal welcher Kategorie) hat die Person gewonnen
grammy nominations: Für wie viele Grammy (egal welcher Kategorie) war die Person nominiert
vma wins:	Wie viele VMAs (egal welcher Kategorie) hat die Person gewonnen
vma nominations: Für wie viele VMAs (egal welcher Kategorie) war die Person nominiert
ema wins:	Wie viele EMAs (egal welcher Kategorie) hat die Person gewonnen
ema nominations: Für wie viele EMAs (egal welcher Kategorie) war die Person nominiert
billboard hot 100 peak: Der höchste jemals erreichte Platz auf der Billboard Hot 100 Liste
billboard 200 peak: Der höchste jemals erreichte Platz auf der Billboard 200 Liste
höchste riaa-zertifizierung: 1 = Gold / 2 = Platin / 3 = Multi-Platin / 4 = Diamant
headliner:	1 = Headliner / 2 = Opener / 3 = beides

NA:	definiert fehlende Werte, bei der Datenerhebung das Feld einfach leer lassen, R rechnet NAs (missing values) automatisch raus