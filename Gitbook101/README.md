# Gitbook 101

## Gitbook gebruik
* `gitbook serve`  
  Runt de [gitbook.io](gitbook.io) output op het lokale machine. Dit is handig
  tijdens het typen, je ziet live de aangemaakte veranderingen verschijnen in de
  browser.
* `gitbook pdf`  
  Genereert een pdf van je gitbook. Het voordeel hierbij is dat
  er een cover word gegenereerd voor je scriptie.

## Opmaak
Gitbook maakt gebruik van markdown files als input. Je moet dus je scriptie in
markdown schrijven.


## SUMMARY.md
De SUMMARY.md file is de inhoudstafel van je Gitbook/scriptie. Alleen de files
die hier instaan worden opgenomen in de Gitbook.

*SUMMARY.md voorbeeld:*
```
# Summary
* [Introductie](./README.md)
* [Gitbook Installatie](GitbookInstallatie/README.md)
* [Gitbook 101](Gitbook101/README.md)
```
> Je kan je hoofdstukken onderverdelen door de indentation van je oplijsting
> aan te passen.

## Cover
* Open het bestand cover.pptx (in powerpoint)
  * Alternatieve hi-res Cover (dank aan Oliver Hofkens): Open het bestand cover.xcf in de gratis, opensource image editor [Gimp](https://www.gimp.org/)
* Vervang "Scriptietitel" door jouw finale scriptietitel.
  * Indien je titel te lang is, gelieve dan manueel een enter toe te voegen. Het lettertype mag maximaal 8pt verkleind worden.
* Vervang "naam student 1, naam student 2" door jouw naam(en) 
* Bewaar het pptx/xcf bestand via Opslaan als naar een "JPEG"-bestand met naam cover.jpg
* Plaats dit nieuwe bestand in de rootmap van je scriptie (daar waar ook SUMMARY.MD staat)
* Deze cover wordt nu automatisch toegevoegd aan je pdf-export van gitbook


## GLOSSARY.md
Je kan termen hier definiëren, wanneer deze termen voorkomen in je scriptie zal
Gitbook automatisch linken naar de uitleg die voorzien is in de glossary. Zie
[hier](http://toolchain.gitbook.com/lexicon.html) in de documentatie voor
verdere details.

