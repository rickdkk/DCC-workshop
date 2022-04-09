# 1. Notebooks

Een Jupyter Notebook is een open source digitaal document en ontwikkelomgeving die gebruikers in staat stelt om data en 
code te combineren met een verhaal. Notebooks worden al sinds jaar en dag gebruikt om de opzet en uitkomsten van experimenten 
bij te houden en te communiceren met collega's. Met Jupyter wordt het idee van de fysieke Notebook omgezet naar de
digitale wereld.

:::{figure} ../figures/moons-of-jupyter.png
:width: 50%
Galileo's manuscript uit 1610 met observaties van Jupyter ([Public Domain](https://en.wikipedia.org/wiki/File:Galileo_Galilei_(1564_-_1642)_-_Serenissimo_Principe_-_manuscript_with_observations_of_Jupiter_and_four_of_its_moons,_1610.png)).
:::

## Waarom notebooks?

Computational narrative

Stukje geschiedenis

Reproduceerbaarheid, samenwerken, herbruikbaarheid

:::{figure} ../figures/reproduciblejourney.svg
Reproduceerbaarheid door het delen van data, tools, code, en resultaten[^journey]
:::

## Waarom Jupyter?

Een groot voordeel van Jupyter is dat het vrij en open source beschikbaar is. Hierdoor kan iedereen het installeren
en kan dus ook iedereen met jouw project aan de slag. Dit is een groot voordeel ten opzichte van de grote spelers in het
veld die voordat Jupyter actief was ook een Notebook variant aanboden. Om maximaal transparant te zijn is het belangrijk
dat iedereen je data en code in kan zien en kan testen, zonder afhankelijk te zijn van dure licenties.

Een ander voordeel is dat het te gebruiken is met meerdere programmeertalen. Het is zelfs mogelijk om binnen één Notebook
meerdere talen te combineren. In praktijk worden Jupyter Notebooks het meest gebruikt in combinatie met de open source
programmeertaal Python.

Tot slot is Jupyter simpelweg het meest populaire format. Het voordeel hiervan is dat er veel tooling rondom Jupyter
ontwikkeld wordt. Er is daardoor ook veel hulp beschikbaar op het internet. In andere woorden: het heeft een grote
community.

:::{figure} ../figures/jupyter-logo.svg
:width: 30%
:::

## Wat kan ik er mee?

In een (Jupyter) Notebook kan je verschillende elementen combineren om je data, tools, code, resultaten, en verhaal te 
delen. In het bovenstaande voorbeeld zie je twee notebooks uit de documentatie van Jupyter. Hierin zie je onder andere
uitleg, formules, en code terugkomen. Door met de sliders te schuiven veranderd de afbeelding. Het vormt een krachtige
manier om je analyses te communiceren. 

- **Code:** Jupyter ondersteund tientallen programmeertalen.
- **Text:** Jupyter ondersteund markdown en HTML om je tekst mee op te maken.
- **Formules:** Door gebruik te maken van LaTeX kan je formules toevoegen.
- **Plots:** Met (interactieve) plots kan je inzicht geven in je data.
- **Media:** Afbeeldingen, video's, en audio kunnen allen verwerkt worden.
- **Widgets:** Met interactieve widgets krijgen mensen echt gevoel voor je data.

:::{figure} ../figures/notebook_examples.png
Jupyter Notebooks in Jupyter Lab.
:::

## Hoe werkt het?

Als we het hebben over Jupyter dan spreken we grofweg over drie verschillende onderdelen:
- **Notebooks:** De Notebooks zelf bevatten alle informatie die ook zichtbaar is in de Jupyter applicatie. Alle input,
output, berekeningen, en afbeeldingen staan opgeslagen in de Notebook file.
- **Jupyter Notebook/Lab:** Jupyter Notebook en Jupyter Lab zijn de applicaties gemaakt door Project Jupyter om Notebooks
mee op te maken. Het zijn dus programmeeromgevingen en staan los van het Notebook format.
- **Kernels:** Het onderdeel dat de code daadwerkelijk gaat uitvoeren en het resultaat teruggeeft aan de web applicatie. 
Elke notebook heeft een eigen kernel. Jupyter ondersteund tientallen programmeertalen, waaronder Julia, Python, en R 
(mede daarom ook de naam Jupyter).

Het mooie van deze modulaire aanpak is dat de kernel en de server op je eigen computer kunnen draaien of, bijvoorbeeld,
op een supercomputer. Vervolgens kan je via je browser aan de slag alsof je op je eigen systeem werkt.

:::{figure} ../figures/notebook_components.png
:width: 90%
De Jupyter Notebook Interface[^jupyter-docs].
:::

## Hoe kan ik mijn werk delen?

Jupyter Notebooks zijn perfect om je werk mee te communiceren, maar niet iedereen heeft Jupyter op hun pc staan. Daarom
zijn er verschillende manieren om Notebooks te delen:
Notebooks kunnen worden geëxporteerd naar HTML, reStructuredText, LaTeX, PDF, boeken (jupyter book), slide shows 
(reveal.js), en meer met nbconvert. Notebooks kunnen ook makkelijk gedeeld worden via nbviewer of GitHub/GitLab. 
Deze zijn allen in staat het notebook te renderen, zonder dat iemand hiervoor nog Jupyter Notebook hoeft te installeren.
- **nbconvert:** Notebooks kunnen worden geëxporteerd naar HTML, PDF, LaTeX, etc.
- **nbviewer:** Notebooks kunnen worden weergeven op <https://nbviewer.org/> of direct op GitHub en GitLab.
- **Voilà:** Notebooks met widgets kunnen als dashboard worden gebruikt, hiermee is je data interactief te bekijken.
- **Binder:** Een hele omgeving kan gedeeld worden voor maximale reproduceerbaarheid.
- **Slideshows:** Met reveal.js kunnen Notebooks omgezet worden naar een slideshow. Met RISE kan je code in je slides
live uitvoeren.
- **jupyterbook:** Meerdere Notebooks kunnen worden omgezet naar een boek dat offline (PDF) of online (deze site) te
bekijken is.

:::{figure} ../figures/reproducible_logbook.png
Reproduceerbare wetenschap met Jupyter en Binder[^jupyter-docs].
:::

## Hoe ziet dit eruit?

Jupyter had een grote 'moment of fame' toen de uitkomsten van de LIGO gravitational waves studie werden gedeeld met Jupyter 
Notebooks. Je kan met de data van LIGO oefenen in Jupyter op hun website <https://www.gw-openscience.org/tutorials/>.

Een ander mooi voorbeeld is een Notebook van Peter Norvig (Director of Research bij Google): [The Traveling Salesperson Problem](https://nbviewer.org/url/norvig.com/ipython/TSP.ipynb)
over een klassiek probleem in de computerwetenschappen. 



[^journey]: The Turing Way Community, & Scriberia. (2021). Illustrations from the Turing Way book dashes. Zenodo. https://doi.org/10.5281/zenodo.5706310
[^Taka]: Juliette Taka, & Nicolas M. Thiéry. (2018). Publishing reproducible logbooks explainer comic strip. Zenodo. https://doi.org/10.5281/zenodo.4421040
[^jupyter-docs]: https://docs.jupyter.org/en/latest/projects/architecture/content-architecture.html
