Tutorial
====================

.. admonition:: How To

    Wir erstellen ein **Typ 1 - Quick Info** Dokument.



Titel , Bild ,  und DefinitionsBox
***********************************

Als Einleitung möchten wir immer gerne :

1. Titel

.. code-block::

    Dokument Titel
    ==============




2. Definition

.. code-block::

    .. admonition:: Definitions Text Titel

        Defintions Box Text

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



Die Sntax Zeichen unter den Titel , Heading , Subheading ...
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

Für Definitionen würde ich es gut finden die wichitigen Informationen **fett** zu schreiben.

.. code-block::

    Die syntax für fett = **inhalt hier**
    Kursiv = *inhalt hier*
    monospace = ``inhalt hier``


Fertiges Beispiel
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

        .. warning::

            - LINK  : https://mein_weiterführender_Artikel

            - LINK 2  : https://mein_weiterführender_Artikel