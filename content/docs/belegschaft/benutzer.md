---
title: "Benutzer"
date: 2025-03-04T00:11:22+00:00
menu:
  docs:
    parent: "belegschaft"
weight: 201
toc: true
---


Alle Daten der Nutzer werden in einem Benutzerkonto verwaltet. In den Benutzerkonten werden auch die Zugangsdaten der Nutzer und deren Zugriffsrechte konfiguriert.
Für die Konfiguration von Benutzerkonten ist die Benutzerrolle „Administrator“ erforderlich. Um Benutzerkonten zu verwalten, klicken Sie in der Menüleiste auf Belegschaft > Benutzer.
Seite „Benutzer“

Administratoren können neue Benutzerkonten (Administrator, Standardadmin und Statistik) konfigurieren.
Einstellungen eines vorhandenen Benutzerkontos können geändert werden, ein Benutzerkonto aus dem System gelöscht oder ein Benutzerkonto dupliziert werden.
Auf der linken Menüseite sind alle bereits angelegten Benutzer aufgeführt. Die Details zu dem ausgewählten Benutzer werden auf der rechten Menüseite angezeigt.

# Hinzufügen eines Benutzerkontos

Um ein neues Benutzerkonto zu erstellen klicken Sie in der Menüleiste auf Belegschaft > Benutzer. Eine Liste der bereits eingerichteten Benutzerkonten wird angezeigt.

Klicken auf „Hinzufügen“ ermöglicht es Administratoren ein Benutzerkonto neu zu konfigurieren und es der Liste der verfügbaren Benutzerkonten hinzuzufügen.
Anmerkung: Abhängig von den Funktionen und der Funktionalität, die für Ihr System lizenziert sind, werden einige dieser Felder möglicherweise nicht angezeigt.

# Definition der Eingabefelder

| | |
| ------------- | ------------- |
| E-Mail-Adresse  | Geben Sie die E-Mail-Adresse des Benutzerkontos ein (bis zu 100 Zeichen). Alle Unicode-Zeichen sind erlaubt, einschließlich Leerzeichen und Buchstaben mit Akzent. |
| Benutzername  | Geben Sie den Benutzernamen ein, der verwendet wird, um sich bei diesem Benutzerkonto anzumelden (bis zu 100 Zeichen). Alle Unicode-Zeichen sind erlaubt, einschließlich Leerzeichen und Buchstaben mit Akzent. |
| E-Mail-Adresse als Benutzernamen verwenden | Um sich bei diesem Benutzerkonto mit der E-Mail-Adresse anstelle des Benutzernamens anzumelden, aktivieren Sie das Kontrollkästchen „E-Mail-Adresse als Benutzername“ verwenden. |
| Kennwort | Das Kennwort, welches der Benutzer eingeben muss, um sich beim System anzumelden. Dies wird in Verbindung mit dem Benutzernamen verwendet, um die Benutzeranmeldung zu authentifizieren. Geben Sie das Kennwort für das Benutzerkonto ein (bis zu 30 Zeichen). Alle Unicode-Zeichen sind erlaubt, einschließlich Leerzeichen und Buchstaben mit Akzent. |
| Link zum Zurücksetzen des Kennworts an den Benutzer senden | Aktivieren Sie „Link zum Zurücksetzen des Kennworts an den Benutzer senden“, um festzulegen, dass dem Benutzer ein Einladungslink (per E-Mail) gesendet wird, um sich bei seinem Benutzerkonto anzumelden und sein eigenes Kennwort festzulegen. Wenn diese Option abgewählt ist, muss dem neuen Benutzer sein Initialkennwort anderweitig mitgeteilt werden. |
| Vorname/Nachname | Geben Sie den Vornamen und Nachnamen des Benutzers ein. Jedes Feld kann bis zu 100 Zeichen enthalten. Alle Unicode-Zeichen sind erlaubt, einschließlich Leerzeichen und Buchstaben mit Akzent. |
| Benutzerrollen | Die Benutzerrollen, denen diese Benutzeranmeldung zugeordnet ist. Jede Rolle definiert die Zugriffsebene, die für diesen Benutzer verfügbar ist. Jede Benutzeranmeldung kann einer oder mehreren Benutzerrollen zugewiesen werden. Weitere Informationen finden Sie unter „Verwaltung Benutzerrolle“. |
| Gesperrt | 	Um festzulegen, dass die Anmeldung für dieses Benutzerkonto gesperrt ist, aktivieren Sie das Kontrollkästchen „Gesperrt“. |

Nach Abschluss der Eingaben klicken Sie auf Änderungen speichern um die Konfiguration zu sichern.

# Importieren von Benutzerdetails

Um eine größere Anzahl von Benutzern anzulegen, können Administratoren eine CSV-Textdatei erstellen, welche die Details für mehrere Benutzerkonten enthält.
Die Daten werden über die Web-Schnittstelle in das System hochgeladen.
Um Benutzerdetails zu importieren klicken Sie in der Menüleiste auf Belegschaft > Benutzer. Eine Liste der bereits eingerichteten Benutzerkonten wird angezeigt.

Für die Erstellung einer CSV-Import Datei gehen Sie wie folgt vor:

- Wählen Sie bitte „Importvorlage herunterladen“ um die Mustervorlage der erforderlichen CSV-Datei zu erhalten,
- Öffnen Sie die heruntergeladene CSV-Dateivorlage und geben Sie die Daten für die Benutzerkonten in den entsprechenden Feldern ein.
- Speichern Sie anschließend die Datei im bestehendem CSV-Format.

