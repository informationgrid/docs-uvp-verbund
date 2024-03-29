Konzept der Nutzerverwaltung des InGrid-Editors
===============================================

Der UVP-Editor ist eine Komponente der Portal-Software InGrid. Durch die Verknüpfung der Nutzverwaltungen des UVP-Portals und des UVP-Editors ergibt sich der Vorteil, dass sich ein Nutzer nur einmal zentral im Portal anmelden muss.

Die UVP-Editor-Nutzerrechte, werden in der Gruppenadministration der UVP-Editor-Nutzerverwaltung festgelegt. Zunächst werden Gruppen definiert, die spezifische Rechte für einen Teilbereich des Katalogs aufweisen und anschließend die Nutzer einer oder mehreren Gruppen zugeordnet.

Im UVP-Editor werden hierbei folgende Rechte (Rollen) unterschieden:

**1. Katalog-Administrator:** Es gibt nur einen Nutzer mit diesen Rechten. Er hat das Recht alle Verwaltungsfunktionen bedienen zu dürfen und kann Nutzer auf allen darunterliegenden Hierarchieebenen mit Schreibrechten auf beliebige Teilbäume erstellen.

**2. Metadaten-Administrator:** Er darf von den Verwaltungsfunktionen nur die Nutzerverwaltung bedienen. Er darf Nutzer mit der Rolle Metadaten-Autor erstellen. Die Rechte dieser Nutzer dürfen aber maximal den Rechten des jeweiligen Metadaten-Administrators entsprechen (z.B. Schreibrechte nur auf einen Teilbaum des Katalogs).

**3. Metadaten-Autor:** Er hat Schreibrechte auf einen Teilbaum des Kataloges, hat aber keinen Zugang zur Nutzerverwaltung oder zu anderen Verwaltungsfunktionen.

Der Katalog-Administrator kann Metadaten-Autoren unter beliebigen Metadaten-Administratoren einrichten. Ein Metadaten-Administrator hat immer das Recht, die ihm nachgeordneten Metadaten-Autoren zu administrieren.
