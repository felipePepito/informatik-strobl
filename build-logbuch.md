# Build-Logbuch informatik-strobl Webpage

## Installation
Installation von Composer, PHP 7.3, symfony
Aktivierung von PHP-Paketen
Alles über offizielle Paketquellen

`symfony check:requirements`

## Symfony Projekt erstellen
`symfony new informatik-strobl`

Erstellt ein minimales Projekt

## WebStorm konfigurieren
Download / Aktivieren von Plugins..
* Symfony Plugins, 
* Composer Plugins, 
* PHP Annotations, 
* PHP Toolbox

## Server, Annotationen per Composer installieren
`composer require server`
Keine Ahnung was das soll..

`composer require annotations`

`composer require sec-checker --dev`
Ein Symfony Plugin um Security Checks durchzuführen.

## Server starten
Aus dem Symfony Verzeichnis heraus..

`symfony server:start`

## git
./idea zu .gitignore hinzufügen

`git push https://github.com/felipePepito/informatik-strobl master`

## Routes / Controller hinzufügen
Eine Klasse in **Controller** erstellen, die Funktion entsprechend mit Annotationen versehen.

### Slugs
Routes kann man mit `{slug}`s versehen (Wildcard routes) 

## Flex

### Flex Aliases
Anstatt vendor/package kann man auch direkt irgendein alias für ein package verwenden, gelistet auf *symfony.sh*

### Flex Recipies
Ein Weg, um andere Bundles zu integrieren.

Ein recipie Fügt Composer-Komponenten hinzu, updatet symfony.lock und kann gleichzeitig auch Dateien im Projekt hinzufügen / ändern, um das Bundle einzufügen.
