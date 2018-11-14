.. _configuration:

Konfiguration
=============

Einstellungen in Magento
--------------------------------

Die Konfiguration des Modules befindet sich unter :menuselection:`System --> Konfiguration --> Sales --> DATEV XML Online` 
Hier werden inbesondere Daten definiert, welche im XML Online Archive Ihrem Steuerberater übergeben werden, wie z.B. Kontierungsinformationen, allgemeine Unternehmensdaten und Bankdaten.

Kontierungsinformationen
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Im Tab *Kontierungsinformationen* können Sie die Konten-Zuweisungen vornehmen. Hier verknüpfen Sie die in Magento eingestellten Steuerregeln mit Ihrem Kontenrahmen.
Das Standard-Personnenkonto wird verwendet für alle Umsätze, die sich nicht zuordnen lassen bzw. für die keine Steuerregel-Zuweisung eingestellt ist.
Typischerweise werden hier Konten von 8000-8099 angegeben. Die speziellen Konten für Ihren Kontenrahmen erfragen Sie bitte bei Ihrem Steuerberater.

Als Gegenkonto geben Sie bitte das entsprechende Sachkonto ein.

Lieferanten Informationen (optional)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

In den Lieferanten Informationen pflegen sie Ihre eigenen Unternehmensdaten zur Übergabe an DATEV. Die Angaben hier sind optional und müssen nur ausgefüllt werden, wenn Sie möchten, dass diese Ihrem Steuerberater zusätzlich zur Verfügung stehen.
 
Steuer Information (optional)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Fügen Sie hier ebenfalls Ihre eigenen steuerelevanten Unternehmensdaten ein. Diese Daten sind ebenfalls optional und müssen nicht zwingend ausgefüllt werden.

Bankdaten (optional)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Fügen Sie hier ebenfalls Ihre eigenen Bankdaten ein. Auch diese Daten sind optional.

Versandkosten als eigenen Position übertragen
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Hier können Sie entscheiden, ob die Versandkosten im Feld *Versandkosten* im XML ausgebenen werden oder als eigene Bestell-Position, analog zu den gekauften Artikeln übertragen werden soll. Die Einstellung hängt von der Präferenz Ihres Steuereraters ab. Stellen Sie Ihrem Steuerberater am Besten beide Versionen zur Verfügung, so dass er sich die für beste Version auswählen kann.

Einstellungen in Datev Unternehmen online
------------------------------------------

Für den korrekten Import in Unternehmen online sind dort einige Einstellungen vorzunehmen. 

Bearbeitungsform auf "Erweitert" umstellen
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Zur korrekten Verbuchung der im Export enthaltenen Rechnungen, ist die Verarbeitungsform umzustellen. Gehen Sie hierzu in **Belege online** und wählen klicken Sie in der rechten unteren Ecke das Einstellungssymbol. Dort wählen Sie das Tab **Bearbeitungsform** und stellen diese auf **Erweitert**.

.. image:: /images/m2-datevxmlonline-uo-bearbeitungsform-pfad.png

.. image:: /images/m2-datevxmlonline-uo-bearbeitungsform.png

.. note:: Diese Einstellung kann unter Umständen nur Ihr steuerlicher Berater durchführen
