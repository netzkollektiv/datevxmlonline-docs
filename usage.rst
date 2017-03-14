.. _usage:

Verwendung
===================

Um die Rechnungsdaten inkl. Belegbildern Ihrem Steuerberater zur Verfügung zu stellen, müssen diese aus Magento in ein DATEV XML Online kompatibles Format exportiert werden. Dies übernimmt die DATEV XML Online Extension für Magento. 

Export von Buchhaltungsdaten aus Magento
----------------------------------------

Rechnungsexport
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Um Rechnungen zu exportieren fahren Sie im Backend von Magento mit der Maus über den Punkt **Verkäufe** und wählen dann **DATEV XML Online**:

:menuselection:`Verkäufe --> DATEV XML Online`

Mit Hilfe der aus den anderen Grids von Magento bekannten Filterung, filtern Sie die relevanten Rechnungen, die sie exportieren möchten in der Ansicht und selektieren die zu exportierenden Rechnungen. Wählen Sie nun aus dem rechts befindlichen Select-Feld "Aktionen", die Option **DATEV XML Online Paket**.

:menuselection:`Aktionen --> DATEV XML Online Paket`

Gutschriftenexport
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Beim Gutschriften Export gehen Sie analog zum Rechnungsexport vor. Sie erhalten ein zweites Archiv, das die Rechnungen des selektierten Zeitraumes enthält.

Rechnungsimport nach DATEV Unternehmen Online
---------------------------------------------

Um die Rechnungen nun zur Verfügung zu stellen, müssen diese nach DATEV importiert werden. 

.. note:: Importieren Sie immer das **nicht-entpackte** ZIP-Archiv in jegliche DATEV-Applikationen, so wie Sie es aus Magento erhalten haben. Falls Sie das Archiv vorher entpacken oder wieder packen, kann es zu Problemen beim Import kommen.

Import über DATEV Unternehmen Online (Web)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

* Navigieren Sie zu `DATEV Unternehmen Online <http://duo.datev.de>`_.
* Loggen Sie sich mit der :ref:`DATEV Smart Login App <requirements>` oder über das :ref:`DATEV Sicherheitspaket <requirements>` ein

.. image:: /images/datev-smartlogin-screen.png

* Wählen Sie links im Menü den Punkt :menuselection:`Belegwesen --> Belegverwaltung`
* Wählen Sie nun rechts :menuselection:`Belege --> neuen Beleg hinzufügen`
* Wählen Sie die aus Magento heruntergeladene ZIP-Datei aus und **entfernen** Sie den Haken von **ZIP-Archiv entpacken**.
* Wählen Sie als Belegtyp

  * bei Rechnungen **Rechnungsausgang**
  * bei Gutschriften **Rechnungseingang**

* Klicken Sie nun unten auf **Übernehmen**

.. image:: /images/datev-unternehmenonline-beleg-upload.png

Import über DATEV Belegtransfer
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


