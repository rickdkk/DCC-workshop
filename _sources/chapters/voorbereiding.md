# 0. Voorbereiding

Er zijn een aantal verschillende manieren om Jupyter te gebruiken.
Zo kan men Jupyter online draaien, bijv. op een cluster van SURF of in [Research Drive](https://wiki.surfnet.nl/pages/viewpage.action?pageId=22413758). 
Je kan het echter ook direct op je eigen computer installeren. Het voordeel is dat je dan leert hoe je het moet 
installeren en dat je het altijd later nog kan gebruiken. Het nadeel is dat het wat werk vooraf vereist. In dit geval 
gaan we voor een lokale installatie.

Om Jupyter te installeren is een installatie van Python nodig. Mac en Linux hebben dat al voorgeïnstalleerd. Daarnaast 
zijn er nog wat losse pakketten nodig, waaronder Jupyter zelf. De meest eenvoudige manier om deze pakketten te 
installeren is met **Miniconda**, wel zo makkelijk!

:::{note}
Het is ook prima om in plaats van Miniconda gebruik te maken van Anaconda of 'gewoon' Python. Kies 
wat voor jou werkt.
:::

## Miniconda installeren

:::{tabbed} Windows
1. Open de website https://docs.conda.io/en/latest/miniconda.html in je browser.
2. Download het bestand `Miniconda3 Windows 64-bit` (of 32-bit op een oude computer).
3. Zoek het bestand in je Downloads map en gebruik dubbel-klik om het bestand te openen.
4. Gebruik voor alles de standaard instellingen.
5. Open `Anaconda Prompt` vanuit het Windows start menu of zoek in de zoekbalk.
6. Test of alles werkt met de volgende commando's:

```shell
python --version
```
Op het moment van schrijven krijg ik hier: `Python 3.9.7`

```shell
conda --version
```
Op het moment van schrijven krijg ik hier: `conda 4.11.0`

Als je geen error krijgt is het goed genoeg!

:::

:::{tabbed} Mac
1. Open de website https://docs.conda.io/en/latest/miniconda.html in je browser.
2. Download het bestand Miniconda3 MacOSX 64-bit pkg\*.
3. Open het bestand en installeer Miniconda met de standaard instellingen.
4. Open een `Terminal` (Klik op Launchpad in het Dock en zoek naar "Terminal" in het zoekveld en klik 
vervolgens op 'Terminal').
5. Test of alles werkt met de volgende commando's:

```shell
python --version
```
Op het moment van schrijven krijg ik hier: `Python 3.9.7`

```shell
conda --version
```
Op het moment van schrijven krijg ik hier: `conda 4.11.0`

Als je geen error krijgt is het goed genoeg!

\*Voor Macs met een M1 architectuur moet je het M1 bestand downloaden. Om die te installeren
kan je naar de instructies voor Linux kijken.
:::

:::{tabbed} Linux
1. Open de website https://docs.conda.io/en/latest/miniconda.html in je browser.
2. Download het bestand Miniconda3 Linux 64-bit (of vergelijkbaar voor jouw architectuur).
3. Voer het bestand uit in de terminal en installeer Miniconda met de standaard instellingen. 
4. Open een nieuwe terminal.
5. Test of alles werkt met de volgende commando's:

```shell
python --version
```
Op het moment van schrijven krijg ik hier: `Python 3.9.7`

```shell
conda --version
```
Op het moment van schrijven krijg ik hier: `conda 4.11.0`

Als je geen error krijgt is het goed genoeg!
:::

## Installeer pakketten

::::::{margin}
:::{Tip}
Je kan het commando kopiëren door je muis boven de code te zetten en op 'Copy to clipboard' te drukken.
:::
::::::

Python kan van zichzelf al heel veel, maar de echte kracht zit in het grote open-source ecosysteem. We gaan een paar
van pakketten uit dat ecosysteem gebruiken in de workshop. Om die te installeren hebben we maar één commando nodig
(moet je eens bedenken hoe lang het zou duren als we voor elk pakket een bestand moesten opzoeken, downloaden en
installeren).
Open de Anaconda Prompt op Windows of de Terminal in MacOS/Linux en run het volgende commando:

```shell
conda install -y -c conda-forge seaborn sympy jupyterlab  
```

## Bestanden

Download de bestanden voor de workshop 👷👷👷hier👷👷👷. Zet de bestanden neer op een voor jou logische plek.
Maak hier bij voorkeur een nieuwe map voor aan waaruit je kan werken tijdens de workshop.