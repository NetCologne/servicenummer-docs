---
title: "Audiodateien"
date: 2025-03-04T00:11:22+00:00
menu:
  docs:
    parent: "anrufannahme"
weight: 404
toc: true
---

Audiodateien können für reine Ansagen oder Voicemail-Ansagen verwendet werden.
Um die Audiodateien zu verwalten, klicken Sie in der Menüleiste auf Anrufannahme > Audiodateien.
Seite „Audiodateien“

Auf der linken Menüseite sind alle bereits angelegten Audiodateien aufgeführt. Die Details zu der ausgewählten Datei werden auf der rechten Menüseite angezeigt.
Angaben einer vorhandenen Audiodatei können geändert und Dateien gelöscht oder dupliziert werden.

# Vorhandene Audiodateien hochladen

Sie haben die Möglichkeit eigene Audiodateien zu verwenden. Dabei werden folgende Formate werden unterstützt:

- Maximale Dateigröße 5MB
- mp3 Datei (200hz, 16Kbit/8Kbit)
- wav Datei (unkomprimiert, Mono, 16 Bit, PCM)

Zur Verwendung von eigenen Audiodateien gehen Sie wie folgt vor:

1. Klicken Sie in der Menüleiste auf Dienste > Audiodateien
2. Wählen Sie „Hinzufügen“ oder „Hochladen“. Das ‚Hochladen‘ ermöglicht es ihnen, mehrere Dateien auf einmal zu importieren.
3. Vergeben Sie einen Namen für die Ansage
4. Beschreibung (optional)
5. Fügen Sie die gewünschte Datei mit „Datei hochladen“ hinzu


# Text to Speech Ansagen erstellen

Text to Speech bietet Ihnen die Möglichkeit eine Ansagen durch Eingabe des gewünschten Ansagetextes zu erstellen.

Zur Erstellung einer Text-to-Speech Ansage gehen Sie wie folgt vor:

1. Klicken Sie in der Menüleiste auf Dienste > Audiodateien
2. Wählen Sie „Hinzufügen“
3. Vergeben Sie einen Namen für die Ansage
4. Beschreibung (optional)
5. Setzen Sie ein Haken in das Auswahlfeld „Text-to-Speech“
6. Wählen Sie eine weibliche oder männliche Stimme aus
7. Definieren Sie die gewünschte Abspielgeschwindigkeit der Ansage. 30% ist ein Normwert, der eine gute Qualität liefert.
8. Geben Sie den gewünschten Text ein. Hinweis: Es kann erforderlich sein einzelne Worte bewusst falsch zu schreiben, um die sprachliche Umsetzung zu verbessern.
9. Bestätigen Sie die Eingabe mit „Hinzufügen“
10. Anhören des Textes über den „Play-Button“

# Verwendung der Audiodateien

Sie haben die Möglichkeit die erstellten Audiodateien in den Routingplänen zu verwenden.
Hierfür stehen Ihnen zwei Möglichkeiten zur Verfügung:

- Reine Ansage
- egrüßungsansage für eine Voicemailbox (UMS)

Die Verwendung als reine Ansage wird über den Node: Play Announcement realisiert

Weitere Informationen zur Konfiguration: Play Announcement

Die Verwendung als Begrüßungsansage wird über den Outdail-Node realisiert.
