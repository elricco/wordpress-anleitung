# Seitenstruktur anlegen

Um eine Seitenstruktur in der Seitenübersicht aufzubauen ist es am einfachsten diese in Abständen von Zehnerschritten anzulegen und sie direkt in die richtige Reihenfolge einzuordnen. Wie wird das gemacht?

Beim "Erstellen" von Seiten kann man die Attribute einer Seite einstellen. Diese bestehen aus "Eltern", "Template" und "Reihenfolge". "Template" können wir an dieser Stelle vernachlässigen.

Ein weiterer Vorteil, bei entsprechend eingestellten "Permalinks", es lassen sich ordentliche "sprechende URLs" erstellen durch eine ordentliche Eltern-Kategorisierung.

## Reihenfolge in Zehnerschritten

Wir legen es so an, damit die vorher festgelegte Seitenstruktur ebenfalls in Wordpress, zur einfacheren Orientierung, hinterher angezeigt wird. Zudem erlauben uns die Zehnerschritte später weitere Seiten in die Struktur einzufügen ohne die Reihenfolge jeder Seite neu einzustellen.

### Konvention

Startseite bekommt immer die 0 \(bitte hierbei später auf SEO Einstellungen achten\)

Jede weitere Seite wird anschließend mit aufsteigenden 10er Schritten angelegt. Gibt es z.B. eine Seite Team wird im Attribut "Reihenfolge" der Seite die 10 eingetragen. Gibt es eine weitere Seite z.B. Produkte wird bei der Reihenfolge eine 20 eingetragen usw.

Seiten die man später -sehr wahrscheinlich- nur selten einstellen muss, legen wir direkt mit einer sehr hohen Nummer an.

* Impressum - 10000
* Datenschutz - 9990
* Allgemeine Geschäftsbedingungen - 9980 \(Titel ausschreiben für SEO\)
* Nutzungsbedingungen - 9970
* usw.

## Das Attribut "Eltern"

Durch das Attribut "Eltern" lassen sich Unterseiten erstellen. Im Attribut Eltern kann festgelegt werden, zu welcher Hauptkategorie eine Seite gehört. Man kann beliebig viel Unterebenen erstellen, es sollten aber nicht mehr als maximal drei Unterebenen geben.

Man wählt einfach die übergeordnete Kategorie - die "Eltern"-Kategorie - aus und die Seite wird als Unterseite geführt.

Im Backend von Wordpress wird die Unterseite dann mit einem Gedankenstrich vor dem Seiten-Titel unterhalb der Eltern-Kategorie angezeigt. Mit jeder weiteren Ebene kommt ein weiterer Gedankenstrich hinzu.

