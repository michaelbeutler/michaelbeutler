---
ref: support
lang: de
permalink: /de/support/
title: Support
description: Hilfe, Kontakt und häufige Fragen zu Helmer.
---

<p class="lede">Helmer ist eine App für Bootsbesitzerinnen und Bootsbesitzer auf
Schweizer Seen: die gesetzlichen Uferzonen auf der Karte, ein GPS-Tachometer,
eine Ankerwache mit Driftalarm und Winddaten von MeteoSchweiz.</p>

## Kontakt

E-Mail **[support@iperka.com](mailto:support@iperka.com)** — ich antworte in der
Regel innert weniger Tage. Helmer wird von einer einzelnen Person entwickelt,
hab also bitte etwas Geduld.

Damit ich ein Problem schnell beheben kann, gib bitte an:

- dein Gerät (z. B. iPhone 15 Pro, Apple Watch Series 9) und die iOS-Version
- die Helmer-Version (Tab «Einstellungen», ganz unten)
- was du getan hast, was du erwartet hast und was stattdessen passiert ist
- einen Screenshot, falls das Problem sichtbar ist

## Voraussetzungen

<div class="table-scroll" markdown="1">

| Plattform | Mindestversion |
|---|---|
| iPhone / iPad | iOS 17.0 |
| Mac | macOS 14.0 |
| Apple Watch | watchOS 10.0 |
| CarPlay | unterstützte Fahrzeuge |

</div>

Verfügbar auf Deutsch, Englisch, Französisch und Italienisch.

## Häufige Fragen

### Warum fragt Helmer nach dem Standort im Hintergrund?

Nur für die Ankerwache. Um dich zu warnen, wenn dein Boot im Schlaf den Anker
schleift, muss die App das GPS auch bei ausgeschaltetem Bildschirm weiterlesen.
Wenn du «Immer» ablehnst, funktioniert alles Übrige — Karte, Zonen, Tacho —
weiterhin normal.

### Der Ankeralarm hat nicht ausgelöst

Prüfe drei Dinge:

1. Die **Mitteilungsberechtigung** inklusive *kritischer Alarme* ist unter
   Einstellungen → Mitteilungen → Helmer erteilt. Kritische Alarme sorgen dafür,
   dass der Alarm den Lautlos-Modus und den Fokus durchbricht.
2. Der Standort steht auf **«Immer»**, nicht auf «Beim Verwenden».
3. Die **Ankerwache ist aktiv** — das Banner wird grün, sobald sie überwacht.

### Welchen Radius soll ich für die Ankerwache wählen?

Faustregel: Kettenlänge + Bootslänge + GPS-Reserve von etwa 15 m. Helmer warnt
bereits bei 80 % des Radius, bevor der volle Alarm ausgelöst wird.

### Warum weicht mein Tempo leicht vom Kartenplotter ab?

Helmer liest die Geschwindigkeit über Grund aus dem GPS des Geräts. Consumer-GPS
schwankt um einige Zehntel km/h, deshalb rechnet Helmer eine Toleranz von
1 km/h ein, bevor eine Überschreitung in der Uferzone gemeldet wird. Wellen,
Verdecke und Hardtops verschlechtern den Empfang zusätzlich; die App zeigt die
aktuelle GPS-Genauigkeit, damit du das einschätzen kannst.

### Funktioniert Helmer ohne Mobilfunkempfang?

Ja. Karte, Zonen, Position, Geschwindigkeit und Ankerwache werden vollständig
auf dem Gerät berechnet und brauchen keine Verbindung. Nur die Winddaten
benötigen ein Netz — ohne Empfang zeigt Helmer weiterhin den zuletzt geladenen
Messwert mit Zeitstempel, damit du weisst, wie alt er ist.

### Woher stammen die Uferzonen?

Sie ergeben sich aus Art. 53 der Binnenschifffahrtsverordnung (SR 747.201.1):

> **Äussere Uferzone (150–300 m)** — max. 10 km/h für Motorschiffe.

> **Innere Uferzone (150 m)** — nur zum Anlegen, Festmachen oder Passieren einer
> Engstelle befahren, auf kürzestem Weg und nie parallel zum Ufer.

Die Linien werden ab der OpenStreetMap-Uferlinie bei 150 m und 300 m berechnet.

### Woher stammen die Winddaten?

Von den 10-Minuten-Messwerten für Wind und Böenspitzen von MeteoSchweiz,
veröffentlicht als Open Government Data (© MeteoSchweiz). Es handelt sich um ein
Messnetz, nicht um eine Prognose.

### Wie genau sind Häfen, Tankstellen und Sperrzonen?

Sie stammen aus Community-Daten von OpenStreetMap und können unvollständig oder
veraltet sein. Prüfe sie vor Ort, bevor du dich darauf verlässt — insbesondere
beim Treibstoff.

### Sind Kursschiff-Routen Live-Positionen?

Nein. Es sind fahrplanmässige, richtungsweisende Linien. Kursschiffe sind
Vorrangschiffe: ausweichen, Kurs frei halten und nicht auf der Linie ankern.

### Wie wechsle ich zwischen km/h und Knoten?

Im Tab «Einstellungen». Die Wahl gilt für den Tacho, die Watch-App und CarPlay.

### Wird meine Position irgendwohin gesendet?

Nein. Siehe [Datenschutzerklärung](/de/privacy/) — deine Position verlässt dein
Gerät nicht.

## Sicherheitshinweis

> Helmer ist ein Hilfsmittel und keine amtliche Navigationskarte. Verantwortlich
> für die Einhaltung der Vorschriften bleibt die Schiffsführerin bzw. der
> Schiffsführer. Die Zonenflächen sind eine bestmögliche Darstellung der
> gesetzlichen Geometrie und können von den massgebenden Quellen abweichen.
> Verlass dich bei gefährlichen Verhältnissen nie allein auf den Ankeralarm.

## Wünsche und Fehler

Ideen sind willkommen unter [support@iperka.com](mailto:support@iperka.com) —
schreib mir, auf welchem See du unterwegs bist und was Helmer nützlicher machen
würde.
