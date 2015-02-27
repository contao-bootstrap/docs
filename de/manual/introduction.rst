
Einführung
==========

Die Erweiterung Contao-Bootstrap integriert das Frontend-Framework `Bootstrap 3`_ in das Open Source Content Management
System `Contao`_. Als modulare Erweiterung setzt sie voll auf die Vorzüge der `Composer-Paket-Verwaltung`_ für Contao.

Diese Dokumentation setzt gute Kenntnisse über die Verwendung `Contao`_ als auch `Bootstrap 3`_ voraus.


Kosten
------

Die Erweiterung kostet mich Zeit zum Entwickeln, Testen, Support leisten, Dokumentation schreiben usw. Nur ein Teil
davon kann ich über eigene Projekte refinanzieren.

Contao-Bootstrap wird als Open-Source-Software unter der *LGPL* sowie *kostenfrei* angeboten. Das Projekt ist aber auf
die `Mitarbeit`_ sowie auf `finanzielle Unterstützung`_ angewiesen um die kontinuierliche Weiterentwicklung
sicherzustellen.


Zwischen zwei Konventionen
--------------------------

Sowohl Contao als auch Bootstrap verfolgen einen eigenen Weg, die sich in der Namensgebung von CSS-Klassen als auch der
vorgegebenen HTML-Struktur widerspiegelt.

Contao-Bootstrap unterstüzt verfolgt den Ansatz Contao über Template-Anpassungen, eigene Module bzw. in einem sinnvollen
Maße durch dynamische Anpassung von CSS-Klassen.


Bootstrap Framework
-------------------

Contao-Bootstrap integriert **nicht** das Bootstrap-Framework. Dies liegt in der Verantwortung des Benutzers. Dadurch
ist die Erweiterung vollständig unabhängig von dem bevorzugten CSS- und Javascript-Workflow. Ob CSS, Less, Sass - es
werden keine Vorgaben gemacht. Möglichkeiten zur Integration werden im :doc:`/cookbook/assets` aufgezeigt.


Modulare Architektur
--------------------

Bootstrap für Contao ist vollständig modular aufgebaut. Dies ermöglicht schnellere Bugfixes und Weiterentwicklung
einzelner Komponenten. Einzelne Komponenten können unabhängig voneinander genutzt werden, sodass eine schlanke
bedarfsgerechte Installation möglich ist.


.. _Bootstrap 3: http://getbootstrap.com
.. _Contao: http://contao.org
.. _Composer-Paket-Verwaltung: https://c-c-a.org/ueber-composer
.. _Mitarbeit: http://contao-bootstrap.netzmacht.de/unterstuetzen.html
.. _finanzielle Unterstützung: http://contao-bootstrap.netzmacht.de/unterstuetzen.html
