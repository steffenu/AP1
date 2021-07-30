Netzplan
========

.. admonition:: Was ist ein Netzplan ?

    Ein ``Netzplan`` ist eine grafische Darstellung
    von Abläufen und deren Abhängikeiten. Die Vorgänge bilden die
    Knoten in den Netzplänen.

.. image:: https://drive.google.com/uc?export=download&id=1hNHAhH2rZAGmSBBxrkl3PmnA6JBAUz98
     :alt:  Freigabe benötigt



=====  =====================================================================================================
FAZ    Der **früheste mögliche Anfangszeitpunkt** zeigt an ,
       dass dieser Vorgang frühestens zu diesem Termin begonnen werden kann.
FEZ    Der **früheste mögliche Endzeitpunkt** zeigt an, wann dieser Vorgang frühestens
       beendet werden kann. Addiert man zum FAZ die Vorgangsdauer , so erhält man den FEZ.
SEZ    Der **späteste mögliche Endzeitpunkt** zeigt an , wann dieser Vorgang spätestens
       zu beenden ist. um das **zeitliche Ziel** des gesamten Projektes nicht
       zu gefährden. Der SEZ- Wert wird bei der Rückwärtsrechnung vom Endtermin aus bestimmt und ist
       abhängig vom spätesten Anfangszeitpunkt seines Nachfolgers. Besitzt ein Vorgang mehrere Nachfolger,
       so berechnet sich der SEZ Wert aus dem kleinsten Wert der SAZ aller seiner Nachfolger
SAZ    Der **späteste mögliche Anfangszeitpunkt** zeigt an, dass dieser Vorgang spätestens zu diesem Termin
       begonnen werden muss, um das **zeitliche Ziel** des gesamten Projektes nicht zu gefährden
       .Zieht man vom SEZ die Vorgangsdauer ab, so erhält man den SAZ.
GP     Der **Gesamtpuffer** des Vorganges gibt an , um welchen Zeitraum dieser Vorgang
       verschoben werden kann, ohne das **zeitliche Ziel** des gesamten Projektes zu gefährden.
       Er ergibt sich jeweils aus der Differenz der spätesten Anfangs- oder Endzeitpunkte und der
       frühesten Anfangs oder Endzeitpunkte
FP     **Freier Puffer**, der zur Verfügung steht, bevor der unmittelbar folgende Prozessschritt beeinflusst
       wird
=====  =====================================================================================================


Netzplan erstellung - Schritte
*******************************

Mit der Tabelle die du in ``AP2``
in einer Aufgabe erhalten wirst
kannst du systematisch die folgenden
Schritte abarbeiten.

Schritt 1: Knoten verknüpfen
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Schritt 2: Vorwärtsrechnung
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Schritt 3: Rückwärtsrechnung
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Schritt 4: Pufferzeiten
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Schritt 5: Kritischer Weg / Pfad
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


.. tip::

    Du wirst dann in der Abschlussprüfung ``AP2`` häufig
    ``Gantt Diagramm`` , ``Netzplan``
    finden und anwenden müssen.  |:grin:|.


Variationen in der Knotendarstellung
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

    Je nachdem welche Quelle du nutzt,
    Sei es ein Lehrbuch , Wikipedia , oder
    eine beliebige Webseite.

    Findest du kleine Variationen
    wie ein Knoten Aufgebaut ist in der
    zeichnerischen Darstellung.

Soll uns aber nicht weiter Stören
wir nehmen einfach die Darstellung
von IHK Prüfungen |:mage:|.

Merke
**************************

- Was ein Netzplan ist.

- Wofür man ihn einsetzt.

- Die Begriffe FAZ , FEZ , SEZ ... einordnen / unterscheiden können

- Schritte aus Tabelle ablesen und Knoten verknüpfen

- Die Formeln wirst du definitiv erhalten in der Prüfung.

- Übe einmal das Beispiel hier , dann solltest du fit sein.

..



:badge:`Vorteile,badge-success`
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


 - Möglichkeit der Darstellung der logischen Abhängigkeiten zwischen Vorgängen
 - Netzpläne zwingen zum systematischen Durchdenken der Projektzusammenhänge


