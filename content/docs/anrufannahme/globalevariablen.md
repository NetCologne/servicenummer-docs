---
title: "Globale Variablen"
date: 2025-03-04T00:11:22+00:00
menu:
  docs:
    parent: "anrufannahme"
weight: 408
toc: true
---

Globale Variablen ermöglichen es eine „zentrale Schaltung“ zu konfigurieren, die über die Menüfunktion „Globale Variablen“ manuell aktiviert und deaktiviert werden kann.
Die Variable wird mit Hilfe der Node „Branch on Company Variable“ im Routingplan verwendet. Da die identisch konfigurierte Node in mehreren Routingplänen parallel eingesetzt werden kann, erlaubt es die Funktion auch zeitgleich mehrere Dienste zu steuern.
Ein möglicher Anwendungsfall ist eine Notfall-Situation. In diesem Fall sollen sämtliche Servicerufnummern nicht mehr „normal“ geroutet werden, sondern durch die Aktivierung auf eine zentrale Notfall-Ansage umgeleitet werden.

Administratoren können auf dieser Seite die globalen Variablen verwalten.
Auf der linken Menüseite sind alle bereits angelegten Variablen aufgeführt. Die Details zu der ausgewählten Variablen werden auf der rechten Menüseite angezeigt.
Angaben zu einer vorhandenen Variablen können geändert und Variablen gelöscht oder dupliziert werden.

# Erstellen einer Globalen Variablen
Zur Erstellung einer Globalen Variable gehen Sie wie folgt vor:
1. Klicken Sie in der Menüleiste auf Dienste > Globale Variablen
2. Wählen Sie „Hinzufügen“
3. Vergeben Sie einen Namen für die Variable
4. Unter „Tag“ vergeben Sie einen eindeutigen Namen. Der vergebene „Tag“ wird in der Konfiguration des im Routingplans verwendeten Nodes angegeben.
5. Geben Sie eine kurze Beschreibung ein (optional)
6. Klicken Sie auf „Speichern“ um die Variable zu erfassen.


Die Steuerung erfolgt über das Setzen des Hakens im Schaltkästchen „Aktiv“.
Im Dienst wird der Ausgang „True“ bei „Aktiv“ gesetzt. Ist die Variable nicht „Aktiv“ wird der Ausgang „False“ gesetzt.
Wurde die Node nicht korrekt eingerichtet erfolgt das Routing über den Ausgang „Failed“.

Ist der Tag ‚Gewinnspiel‘ auf ‚Aktiv‘ gesetzt, passiert in unserem Beispiel folgendes:
Ist das Ziel ‚München‘ besetzt oder werden Anrufe nicht angenommen, werden die Anrufer zu einer Ansage weitergeleitet.
Ist ‚Gewinnspiel‘ nicht aktiv, werden die Anrufer in diesen Fällen zu einer Voicemailbox weitergeleitet.
