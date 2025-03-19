
======
Rollen
======

Die Rechte der Benutzer im UVP-Editor werden in der Gruppenadministration der UVP-Editor-Benutzerverwaltung festgelegt. Zunächst werden Gruppen definiert, die spezifische Rechte für einen Teilbereich des Katalogs aufweisen und anschließend die Benutzer einer oder mehreren Gruppen zugeordnet.

Im UVP-Editor werden folgende Rollen unterschieden:


1. Metadatenautor
-----------------

Der Metadatenautor hat Schreibrechte für einen ihm (in der Gruppenverwaltung) zugewiesenen Teilbaum des Katalogs.

Er kann:

| **Adressen:** ab der ihn zugewiesenen Ebenen anlegen
| **Verfahren und negative Vorprüfungen:** anlegen und diese mit den angelegten Adressen verknüpfen
| **Benutzerverwaltung:** kein Zugriff
| **Katalogeinstellungen:** kein Zugriff 


2. Metadatenadministrator
-------------------------

Der Metadatenadministrator hat Schreibrechte für einen ihm (in der Gruppenverwaltung) zugewiesenen Teilbaum des Katalogs.

Er kann:

| **Adressen:** ab der ihn zugewiesenen Ebenen anlegen
| **Verfahren und negative Vorprüfungen:** anlegen und diese mit den angelegten Adressen verknüpfen
| **Benutzerverwaltung:** Zugriff - kann neue Benutzer (Metadatenautoren) unterhalb seiner Ebene anlegen und verwalten.
| **Benutzergruppen:** kann neue Gruppen anlegen
| **Katalogeinstellungen:** kein Zugriff 

Der Metadatenadministrator ist Ansprechpartner für die Metadatenautoren; bei Problemen, die er nicht lösen kann, wendet er sich an den Katalogadministrator.


3. Katalogadministrator
------------------------

Der Katalogadministrator hat das Recht, alle administrativen Funktionen in seinem Katalog zu nutzen und kann Benutzer auf allen untergeordneten Hierarchieebenen mit Schreibrechten in beliebigen Teilbäumen anlegen.

| **Adressen:** Zugriff
| **Verfahren und negative Vorprüfungen:** Zugriff
| **Benutzerverwaltung:** Zugriff - Er kann neue Benutzer (Metadatenautoren und Metadatenadministratoren) anlegen und verwalten.
| **Benutzergruppen:** kann neue Gruppen anlegen und kann Gruppen löschen
| **Katalogeinstellungen:** Zugriff
| **Kataloginterne Medungen im UVP-Editor:** Zugriff
| **Meldungen an die EU (Export):** Zugriff
| **Langzeitspeicherung (geplant):** Zugriff 
| **Monitoring von Dokumenten und Verlinkungen zu Dokumenten (ZABBIX):** Zugriff

Der Katalogadministrator leistet Support bei Problemen mit der Software, dem Katalog und der Benutzerverwaltung.


4. Superadministrator
---------------------

Ein Superadministrator ist eine Ebene über dem Katalogadministrator und kann alle Kataloge verwalten und technischen Support leisten.

**Katalogübergreifende Meldungen im UVP-Editor:** Zugriff
**Meldungen auf der Portal-Startseite:** Zugriff