
#Gitbook Installatie  

Je scriptie moet geschreven worden in markdown en dient steeds ook naar een pdf
geconverteerd te worden. We gaan hier voor
[GitBook](https://github.com/GitbookIO/gitbook) gebruiken (zie voorbeeld in  je
studentrepo in de map Scriptie)

## Vereisten 

Om te kunnen werken met Gitbook zijn er volgende programma's nodig:
* node.js
* npm
* git

## Gitbook Installatie

Gitbook is een node.js package die je eenvoudig met npm kan installeren. Voer
hiervoor volgend commando uit: 

`npm install gitbook-cli -g`

Als dit klaar is is GitBook  geïnstalleerd.

Lees vervolgens [de documentatie](http://toolchain.gitbook.com/). Pas op
Gitbook voorziet 2 documentaties. Een is voor de Gitbook Toolchain, het geen
dat je nu gaat gebruiken en een voor de Gitbook hosting website.

## Gitbook gebruiken
Om aan je scriptie te starten moet je als eerst een lokale clone maken van
BAP/Stage GitHub Classroom Repo. Navigeer daarna na map waar de repo is
gecloned en voor volgende commando uit: 

`gitbook serve` 

Nu word de Gitbook output (html website) gehost op je computer en kan je de
pagina bezoeken op [localhost:4000](localhost:4000). Je kan dan live de
aanpassing aan je scriptie volgen.

Je kan ook de PDF generen met volgend commando:

`gitbook pdf`



