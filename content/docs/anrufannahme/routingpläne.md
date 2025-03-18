---
title: "Routingpläne"
date: 2025-03-04T00:11:22+00:00
menu:
  docs:
    parent: "anrufannahme"
weight: 401
toc: true
---

Um die Routingpläne zu verwalten, klicken Sie in der Menüleiste auf Anrufannahme > Routingpläne.
Ihnen wird links eine Liste sämtlicher bereits angelegter Routingpläne angezeigt.
Sie können nun einen neuen Routingplan hinzufügen, bestehende Routingpläne bearbeiten oder duplizieren. Für bereits erstellte Routingpläne kann zusätzlich die Im- oder Export-Funktion genutzt werden.

# Erstellen eines Routingplans

Die Konfiguration eines Routingplans erfolgt über das Tool „MapStudio“.

Die Konfigurationsmöglichkeiten sind aufgrund einer Vielzahl von verfügbaren Funktionsblöcken (Nodes) sehr umfangreich und erlauben es sehr individuelle Anrufverteilungen zu erstellen.
Dieser Abschnitt erläutert die generelle Funktionsweise anhand eines einfachen Beispiels und gibt Ihnen einige hilfreiche Tipps zur erfolgreichen Erstellung Ihres eigenen Dienstes.
Weitere Beispiele finden sie unter dem Hilfepunkt „Beispielroutingpläne“

Die Routingpläne werden unabhängig von ihrer Servicerufnummer entwickelt und werden erst durch die Zuordnung zu einer Servicerufnummer aktiviert.
Sobald Sie über die Taste „Hinzufügen“ einen neuen Routingplan anlegen oder einen bestehenden Routingplan auswählen, können Sie das Tool „MapStudio“ durch das Klicken auf das MapStudio-Symbol rechts oben in der Ecke starten.

Wenn Sie einen neuen Routingplan erstellen, befinden Sie sich nun auf einer (noch) leeren Arbeitsfläche.

Die Grundlage für die Erstellung eines Routingplans bilden die sogenannten Nodes. Jede Node repräsentiert einen bestimmten Funktionsumfang innerhalb des Routingplans. Im Kapitel „Nodes“ werden die Funktionen genauer erläutert.
Um alle verfügbaren Nodes anzuzeigen klicken Sie auf das „Buch/Bibliothek“-Symbol.


Um die grundlegenden Prinzipien des MapStudios und die Verwendung von Nodes zu erläutern betrachten wir einen einfachen Anwendungsfall.
Beispiel: Die Anrufe auf eine Servicerufnummer sollen auf eine bestimmte Zielrufnummer geleitet werden.
Um diesen Routingplan in MapStudio zu erstellen, benötigen wir 3 Nodes.

- Inbound Call
- Outdial
- End Call

Durch das Anklicken der drei Nodes in der Bibliothek werden Ihnen diese zur Erstellung des Routingplans im „Node Types“ Fenster angezeigt.
Klicken Sie auf einen Node und bewegen Sie das Element per Drag&Drop auf die Arbeitsfläche. Wiederholen Sie das mit jedem der drei Nodes.
Auf Ihrer Arbeitsfläche sollten sich nun die 3 Nodes befinden und es sollte in etwa so aussehen:


Die Nodes müssen nun zu einem Routingplan verbunden werden, um den genauen Ablauf der Anrufweiterleitung festzulegen.

Der „Inbound Call“-Node ist immer der Anfangs-Node. Hier startet der Routingplan.
Der Routingplan soll als nächstes auf die Zielrufnummer vermitteln, also verbinden wir den Ausgang des „Inbound Call“- Nodes mit dem „Outdial“-Node.
Der „Outdial“-Node verfügt zusätzlich über 3 weitere Optionen für den Fall einer fehlgeschlagenen Vermittlung auf die Zielrufnummer. In Abhängigkeit für den Grund („Timeout/Ziel nicht erreicht“, „Busy/Besetzt“ oder „Other Failure/alle anderen Fehler“) warum die ursprüngliche Zielrufnummer erreicht wurde könnten hier alternative Zielrufnummern angegeben werden.

Wir verbinden aber in diesem Beispiel alle Ausgänge mit dem „End Call“-Node. Das bedeutet, dass der Anruf beendet werden soll, falls das Gespräch nicht angenommen werden konnte.

Ihre Arbeitsfläche sollte nun in etwa so aussehen:


Der Routingplan ist nun so gut wie fertig.
Als letzte Information müssen wir noch die Zielrufnummer anlegen, auf die die eingehenden Anrufe weitervermittelt werden sollen.

Klicken Sie hierzu auf den „Outdial 0“ – Node auf der Arbeitsfläche (nicht auf den links in der Node-Palette). Auf der linken Seite öffnet sich nun ein Bereich, in dem Sie den „Outdial“ – Node fertig konfigurieren können.

Klicken Sie nun auf das „+“ neben den Options.
Klicken Sie auf das „+“ neben der „Outdial Number“ und geben Sie die Rufnummer ein, auf die Ihr Routingplan vermitteln soll.
Der Bildschirm sollte nun in etwa so aussehen:


Der Dienst ist nun fertig konfiguriert und muss nur noch gespeichert werden.

Um den Routingplan abzuspeichern, drücken Sie auf den Pfeil auf der linken Seite des Arbeitsplatzes (gleich über dem „Buch“). Ihr Routingplan sollte fehlerfrei sein, klicken Sie nun auf „Publish“.

Fertig! Ihr erster Dienst kann nun einer Servicenummer zugeordnet werden.
