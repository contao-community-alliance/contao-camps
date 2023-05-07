# UX für Backend User / Contao Camp '23

## Funktionen

* Wie finde ich im Backend das, was ich im Frontend editieren möchte?
* Welche Erweiterungen helfen schon heute im Backend?
    * Node von Terminal42 https://github.com/terminal42/contao-node [1]
    * File Usage von Inspired Minds https://github.com/inspiredminds/contao-file-usage [2]
    * Include Info von Inspired Minds https://github.com/inspiredminds/contao-include-info [3]
    * Page Info von Ingolf https://github.com/e-spin/page-info-bundle [4]
    * Image Copyright von Tastaturberuf https://github.com/Tastaturberuf/contao-image-copyright-bundle/ [5]
    * Layoutusage von Hofff https://github.com/hofff/contao-layoutusage [6]
    * Datei-Verweise anzeigen von Marcel Mathias Nolte (
      u.a.) https://github.com/marcel-mathias-nolte/contao-filesmanager-fileusage [7]
    * Extended Filemanager von Sineos https://gitlab.com/Sineos/filemanager-bundle [8]
    * ... bitte ergänzen
* Wo ist was eingebunden und wird es überhaupt verwendet? (Moritz)
    * Dateien, insbesondere Bilder [2, 7, 8]
    * Formulare [3]
    * News
    * Events
    * Module
    * Templates
    * Layouts [6]
    * Artikel, Seiten [6]
* Wie ließe sich die Symfony Toolbar sinnvoll mit Contao-Informationen oder -Funktionen ergänzen? (Ingolf) https://github.com/contao/contao/issues/6029
* Klickpfade im Backend (Christian & Thorsten)
    * Neues Inhaltselement hinzufügen: Direkt beim Hinzufügen den Elementtyp auswählen, statt erst ein Text-Element
      anlegen und dann den Typ ändern müssen
* Wie kann man die erste Konfiguration (nach der Installation) vereinfachen?
    * z.B. mit einem Wizard, der die User:in durch den Prozess führt: erst Theme und Seitenlayout anlegen, dann die
      Seite etc. "Onboarding"
* Papierkorb für die Dateiverwaltung: Dateien nicht sofort löschen, sondern in einen Papierkorb verschieben, um sie ggf.
  wiederherstellen zu können (Kim) https://github.com/contao/contao/issues/6019
* Wenn ein Bild unter gleichem Namen neu hochgeladen wird, wird es automatisch ersetzt: Wünschenswert wäre es, wenn man
  das vorher explizit bestätigen muss. (Kim) https://github.com/contao/contao/issues/6017
* Breadcrumb für Inhaltselemente: Elternelement anzeigen (Ingolf, Kim) https://github.com/contao/contao/issues/6027
* Bildgrößen direkt im Inhaltselement anlegen (Kim) https://github.com/contao/contao/issues/6020
* Alle verwendeten Bilder mit Lizenz ausgeben (Sitemap für verwendete Bilder) - Image Copyright von Tastaturberuf [5]
  kann eine Liste mit Bildern mit Lizenz + Lizenzlink auszugeben, per Checkbox können einzelne Bilder von der Ausgabe
  ausgeschlossen werden (Ingolf) - ab 07.06.2023 proaktive Meldung der Verwendung von Bildern an Rechteinhaber!
* In Backend und Frontend gleichzeitig einloggen (Im Frontend ausloggen loggt auch den Backend User aus) (Kim) https://github.com/contao/contao/issues/6028
* Weiterlesen-Link individuell benennen können (mit Fallback)
    * Scheint ab 5.x schon möglich zu sein, siehe https://github.com/contao/contao/pull/4742
* Templatenamen beim Anlegen eines neuen Templates direkt vergeben https://github.com/contao/contao/issues/803
* Einzelne Module über das Berechtigungssystem freigeben https://github.com/contao/contao/issues/6016
* Es können nicht alle Module, Formulare, Inhaltselemente, ... dauerhaft freigegeben werden. Die Auswahl beschränkt sich
  immer nur auf die aktuell zur Verfügung stehenden Elemente. https://github.com/contao/contao/issues/6018
* Mehrere Inhaltselemente bearbeiten: Nur Felder zur Auswahl anbieten, die sich auf die ausgewählten Elemente
  beziehen https://github.com/contao/contao/issues/3814
* Wenn eine neue Bildgröße angelegt wird, ist sie standardmäßig nicht freigegeben (Bene)
    * Nach dem Anlegen fragen, ob die Bildgröße direkt freigegeben werden soll (und für welche Gruppe)
    * Gilt auch allgemein für andere Elemente (s.o.)
    * https://github.com/contao/contao/issues/6030


## User Interface (Alexander & Maren)

* Die zur Verfügung stehende Fläche besser nutzen und z.B. mehrere Inhalte nebeneinander anzeigen können
    * Häufiger Workaround: Mehrere Tabs öffnen; macht hin und wieder Probleme mit der Session
* Der Button, um Inhaltselemente auszuklappen, ist winzig klein (und die drei Punkte sind nicht selbst erklärend) https://github.com/contao/contao/issues/6024
* Alle Inhaltselemente auf einmal aufklappen https://github.com/contao/contao/issues/6025
* Alle Kontraste im Backend sind sehr gering https://github.com/contao/contao/issues/6026
* Die Usability der Filter ist schlecht
    * "Filter anwenden" und "Filter zurücksetzen"-Buttons sind zu klein https://github.com/contao/contao/issues/6023
    * Angewendete Filter sind schlecht zu erkennen https://github.com/contao/contao/issues/6022
    * Wenn in einem Dropdown ein Wert ausgewählt ist, ist nicht mehr zu sehen, wonach hier gefiltert wurde (es fehlt ein
      Label für das Dropdown) https://github.com/contao/contao/issues/6021
* Sticky Backend Footer