Anmerkung: Die Daten im Schlüsseldatenfeld userName in der CSV-Datei müssen eindeutig sein. Damit wird der Benutzername (E-Mail-Adresse) des Benutzerkontos identifiziert.
Zum Importieren der Benutzerdetails:

- Klicken Sie auf „Importieren“
- Geben Sie dann die entsprechende CSV-Datei, die hochgeladen werden soll, an und öffnen Sie sie.

# Duplizieren eines Benutzerkontos

Administratoren können ein vorhandenes Benutzerkonto duplizieren, was hilfreich sein kann, wenn sie ein Benutzerkonto hinzufügen möchten, das einem bestehenden sehr ähnelt, sie aber geringfügige Änderungen daran vornehmen möchten.
Zur Duplizierung eines vorhandenen Benutzerkontos klicken Sie in der Menüleiste auf Belegschaft > Benutzer
Eine Liste der bereits eingerichteten Benutzerkonten wird angezeigt.


- Wählen Sie das entsprechende Benutzerkonto aus der Liste aus.
- Klicken Sie auf Duplizieren.
- Geben Sie den neuen Benutzernamen (bis zu 100 Zeichen), die neue E-Mail-Adresse und das zu verwendende Kennwort zur Authentifizierung des Benutzers ein. und klicken Sie anschließend auf OK.
- Bestätigen Sie Ihre Eingaben mit „OK“, zum Verlassen des Dialogs ohne eine Änderung durchzuführen wählen Sie „Verwerfen“.
- Sie können anschließend die Parameter für das duplizierte Benutzerkonto noch ändern.

# Bearbeiten oder Entfernen eines Benutzerkontos

Administratoren können:

- Parameter eines vorhandenes Benutzerkonto ändern
- Änderungen der Benutzerrollen durchführen
- Benutzerkonten aus dem System entfernen

## Änderungen eines Benutzerkontos

Zur Bearbeitung oder zum Entfernen eines vorhandenen Benutzerkontos klicken Sie in der Menüleiste auf Belegschaft > Benutzer
Eine Liste der bereits eingerichteten Benutzerkonten wird angezeigt. Wählen Sie den Benutzer aus für den Änderungen durchgeführt werden sollen.

Über die Informationsmaske zum Benutzer können nun sämtliche gewünschten Änderungen durchgeführt werden.
Um Ihre Eingaben zu sichern bestätigen Sie bitte mit „Änderungen speichern“.

## Löschen eines Benutzerkontos

Zum Entfernen eines vorhandenen Benutzerkontos klicken Sie in der Menüleiste auf Belegschaft > Benutzer
Eine Liste der bereits eingerichteten Benutzerkonten wird angezeigt.

- Wählen Sie den Benutzer aus, der gelöscht werden soll und klicken Sie auf „Entfernen“.
- Bestätigen Sie das Entfernen des Benutzers mit „Ja“

# Zurücksetzen eines Kennworts

Administratoren können das Kennwort zurücksetzen, das ein Benutzer eingeben muss, um sich am System anzumelden. Das Kennwort wird in Verbindung mit dem Benutzernamen zur Authentifizierung des Benutzer-Login verwendet.
Zum Zurücksetzen eines Kennworts klicken Sie in der Menüleiste auf Belegschaft > Benutzer.
Eine Liste der bereits eingerichteten Benutzerkonten wird angezeigt.

Klicken Sie für das entsprechende Benutzerkonto auf Kennwort festlegen. Der Dialog “Kennwort ändern” wird angezeigt.


- Geben Sie das neue Kennwort für das Benutzerkonto ein (bis zu 30 Zeichen). Alle Unicode-Zeichen sind erlaubt, einschließlich Leerzeichen und Buchstaben mit Akzent. Dieses wird in Verbindung mit dem Benutzernamen (Email-Adresse) zur Authentifizierung des Benutzer-Login verwendet.
- Bestätigen Sie das neue Kennwort und klicken Sie dann auf OK. Das System sendet eine E-Mail an den Benutzer, die ihn darüber informiert, dass sein Kennwort zurückgesetzt wurde.

# Suchfunktion

Sie können die integrierte Suchfunktion über das Lupen-Symbol aufrufen können.
Die Suche unterstützt Sie durch auf die jeweiligen Menüseiten abgestimmte Suchparameter.

Über die Dropdown-Liste können Sie die Suchkriterien wählen (aktivieren) nach denen Sie suchen möchten. Standardmäßig sind alle Parameter aktiviert.
Um die Suchkriterien weiter zu verfeinern, können Sie die spezifischen Suchbegriffe im Kästchen Filter eingeben. Sie können zum Beispiel nach einer spezifischen E-Mail-Adresse suchen.
Alle Unicode-Zeichen sind erlaubt, einschließlich Leerzeichen und Buchstaben mit Akzent. Bei den Zeichen werden Groß- und Kleinschreibung nicht berücksichtigt.
Partielle Suchbegriffe werden unterstützt. Wenn Sie also zum Beispiel nach “admin” suchen, werden alle durchsuchbaren Daten, die diesen Begriff irgendwo im Feld enthalten, angezeigt, wie zum Beispiel “admin@company1.com”, “user1@admin.org”, usw.
Ein einzelner Suchbegriff kann gleichzeitig mit mehreren Feldern abgeglichen werden. Wenn Sie zum Beispiel in allen Spalten in der Benutzerkonten-Liste suchen und Sie geben “Dan” als Suchkriterium im Kästchen Filter ein, werden alle Benutzerkonten mit “Dan” oder “dan” im Vornamen-Feld, Nachnamen-Feld oder dem Benutzernamen-Feld angezeigt.