:badge:`Nachteile,badge-danger`
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

 - Nicht so Anwenderfreundlich wie ein ``Gantt Diagramm``
 - Steigende Detaillierung eines Netzplanes ist unmittelbar mit steigendem Kontroll- und Revisionsaufwand verbunden


IHK - Beispiel - Multiple Choice
**********************************


.. image:: https://drive.google.com/uc?export=download&id=1v2CRCUG0aO1WT9q4F_Th4J6qHySIHw63
     :alt:  Freigabe benötigt




.. raw:: html

   <details>
   <summary><a>Die Lösung</a></summary>

.. code-block:: python

   Die Lösung ist Antwort 4

.. raw:: html

   </details>


.. raw:: html

    <br />
    <br />


.. raw:: html

    <br />
    <br />

IHK - Beispiel - Abschlussprüfung
**********************************

.. tip::

    Der ``Netzplan`` ist eine beliebte Aufgabe in den
    vergangenen Abschlussprüfungen gewesen.
    **Viele Punkte** für simples ablesen und Zeichnen. Gönn dir !


AUFGABE
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: https://drive.google.com/uc?export=download&id=17SUPXEmnQu_J1p_Rqpg4HfckAIA5MvIP
    :alt:  Freigabe benötigt







LÖSUNG
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: https://drive.google.com/uc?export=download&id=14c_x-MlhiSbUr6CtFjV1yq8MHBQidWmS
     :alt:  Freigabe benötigt


LÖSUNGSHINWEISE
~~~~~~~~~~~~~~~~~~~~~~~~~~~~


.. image:: https://drive.google.com/uc?export=download&id=1UE0pBbne-PZBqw4kl5cC7_qP79IBhLJ6
     :alt:  Freigabe benötigt


.. tip::

    - Quelle 1 : https://de.wikipedia.org/wiki/Netzplantechnik
    - Quelle 2 : https://www.modu-learn.de/verstehen/management/netzplantechnik/
    - Quelle 3 : Buch -Entwickeln und Bereitstellen von Anwendungssystemen


Schritte im Detail
**********************************

Wir nutzen das Tutorial hier : https://www.modu-learn.de/verstehen/management/netzplantechnik/

Dort wird die Vorgehensweise erklärt.
Nutze die Anleitung und schaue das du
die Lösung der IHK Aufgabe damit sicher aufs
Papier bringst.

Schritt 0 - Tabelle lesen
~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Eine Tabelle mit Prozesschritten
ist der Ausgangspunkt in der Prüfung
woran du dich orientierst und deinen Netzplan
erstellen wirst.



===============  ===============           ===================
Prozesschritte    Dauer in                 Vorher zu beenden
                  Stunden
---------------  ---------------           -------------------
===============  ===============           ===================
A	              2	                       -
B	              4	                       A
C	              3	                       B
D	              2	                       B
E	              1	                       C, D
F	              4	                       C
G	              5	                       E, F
===============  ===============           ===================

Schritt 1: Knoten verknüpfen
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: https://drive.google.com/uc?export=download&id=1wlwj_jbW5cBXypEpEkuwpeFERxjmY0gO
     :alt:  Public

Schritt 2:Vorwärtsrechnung
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: https://drive.google.com/uc?export=download&id=14JTMPvgprxMzxfbxXGca22nkLeJGBf1d
     :alt:  Public

Schritt 3:Rückwärtsrechnung
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: https://drive.google.com/uc?export=download&id=1pdCojbu_wyi36ZPoDsV6S_Qj4YdIfg5N
     :alt:  Public

Schritt 4: Pufferzeiten
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: https://drive.google.com/uc?export=download&id=1YfTfpVWnSMinqLv_98fuHOmmBFQq8BaL
     :alt:  Public

Schritt 5:  Kritischer Weg / Pfad
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: https://drive.google.com/uc?export=download&id=1uKxSp4983B03nVSjBDaoG6UG5puGqAMh
     :alt:  Public




*Seite erstellt: Steffen*