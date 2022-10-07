
Benutzerverwaltung
================

Die Rechte der Benutzer im UVP-Editor werden in der Gruppenadministration der UVP-Editor-Benutzerverwaltung festgelegt. Zunächst werden Gruppen definiert, die spezifische Rechte für einen Teilbereich des Katalogs aufweisen und anschließend die Benutzer einer oder mehreren Gruppen zugeordnet.

Im UVP-Editor werden hierbei folgende Rechte (Rollen) unterschieden:

**1. Autor:** Er hat Schreibrechte auf einen Teilbaum des Kataloges, hat aber keinen Zugang zur Benutzerverwaltung oder zu anderen Verwaltungsfunktionen.

**2. Metadaten-Administrator:** Er darf von den Verwaltungsfunktionen nur die Benutzerverwaltung bedienen. Er darf Benutzer mit der Rolle Metadaten-Autor erstellen. Die Rechte dieser Benutzer dürfen aber maximal den Rechten des jeweiligen Metadaten-Administrators entsprechen (z.B. Schreibrechte nur auf einen Teilbaum des Katalogs).

**3. Katalog-Administrator:** Es gibt nur einen Benutzer mit diesen Rechten. Er hat das Recht alle Verwaltungsfunktionen bedienen zu dürfen und kann Benutzer auf allen darunterliegenden Hierarchieebenen mit Schreibrechten auf beliebige Teilbäume erstellen.

Eine Ebene über den Katalogadmnistrator ist der Superadministrator, dieser wird durch den Katalogadministrator bei technischen Problemen kontaktiert.

.. image:: ../img-ige-ng/nutzerverwaltung/ige-ng_nutzerverwaltung_rollen.png

Abb.: Benutzerverwaltung - Rollen

Der Katalog-Administrator kann Autoren und Metadaten-Administratoren einrichten. Ein Metadaten-Administrator hat immer das Recht, die ihm nachgeordneten Autoren zu administrieren.


