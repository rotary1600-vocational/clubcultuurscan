# Clubcultuurscan

Rapportgenerator voor de clubcultuurscan van de Commissie Vocational Service,
Rotary District 1600.

**Gepubliceerde versie:** https://ORGANISATIE.github.io/clubcultuurscan/

## Wat dit is

Eén HTML-bestand dat van de antwoorden op de clubcultuurvragenlijst een rapport
maakt. Alle verwerking gebeurt in de browser van de gebruiker: er wordt niets
verzonden en niets opgeslagen. De pagina werkt ook zonder internetverbinding.

## Voor clubs

Een club heeft twee links nodig:

1. de kopieerlink van het Google-formulier, waarmee de club een eigen exemplaar maakt;
2. de link hierboven, waarmee de contactpersoon na afloop het rapport maakt.

De vragenlijst mag niet worden aangepast: de generator herkent de vragen op tekst,
en alleen een ongewijzigde lijst maakt vergelijken over de jaren mogelijk.

## Voor beheerders

Alles wat instelbaar is, staat in het blok `CONFIG` bovenin `index.html`:
de vragen en hun themaindeling, de bandgrenzen, de drempelwaarden, de
duidingbibliotheek van 24 teksten, en alle vaste rapportteksten. De logica
daaronder hoeft niet gewijzigd te worden.

Een wijziging doorvoeren: pas `index.html` aan, commit, en GitHub Pages
publiceert de nieuwe versie binnen een minuut. Clubs die de link openen,
krijgen vanaf dat moment de nieuwe versie.

De volledige documentatie — functionele specificatie, duidingbibliotheek,
begeleidingsdocumenten voor de ledenavond — staat in de werkmap van de commissie.

## Eigendom

Ontwikkeld door Robert Teunissen voor de Commissie Vocational Service,
Rotary District 1600. Uitsluitend voor gebruik door Rotaryclubs.
