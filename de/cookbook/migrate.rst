
Migration von netzmacht/contao-bootstrap
========================================

Die Erweiterung contao-bootstrap existierte erstmal als Komplettpaket unter *netzmacht/contao-bootstrap*. Auch wenn
contao-bootstrap daraus hevorgegangen ist, so hat sich dessen Interna an vielen Stellen geändert. Eine Migration einer
Contao-Installation auf die neue Version sollte daher mit Bedacht vorgenommen werden.

Seit dem Release des Grid-Editors 1.0.0 wurde ein Migrationsskript hinzugefügt, der die Spaltensetzuweisung
aktualisiert, sodass die Datenbankstruktur *prinzipiell kompatibel* ist. Jedoch empfehle ich dringend ein Update nur in
einer *Testumgebung durchzuführen*.


Checkliste
----------


Nicht mehr unterstützte Funktionen
**********************************

`Nicht mehr unterstützte Funktionen`_ müssen überprüft werden und ggf. durch andere Funktionen ersetzt werden.


Abhängige Erweiterungen
***********************

Die vorherige Version netzmacht/contao-bootstrap hat einige Erweiterungen vorausgesetzt und automatisch mit installiert.
Sollen diese weiterhin eingesetzt werden, so sind die nachzuinstallieren.

Dies betrifft vor allem:

 * Theme+
 * Subcolumns


Templateänderungen
******************

Vor allem die Templates haben sich geändert. Angepasste Templates müssen dementsprechend überprüft werden und ggf.
angepasst.


Assets
******

Die Bootstrap Assets werden nicht mehr mitgeliefert und müssen nun selbst eingebunden werden.

Empfehlenswert können z.b. die `components/bootstrap`_ Pakete sein.


.. _Nicht mehr unterstützte Funktionen: http://contao-bootstrap.netzmacht.de/neuigkeiten/neue-version-veroeffentlicht.html
.. _components/bootstrap: https://github.com/components/bootstrap
