Tutorial
====================

.. admonition:: How To

    Wir erstellen ein **Typ 1 - Quick Info** Dokument.



Beispiel für Typ1
***********************************

.. code-block::

        TYP 1 TITLE
        ###########

        .. admonition:: Defintion

            Dies ist die definition des Thema / Kurze Einleitung


        .. image:: url or file path here
           :alt:  Alternaitve Text
           :scale: 25


        Extra Text falls benötigt

        * stichpunkt
        * stichpunkt

        1. nummerierter stichpunkt

        2. nummerierter stichpunkt

        Heading
        ************

        Text hier ... lalalla

        BILD ggf

        Subheading
        ~~~~~~~~~~~~

        Text hier , **fetter text** , *kursiver text* , ``monospaced``

        BILD ggf

        IHK Fragenbeispiel
        ********************

        Fragestellung als text ( screenshot von Aufgabe - bevorzugt )

        .. raw:: html

           <details>
           <summary><a>Die Lösung</a></summary>

        .. code-block::

           Die Lösung ist Antwort C

        .. raw:: html

           </details>

        .. warning::

            - LINK  : https://mein_weiterführender_Artikel

            - LINK 2  : https://mein_weiterführender_Artikel


Titel , Bild ,  und DefinitionsBox
***********************************

Ein Titel ist immer nötig am start des Dokuments:

1. Titel

.. code-block::

    Dokument Titel
    ==============

Danach soll eine Definitionsbox kommen.

2. Definition

.. code-block::

    .. admonition:: Definitions Text Titel

        Defintions Box Text

Dann ein Bild (Bild / Definition auch vertauschbar)

3. Bild

.. code-block::

    .. image::  url or filepath
        :alt:  IMAGE SYNTAX von URL
        :scale: 25

4. Headings , Subheadings

.. code-block::

        Heading
        *******

        Subheading
        ~~~~~~~~~~



Die Syntax Zeichen unter den Titel , Heading , Subheading ...
müssen immer mindestens genauso lang sein wie der Titel. ( länger ist  ok)




Subheading
~~~~~~~~~~~~~~~~

Sofern weitere Unterpunkte benötigt werden
könnt ihr auch noch Subheadings nutzen ...
2 Ebenen sollten hoffentlich ausreichen ( Dokument Titel , Unterpunkt Headings , Subheadings )

.. code-block::

        Dokument Titel
        ====================

        Heading 1
        *********

        Subheading 1
        ~~~~~~~~~~~~

        Heading 2
        *********

        Subheading 2
        ~~~~~~~~~~~~


Fett , Kursiv , Monospace
***********************************

Für Definitionen / wichtige Infos würde ich es gut finden die wichitigen Informationen **fett** zu schreiben.

.. code-block::

    Die syntax für fett = **inhalt hier**
    Kursiv = *inhalt hier*
    monospace = ``inhalt hier``



Zusätzlich habe ich noch 2 Extensions installiert |:metal:|


* für Emojis : https://sphinxemojicodes.readthedocs.io/en/stable/

* und Panels : https://sphinx-panels.readthedocs.io/en/latest/

Ihr könnt dort mal reinschauen falls euch die basic
formatierung nicht ausreicht ;) .
Der Schnickschack sollte reichen.
