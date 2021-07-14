Anlegen von IGE-Benutzern
=========================

Konzept der Nutzerverwaltung des InGrid-Editors
-----------------------------------------------


Der UVP-Editor ist eine Komponente der Portal-Software InGrid. Durch die Verknüpfung der Nutzverwaltungen des UVP-Portals und des UVP-Editors ergibt sich der Vorteil, dass sich ein Nutzer nur einmal zentral im Portal anmelden muss.

Die UVP-Editor-Nutzerrechte, werden in der Gruppenadministration der UVP-Editor-Nutzerverwaltung festgelegt. Zunächst werden Gruppen definiert, die spezifische Rechte für einen Teilbereich des Katalogs aufweisen und anschließend die Nutzer einer oder mehreren Gruppen zugeordnet.

Im UVP-Editor werden hierbei folgende Rechte (Rollen) unterschieden:

1.	Katalog-Administrator: Es gibt nur einen Nutzer mit diesen Rechten. Er hat das Recht alle Verwaltungsfunktionen bedienen zu dürfen und kann Nutzer auf allen darunterliegenden Hierarchieebenen mit Schreibrechten auf beliebige Teilbäume erstellen.

2.	Metadaten-Administrator: Er darf von den Verwaltungsfunktionen nur die Nutzerverwaltung bedienen. Er darf Nutzer mit der Rolle Metadaten-Autor erstellen. Die Rechte dieser Nutzer dürfen aber maximal den Rechten des jeweiligen Metadaten-Administrators entsprechen (z.B. Schreibrechte nur auf einen Teilbaum des Katalogs).

3.	Metadaten-Autor: Er hat Schreibrechte auf einen Teilbaum des Kataloges, hat aber keinen Zugang zur Nutzerverwaltung oder zu anderen Verwaltungsfunktionen.

Der Katalog-Administrator kann Metadaten-Autoren unter beliebigen Metadaten-Administratoren einrichten. Ein Metadaten-Administrator hat immer das Recht, die ihm nachgeordneten Metadaten-Autoren zu administrieren.


Neuanlegen eines IGE-Nutzers
----------------------------

Vorbereitende Schritte:

Neuen Portal-Nutzer anlegen
Der Nutzer muss als Portal-Nutzer registriert sein. Er kann sich selbst unter dem Link „Anmelden interner Bereich“ (rechts oben) registrieren. Zur Bestätigung seiner Anmeldung erhält der Nutzer eine E-Mail mit einem Freischaltungslink. Mit der Bestätigung dieses Links wird die Anmeldung im Portal aktiviert.

Um dem neuen Nutzer passende Rechte für den InGrid-Editor zuordnen zu können, muss in der „Gruppenadministration“ der UVP-Editor-Nutzerverwaltung geprüft werden, ob bereits eine oder mehrere Gruppen existieren, die mit entsprechenden Rechten ausgestattet sind. Ist dies nicht der Fall, müssen eine oder mehrere neue Gruppen angelegt werden.

Abb.:

 
Nachdem gehen Sie bitte wie folgt vor:

Klicken Sie in der Nutzeradministration (UVP-Editor-Nutzerverwaltung) auf den Administrator, der für den neuen Nutzer zuständig sein soll (Hierarchiebaum auf der linken Seite).

Als Katalog-Administrator können Sie Metadaten-Administratoren und Metadaten-Autoren im gesamten Katalog anlegen. Als Metadaten-Administrator können Sie nur Metadaten-Autoren unterhalb ihres eigenen Eintrags anlegen. Unterhalb von Metadaten-Autoren können keine weiteren Nutzer angelegt werden.

Klicken Sie auf die Schalfläche Nutzer anlegen (unterhalb des Hierarchiebaums). Geben Sie nun in das Dialogfeld die Anfangsbuchstaben des neuen Portal-Nutzers ein und wählen Sie dann aus der Auswahlliste den entsprechenden Nutzer aus. Klicken Sie anschließend auf die Schalfläche Übernehmen, um dem neuen Nutzer den ausgewählten UVP-Editor-Administrator zuzuordnen.
 
**Hinweis:**
*Namen, die mit großen Anfangsbuchstaben beginnen, werden in der Auswahlliste zuerst gelistet.*

Abb.:
 
**Hinweis**
Ein Portal-Nutzer, der bereits einem UVP-Editor-Katalog zugeordnet ist, kann keinem zweiten Katalog zugeordnet werden. Diese Regelung betrifft auch Schulungskataloge. Deshalb werden Nutzer, die bereits mit UVP-Editor-Rechten ausgestattet sind, nicht mehr in der Auswahlliste angezeigt.

1. Für den neuen UVP-Editor-Nutzer müssen nun einige Nutzerdaten (Name, E-Mail, Institution) erfasst werden.

