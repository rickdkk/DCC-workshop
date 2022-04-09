# Research Drive

Je kan Jupyter op je eigen computer gebruiken óf direct vanuit Research Drive (Pilot) met Jupyter Hub. Om Jupyter Hub te 
starten moet je op het Jupyter logo klikken in het menu van Research Drive. 

## Stappenplan

**Stap 1: klik op Jupyter Hub in het Research Drive menu (linksboven)**

:::{figure} ../figures/RD_select.png
:width: 50%
:::

:::{Note}
Het kan zijn dat de optie bij jou (nog) niet beschikbaar is. Via het Research Drive Dashboard kan een Research Drive 
administrator de service voor een specifiek account aanzetten. Overleg dus met je Data Steward. 
:::

**Stap 2: kies een notebook configuratie**

Men krijgt nu een aantal opties voor de omgeving in het ‘spawner’ scherm. Hier kun je kiezen uit verschillende 
configuraties voor je Notebooks (op volgorde van aantal features):
-    Minimal notebook: minimale container
-    R Notebook: met R en de tidyverse
-    DataScience Notebook: met Python, R, Julia, én voorgeïnstalleerde pakketten

:::{figure} ../figures/RD_spawner.png
:::

Elke container krijgt 2 cores en 2GB werkgeheugen. Als je niet weet welke je nodig hebt kan je het beste kiezen voor de 
`DataScience Notebook`, deze heeft de meeste features. Zit jouw favoriete pakket er niet tussen? Geen probleem, via de 
terminal of een notebook kun je altijd nog meer pakketten of een specifieke versie van een pakket installeren. Het is 
dan wel handig om de uiteindelijke configuratie op te slaan, bij het opnieuw opstarten van een server ben je de oude 
configuratie kwijt.

Vervolgens krijg je een standaard Jupyter Notebook omgeving te zien, dat is een iets oudere omgeving dan Jupyter Lab. 
Voor wie bekend is met Jupyter is dit een vertrouwde omgeving. Je kunt in deze map notebooks aanmaken, maar de map 
verdwijnt weer als je Jupyter sluit! Daarom is het verstandig om je notebook aan te maken in een map op Research Drive 
zelf. Klik dus eerst op de map ‘work’ en kies daarna een locatie op jouw Research Drive:

:::{figure} ../figures/RD_jupyter.png
:::


**Stap 3: maak een notebook aan**

Navigeer in de notebook omgeving naar de gewenste map in jouw Research Drive en maak een nieuwe notebook aan door te 
klikken op `New` en de kernel te selecteren die jij wilt (bijv. Python 3).
:::{figure} ../figures/RD_kernel.png
:width: 60%
:::

**Stap 4: test of alles werkt**

:::{figure} ../figures/RD_test.png
:::
