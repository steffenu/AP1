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
=====  =====================================================================================================




Netzpläne - Berechnungen
**************************

Vorwärtsrechnung
~~~~~~~~~~~~~~~~~~

Rückwärtsrechnung
~~~~~~~~~~~~~~~~~~

Kritischer Weg / Pfad
~~~~~~~~~~~~~~~~~~~~~~~


IHK - Beispiel
**************************


.. image:: https://drive.google.com/uc?export=download&id=1v2CRCUG0aO1WT9q4F_Th4J6qHySIHw63
     :alt:  Freigabe benötigt

.. raw:: html

   <details>
   <summary><a>Die Lösung</a></summary>

.. code-block:: python

   Die Lösung ist Antwort 4

.. raw:: html

   </details>