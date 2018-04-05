Author: Sven Rhinow
Web: www.sr-tag.de
License: LPGL
Version: 3.1.0

deutsch
--------------------------------------
dieses Contao-Modul stellt die Möglichkeit zur Verfügung ein Layer in verschiedenen Arten anzuzeigen
- durch Klick auf eine Schaltfläche oder Link
- Aufruf beim betreten der Seite
- Übergabe von bestimmten GET-Parametern
- Die Anzeige kann durch COOKIES,SESSION und mit Start und Stop-Zeit limitiert werden

weitere Eigenschaften vom srlayer sind:
- unterstützt jetzt sowohl jQuery als auch Mootools
- diverse Vorgaben wie Breite und Höhe des Layers als auch Position des Layers und Transparenz des Overlays werden zukünftig nur noch per CSS-Datei gesetzt. So kann man z.B. besser auf responsive Bedingungen reagieren.
- die Anzeige kann zeitlich verzögert werden bevor der Layer erscheint
- Der Inhalt des Layers kann absolute flexible gestaltet werden da es den im Modul eingetragenen Text anzeigt und auch mit inserttags auf Artikel, Inhaltselemente und Module gesteuert werden kann

Vorraussetzung: dieses Modul basiert auf das Mootools-, oder das jQuery-Framework

*neu (>= 3.1.0)*
Es kann das Modul jetzt auch so eingestellt werden das die Cookie-Prüfung unabhängig von der Cookie-Setzung ist. So kann die Cookie-Setzung z.B. von einem Formular gesetzt werden.
Dazu muss im Formular drei versteckte Felder angelegt werden

 - "srlayer_set_cookie" als Wert muss hier der Cookiename angegeben werden
 - "srlayer_check_field" (optional) Name des zuprüfenden Feldes
 - "srlayer_cookie_duration" (optional) kann den Defaultwert von 3600 überschreiben

Im Formular darf dann kein Haken bei Cookie setzen sein aber bei Cookie auswerten muss ein Haken sein und der Cookiename muss dem aus dem versteckten Formularfeld entsprechen.