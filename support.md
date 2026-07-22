---
title: Helmer Support
description: Help, contact and FAQ for Helmer
permalink: /support/
---

Helmer is a companion app for boat owners on Swiss lakes: a chart with the legal
shore zones, a GPS speedometer, an anchor watch with drift alarm, and MeteoSwiss
wind data.

## Contact

Email **[support@iperka.com](mailto:support@iperka.com)** — I usually reply
within a few days. Helmer is made by one person, so please be patient.

To help me fix a problem quickly, include:

- your device (e.g. iPhone 15 Pro, Apple Watch Series 9) and iOS version
- the Helmer version (Settings tab, bottom of the screen)
- what you did, what you expected, and what happened instead
- a screenshot, if the problem is visible

## Requirements

| Platform | Minimum version |
|---|---|
| iPhone / iPad | iOS 17.0 |
| Mac | macOS 14.0 |
| Apple Watch | watchOS 10.0 |
| CarPlay | supported on compatible vehicles |

Available in English, German, French and Italian.

## Frequently asked questions

### Why does Helmer ask for background location?

Only for the anchor watch. To warn you that your boat has dragged its anchor
while you sleep, the app needs to keep reading GPS with the screen off. If you
decline "Always" access, everything else — chart, zones, speedometer — still
works normally.

### The anchor alarm did not sound

Check three things:

1. **Notification permission**, including *critical alerts*, is granted in
   Settings → Notifications → Helmer. Critical alerts are what let the alarm
   break through Silent mode and Do Not Disturb.
2. **Location is set to "Always"**, not "While Using".
3. **The anchor watch is armed** — the banner at the top of the anchor screen
   shows green when it is actively watching.

### Why is my speed slightly different from my chartplotter?

Helmer reads speed over ground from the device GPS. Consumer GPS drifts by a
few tenths of a km/h, so Helmer applies a 1 km/h tolerance before flagging you
as over the limit in a shore zone. Waves, canopies and hardtops also degrade
GPS reception; the app shows the current GPS accuracy so you can judge it.

### Does Helmer work without mobile signal?

Yes. Zones, position, speed and the anchor watch are computed entirely on the
device and need no connection. Only the wind data requires a network — with no
signal, Helmer keeps showing the last reading it fetched, with a timestamp so
you know how old it is.

### Where does the wind data come from?

From MeteoSwiss 10-minute wind measurements, published as Swiss Open Government
Data (© MeteoSwiss). It is a measurement network, not a forecast.

### Where do the shore zones come from?

They are drawn from Art. 53 of the Swiss Inland Navigation Ordinance
(Binnenschifffahrtsverordnung, SR 747.201.1): the 300 m shore zone with a
10 km/h limit for motorised vessels, and the 150 m inner shore zone which you
may enter only to berth, moor or pass a narrows, by the shortest route.

### How do I switch between km/h and knots?

In the Settings tab. The choice applies to the speedometer, the Watch app and
CarPlay.

### Is my position sent anywhere?

No. See the [privacy policy](/privacy/) — your position never leaves your
device.

## Safety notice

Helmer is an informational aid, **not** a certified navigation instrument. It
does not replace official nautical charts, a proper lookout, or your own
judgement as skipper. Zone overlays are a best-effort rendering of the legal
geometry and may deviate from the authoritative sources; complying with
navigation rules and speed limits remains your responsibility. Never rely on
the anchor alarm alone in dangerous conditions.

## Feature requests and bugs

Ideas are welcome at [support@iperka.com](mailto:support@iperka.com) — tell me
which lake you sail and what would make Helmer more useful.

---

[Privacy Policy](/privacy/) · [Home](/)