2. Weisen Sie dem neuen UVP-Editor-Nutzer eine oder mehrere Gruppen zu. In der Auswahlliste werden alle in der Gruppenadministration definierten Gruppen angezeigt für die Sie die Berechtigung zur Administration besitzen.

Abb.:
 
3.	Mit „Speichern“ (Schaltfläche unten rechts) schließen Sie den Vorgang ab.


Bearbeiten und Löschen eines bereits existierenden IGE-Nutzers
--------------------------------------------------------------

Wählen Sie durch Mausklick im Hierarchiebaum auf der linken Seite des Fensters einen Nutzer aus, den Sie bearbeiten oder löschen wollen.

Die Nutzerdaten werden in die Felder auf der rechten Seite des Fensters geladen. Sie können das Login, die Adressdaten und die Gruppe ändern. Über Speichern sichern Sie die Änderungen.

Hinweis: Dem Katalog-Administrator ist immer automatisch die Gruppe administrators zugewiesen. Diese Zuordnung kann nicht geändert werden. Die Gruppe steht anderen Nutzern nicht zur Verfügung.

Zum Löschen des Nutzers klicken Sie auf die Schaltfläche Nutzer löschen und bestätigen den Vorgang in dem sich öffnenden Dialog.

Abb.:
 

Anzeige der Verantwortlichkeiten eines IGE-Nutzers
--------------------------------------------------
Über den Reiter "Verfahren / Adressen" (Nutzeradministration) werden zwei Tabellen angezeigt, die die Verfahren und Adressen auflisten, in denen der ausgewählte Benutzer als Verantwortlicher eingetragen ist. Es ist möglich direkt aus diesen Tabellen-Zeilen auf ein Verfahren bzw. Adresse zu springen.
 
Abb.:


Gruppenadministration
=====================

Über die (Nutzer-) Gruppen werden die Schreibrechte auf Verfahren und Adressen festgelegt.

In der Gruppenadministration können Sie:

 • Eine Gruppe bearbeiten: Klicken Sie auf den Namen der Gruppe in der Liste links oben im Fenster. Sie können nun den Namen der Gruppe ändern sowie die Rechte für die Gruppe. Änderungen müssen mit Speichern abgeschlossen werden und stehen dann sofort zur Verfügung.

Abb.:

 • Eine Gruppe neu anlegen: Klicken Sie auf die Schaltfläche Neue Gruppe anlegen. Sie müssen den Gruppennamen angeben und den Vorgang mit Speichern abschließen. Sie können nun die Rechte für die Gruppe angeben.

Abb.:

 • Eine Gruppe löschen: Klicken Sie mit der rechten Maustaste auf den Namen der Gruppe, die Sie löschen wollen. Wählen Sie Zeile löschen aus dem Kontextmenü und bestätigen Sie den Vorgang in dem sich öffnenden Dialog.

Abb.:
 
**Wichtig:** *Alle Änderungen an den Gruppen müssen über Speichern abgeschlossen werden, damit die Änderungen wirksam werden und nicht verloren gehen.*

Sie können folgende Berechtigungen für eine Gruppe vergeben:

**Berechtigungen für Verfahren**
Sie können Schreibberechtigungen für Verfahren vergeben. Wählen sie dazu den Ordner oder das Verfahren unter Berechtigungen für Verfahren aus dem Hierarchiebaum aus, für das Sie oder ab dem Sie die Schreibberechtigung vergeben wollen. Ein Klick auf das Symbol färbt den Hintergrund blau. Über die Schaltfläche > können Sie das markierte Symbol in die Liste der Berechtigungen übernehmen.

Sie haben drei Einstellungsmöglichkeiten für die Berechtigung pro Ordner/Vorhaben:

Abb.:
 
 •**Teilbaum:** Dies ist die Standardeinstellung. Sie haben für dieses und alle nachgeordneten Verfahren eine Schreibberechtigung. Sie können unterhalb dieses Verfahrens und allen nachgeordneten Verfahren neue Verfahren anlegen.

 •**Unter-Verfahren:** Sie können direkt unterhalb dieses Verfahrens ein neues Verfahren anlegen, für das Sie dann den vollen Zugriff bekommen (Teilbaum Recht auf neuem Unter-Verfahren). Alle Benutzer Ihrer Gruppe bekommen damit ebenfalls vollen Zugriff (alle Benutzer der Gruppe, die das Unter-Verfahrensrecht beinhaltet).

 •**Einzelobjekt:** Sie haben nur auf diesem Verfahren eine Schreibberechtigung, auf nachgeordnete Verfahren nicht. Sie können keine neuen Verfahren unterhalb dieses Verfahrens anlegen.

**Hinweis:** *Sie können keine Schreibrechte auf den Strukturbaumknoten Verfahren vergeben. Alle Teilbäume des Kataloges, auf die ein Schreibrecht bestehen soll, müssen einzeln ausgewählt werden.*

