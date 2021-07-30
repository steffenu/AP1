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

Der Ablauf erklärt für AP1
**************************

    *für die Lösung der IHK multiple choice Aufgabe*

**Merke dir** :

- Was ein Netzplan ist.

- Wofür man ihn einsetzt.

- Die Begriffe FAZ , FEZ , SEZ ... einordnen / unterscheiden können

.. tip::

    Für ``AP1`` genügt es die Begriffe zu kennen und den Ablauf
    grob zu verstehen. Du kannst natürlich vorab üben für ``AP2``.
    Wenn du aufs IHK Beispiel (vergangene Zwischenprüfung)
    schaust weist du warum ich meine du kannst erstmal
    noch locker bleiben.



Schritt 0 - Prozessschritte
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

Schritt 2:Vorwärtsrechnung
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Schritt 3:Rückwärtsrechnung
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Schritt 4: Pufferzeiten
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Schritt 5:  Kritischer Weg / Pfad
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

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

.. tip::

    - Quelle 1 : https://de.wikipedia.org/wiki/Netzplantechnik
    - Quelle 2 : https://www.modu-learn.de/verstehen/management/netzplantechnik/
    - Quelle 3 : Buch -Entwickeln und Bereitstellen von Anwendungssystemen

.. raw:: html

    <br />
    <br />

IHK - Beispiel - Abschlussprüfung
**********************************

.. tip::

    Der ``Netzplan`` ist eine beliebte Aufgabe in den
    vergangenen Abschlussprüfungen gewesen.
    Viele Punkte für simples ablesen und Zeichnen.

AUFGABE :

.. image:: https://drive.google.com/uc?export=download&id=1UE0pBbne-PZBqw4kl5cC7_qP79IBhLJ6
     :alt:  Freigabe benötigt

*LÖSUNGSHINWEISS* :

.. image:: https://drive.google.com/uc?export=download&id=14c_x-MlhiSbUr6CtFjV1yq8MHBQidWmS
     :alt:  Freigabe benötigt

**

LÖSUNG :

.. image:: https://drive.google.com/uc?export=download&id=17SUPXEmnQu_J1p_Rqpg4HfckAIA5MvIP
    :alt:  Freigabe benötigt



.. image:: https://drive.google.com/uc?export=download&id=17SUPXEmnQu_J1p_Rqpg4HfckAIA5MvIP
     :alt:  Freigabe benötigt

 *Seite erstellt: Steffen*