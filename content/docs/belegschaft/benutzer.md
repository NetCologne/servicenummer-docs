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

Um ein neues Benutzerkonto zu erstellen klicken Sie in der Menüleiste auf Team > Benutzer. Eine Liste der bereits eingerichteten Benutzerkonten wird angezeigt.

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
Die Daten werden über die Web-Schnittstelle des IN-ServiceManagers in das System hochgeladen.
Um Benutzerdetails zu importieren klicken Sie in der Menüleiste auf Team > Benutzer. Eine Liste der bereits eingerichteten Benutzerkonten wird angezeigt.

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
Zur Duplizierung eines vorhandenen Benutzerkontos klicken Sie in der Menüleiste auf Team > Benutzer
Eine Liste der bereits eingerichteten Benutzerkonten wird angezeigt.