**Berechtigungen für Adressen**
Sie können Schreibberechtigungen für Adressen vergeben. Wählen Sie dazu die Adresse unter Berechtigungen für Adressen aus dem Hierarchiebaum aus, für die Sie oder ab der Sie die Schreibberechtigung vergeben wollen. Ein Klick auf die Adresse färbt sie blau ein. Über die Schaltfläche > können Sie die markierte Adresse in die Liste der Berechtigungen übernehmen.

Sie haben drei Einstellungsmöglichkeiten für die Berechtigung pro Adresse:
 
 •**Teilbaum:** Dies ist die Standardeinstellung. Sie haben für diese Adresse und alle nachgeordneten Adressen eine Schreibberechtigung. Sie können unterhalb dieser und allen nachgeordneten Adressen neue Adressen anlegen.

 •**Unteradressen:** Sie können direkt unterhalb dieser Adresse eine neue Adresse anlegen, für die Sie dann den vollen Zugriff bekommen (Teilbaum Recht auf neuer Unteradresse). Alle Benutzer Ihrer Gruppe bekommen damit ebenfalls vollen Zugriff (alle Benutzer der Gruppe, die das Unteradressenrecht beinhaltet).

 •**Einzeladresse:** Sie haben nur auf diese Adresse eine Schreibberechtigung, auf nachgeordnete Adressen nicht. Sie können keine neuen Adressen unterhalb dieser Adresse anlegen.
 
**Hinweis:** *Sie können keine Schreibrechte auf die Strukturbaumknoten Adressen und freie Adressen vergeben. Alle Teilbäume des Kataloges, auf die ein Schreibrecht bestehen soll, müssen einzeln ausgewählt werden.*

**Root-Verfahren und -Adressen anlegen**
Dies ist ein gesondertes Schreibrecht. Wird es für eine Gruppe vergeben, haben die Mitglieder dieser Gruppe das Recht, neue Verfahren und Adressen auf der obersten Ebene des Kataloges anzulegen. Sie erhalten dann automatisch die Schreibrechte auf den ganzen Teilbaum des neuangelegten Verfahrens bzw. der neuangelegten Adresse.

Abb.:
 
**Wichtig:** *Durch dieses Recht hat die Gruppe nicht automatisch das Schreibrecht auf schon vorhandene Teilbäume, für die ihr nicht explizit Schreibrechte eingeräumt wurden.*

**Qualitätssichernder**
Über die Berechtigung Qualitätssichernder werden die Nutzer der Gruppe für alle Verfahren und Adressen, für die sie ein Schreibrecht besitzen, zu Qualitätssichernden. Sie haben also das Recht (und auch die Pflicht), an sie überwiesene Verfahren und Adressen zur Veröffentlichung freizugeben bzw. endgültig zu löschen oder bei Qualitätsmängeln die Verfahren bzw. Adressen an den Zuständigen zurück zu überweisen.

Abb.:
 
**Hinweis:** *Dieses Recht wird nur im Zusammenhang mit der eingeschalteten Workflow-Kontrolle in den Katalogeinstellungen wirksam.

**Zugeordnete Nutzer**
Auf dem dritten Reiter werden alle Benutzer aufgelistet, welche der gewählten Gruppe zugeordnet wurden.

Abb.:

**Die spezielle Gruppe administrators des Katalogadministrators**
Dem Katalogadministrator wird immer automatisch die Gruppe administrators zugewiesen. Diese Zuweisung kann nicht verändert werden. Die Gruppe hat Schreibrechte auf den gesamten Katalog (natürlich einschließlich des Rechts auf Anlegen von neuen Verfahren und Adressen auf der obersten Ebene). Die Gruppe hat feste Rechte und ist in jedem Katalog automatisch vorhanden. Sie lässt sich nicht über die Gruppenadministration pflegen und wird daher auch nicht in der Liste der Gruppen angezeigt.


Berechtigungsübersicht
----------------------

In der Berechtigungsübersicht werden alle Nutzer angezeigt, die auf ein Verfahren, eine Adresse oder einen Teilbaum Schreibrechte oder das Recht für Unter-Verfahren/Unteradressen oder zur Qualitätssicherung haben.

Abb.:
 
Klicken Sie auf ein beliebiges Verfahren unter Berechtigung für Verfahren oder auf eine beliebige Adresse unter Berechtigung für Adressen. Das ausgewählte Verfahren bzw. die ausgewählte Adresse werden blau markiert. Es werden die Nutzernamen und die Rollen aller Nutzer angezeigt, die auf das Verfahren bzw. die Adresse mindestens eines der folgenden Rechte haben:
 • Schreibrecht auf das Einzelverfahren bzw. die Einzeladresse
 • Schreibrecht auf den Teilbaum
 • Recht zur Erstellung direkter Unter-Verfahren bzw. Unteradressen


**Hinweis:** *Eine Anleitung für die Erfassung von Verfahren, finden Sie im Teil 2 der Erfassungsanleitung.*
