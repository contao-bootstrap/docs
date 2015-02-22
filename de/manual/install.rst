
Installation
============

Contao-Bootstrap ist eine modular aufgebaute Erweiterung. Je nach Anforderungen können die gewünschten Komponenten
ausgewählt und installiert werden.

Bundle
------

Dank des Bundles gibt es einen komfortablen Weg alle Pakete von Contao-Bootstrap auf einmal zu installieren.
Da das Bundle selbst keine Versionen vorgibt, empfiehlt es sich zusätzlich die Abhängigkeit zur *Core* Komponente zu
setzen.

.. code-block:: javascript

    {
        "require": {
            "contao-bootstrap/core": "~1.0"
            "contao-bootstrap/bundle": "*"
        }
    }

Einzelne Komponenten
--------------------

Dank des modularen Aufbaus der Erweiterung ist es problemlos möglich nur einzelne Komponenten zu installeren und zu
verwenden. Auch dies ist über die Composer möglich.

Beispiel Installation Formular-Komponente:
******************************************

.. code-block:: javascript

    {
        "require": {
            "contao-bootstrap/form": "~1.0"
        }
    }

Optionale Erweiterungen
-----------------------

Contao-Bootstrap unterstützt einige Erweiterungen und greift somit auf bereits vorhandene Funktionen zurück. Diese
werden *nicht* als Abhängigkeiten installiert, sondern können über die gewohnte Installation von Erweiterungen über
den Composer-Client installiert werden.
