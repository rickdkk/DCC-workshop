# 2. Jupyter Lab

Jupyter Lab is een grafische omgeving waarmee we Jupyter Notebooks kunnen opmaken. 

## Opstarten

Om Jupyter Lab te starten moeten we het volgende commando in de Anaconda Prompt gebruiken:

```shell
jupyter lab
```

Vervolgens komt er een hele hoop tekst voorbij en opent er een nieuw tabblad in je browser (bijv. 
Firefox of Chrome). Als de browser niet opent kan je ook handmatig naar de URL <http://localhost:8888/lab>
gaan. Als het goed is zie je (na een tijdje) de Jupyter Lab interface.

## Vogelvlucht

Het eerste wat je ziet als je Jupyter Lab opstart is de **Launcher**. Vanuit hier kan je een Notebook
aanmaken, maar ook andere documenten zoals Text Files of Markdown Files. Het is ook mogelijk om een 
Terminal te starten. Als je bijvoorbeeld R of Julia hebt geïnstalleerd, dan kan je ook die kernels aanklikken.
In beide gevallen moet je nog wel eerst een los pakket installeren.

Bovenin zie je een klassieke **Menu Bar** met 'File', 'Edit', 'View', enzoverder. Het menu is vrij standaard en spreekt redelijk 
voor zich.

Aan de linkerkant staat de 'side bar' met de **File Browser**. Hierin zie je de documenten en mappen in de map waarin je Jupyter
Lab hebt opgestart. 

De optie onder de mappen zijn die van de **Running Terminals and Kernels**. Hier zie je welke programmeeromgevingen
je allemaal hebt open staan in Jupyter. Je kan ze vanuit hier het overzicht houden en waar nodig een programma stoppen.

Daaronder staat de **Table of Contents**. Als we straks kopjes toe gaan voegen in een notebook, kan je hier de structuur
van het document zien en navigeren.

Het laatste kopje is de **Extension Manager**. We kunnen extra functionaliteiten toevoegen met extensies. Een goed voorbeeld 
is de jupyterlab-git extensie die zorgt dat versiebeheer via Jupyter Lab kan. Dat gaan we vandaag niet doen, maar het is 
wel een krachtige toevoeging!

Tot slot zien we onderin nog de **Status Bar**. Hier vinden we straks nuttige informatie over onze notebook. 

## Cellen

Laten we nu eerst een Notebook openen. Klik in de Launcher op de Python 3 Notebook. Als het goed is zie je nu een
relatief leeg scherm met één cell. Bovenin staat Untitled.ipynb. De `.ipynb` extensie wordt gebruikt om notebooks aan te 
geven. De data in het bestand zelf is tekst bestand in de vorm van een JSON file.

### Command en edit mode

Als je nu rechts onderin kijkt op de Status Bar zie je dat we in **Command Mode** zitten. In deze modus kunnen we cellen 
toevoegen, verwijderen, en verplaatsen. Als je nu op `Enter` drukt kom je in de **Edit Mode**. Nu kan je wat typen in de 
cell. 

### Code cellen
Traditiegetrouw zullen we het volgende commando als eerst runnen:

```python
print("Hello world")
```

Typ het commando in de cell en druk op `Shift + Enter`, hiermee run je de code en maak je direct een nieuwe cell aan.

Zoals je ziet krijg je de output van de code direct onder de cell. Om aan te geven dat de cell is uitgevoerd en wanneer
deze is uitgevoerd komt er een getal voor te staan.

### Markdown cellen

De tweede belangrijke soort cellen zijn 'markdown cellen'. Deze worden gebruikt om tekst toe te voegen aan de Notebook.
Markdown is een tekstformat om documenten mee op te maken. Het voordeel van markdown is dat het erg veel lijkt op platte
tekst, op veel plekken te gebruiken is, en in een avond te [leren](https://www.markdownguide.org/basic-syntax/) is.
Het document dat je nu voor je hebt, is ook geschreven in markdown!

Om een markdown cell toe te voegen moeten we eerst naar Command Mode met `Esc`. We kunnen de cell omzetten naar een markdown
cell door bovenin het uitklapmenu aan te klikken of door de shortcut `m` in te drukken. Door weer op `Enter` te drukken 
komen we met onze cursor weer in Edit Mode. Kopieer de volgende tekst losse cellen en voer deze uit:

```markdown
# Heading 1

## Heading 2

### Heading 3
```
```markdown
Deze zin bevat **dikgedrukte text**.

Deze zin bevat *schuingedrukte tekst*.

Deze zin bevat ~~doorgestreepte tekst~~.
```
```markdown
> Deze workshop gaat me tot nu toe echt goed af!
```
```markdown
$log_b(xy) = log_b(x) + log_b(y)$

$F = G \frac{m_1m_2}{r^2}$

$e^{i\pi} + 1 = 0$

$g(x) = \int_0^\infty e^{-y^2} \, dy$
```
```markdown
1. Eerste item
2. Tweede item
3. Derde item
4. Vierde item 
```
```markdown
De workshop staat [Hier](https://rickdkk.github.io/DCC-workshop/).

![Logo van het DCC](https://rickdkk.github.io/DCC-workshop/_static/logo_dcc.png)
```

Kwam er uit wat je had verwacht?

## Snelkoppelingen

We hebben net de belangrijkste snelkoppelingen al voorbij zien komen. De meeste snelkoppelingen zijn bedoeld voor de
Command Mode. Hieronder vind je de belangrijkste snelkoppelingen:

| Snelkoppeling   | Modus   | Actie                               |
|-----------------|---------|-------------------------------------|
 | `Enter`         | Command | Activeer Edit Mode                  |
| `Escape`        | Edit    | Activeer Command Mode               |
| `a`             | Command | Voeg een cell boven toe             |
| `b`             | Command | Voeg een cell onder toe             |
| `dd`            | Command | Verwijder een cell                  |
| `z`             | Command | Herstel een cell                    |
| `c/v/x`         | Command | Kopiëren/Plakken/Snijden            |
| `Ctrl + Enter`  | Edit    | Voer de cell uit                    |
| `Shift + Enter` | Edit    | Voer de cell uit en maak een nieuwe |

Alle snelkopelingen zijn terug te vinden in de **Advanced Settings Editor** (`Ctrl + ,`) en staan achter alle commando's
in de menu's zelf. 