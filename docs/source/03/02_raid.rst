RAID
###########



.. panels::

    **RAID 0**

    ``Striping``

    .. image:: ../raid0.png
       :alt: some image
       :class: with-shadow
       :scale: 25


    ---

    **RAID 1**

    ``Mirroring``

    .. image:: ../raid1.png
       :alt: some image
       :class: with-shadow
       :scale: 25

    ---

    **RAID 5**

    ``Block-Level Striping``

    .. image:: ../raid5.png
       :alt: some image
       :class: with-shadow
       :scale: 50



.. admonition:: Was ist ein RAID?

  Ein ``RAID-System`` dient zur Organisation mehrerer physischer
  Massenspeicher zu einem logischen Laufwerk,
  das eine höhere Ausfallsicherheit oder einen größeren Datendurchsatz erlaubt als
  ein einzelnes physisches Speichermedium.


RAID 0: Striping
****************

.. admonition:: Definition

  Beschleunigung ohne Redundanz



:badge:`Vorteile,badge-success`
==============


 - RAID 0 bietet gesteigerte Transferraten
 - RAID 0 bietet gesteigerte Transferraten

:badge:`Nachteile,badge-danger`
===========



 - bei Defekt einer Platte tritt Datenverlust ein
 - bei Defekt einer Platte tritt Datenverlust ein





RAID 1: Mirroring - Spiegelung
********************************

RAID 1 ist der Verbund von mindestens zwei Festplatten.

+ +	Beide Platten sind identisch beschrieben und enthalten alle Daten eines Systems
+ +	Fällt eine der gespiegelten Platten aus, kann jede andere weiterhin alle Daten liefern
+ + Zur Erhöhung der Leseleistung kann ein RAID-1-System beim Lesen auf mehr als eine Festplatte zugreifen und gleichzeitig verschiedene Sektoren von verschiedenen Platten einlesen


- - 	Eine Spiegelplatte ist kein Ersatz für eine Datensicherung
- -



RAID 5: Leistung + Parität
********************************
Block-Level Striping mit verteilter Paritätsinformation

.. warning::
 - Weitere Raid Arten : https://de.wikipedia.org/wiki/RAID