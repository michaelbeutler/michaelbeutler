---
ref: support
lang: en
permalink: /support/
title: Support
description: Help, contact and frequently asked questions for Helmer.
---

<p class="lede">Helmer is a companion app for boat owners on Swiss lakes: the
legal shore zones on a chart, a GPS speedometer, an anchor watch with drift
alarm, and MeteoSwiss wind data.</p>

## Contact

Email **[support@iperka.com](mailto:support@iperka.com)** — I usually reply
within a few days. Helmer is made by one person, so please be patient.

To help me fix a problem quickly, include:

- your device (e.g. iPhone 15 Pro, Apple Watch Series 9) and iOS version
- the Helmer version (Settings tab, bottom of the screen)
- what you did, what you expected, and what happened instead
- a screenshot, if the problem is visible

## Requirements

<div class="table-scroll" markdown="1">

| Platform | Minimum version |
|---|---|
| iPhone / iPad | iOS 17.0 |
| Mac | macOS 14.0 |
| Apple Watch | watchOS 10.0 |
| CarPlay | supported vehicles |

</div>

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
   break through Silent mode and Focus.
2. **Location is set to "Always"**, not "While Using".
3. **The anchor watch is armed** — the banner turns green when it is actively
   watching.

### What radius should I set for the anchor watch?

Rule of thumb: rode length + boat length + a GPS margin of about 15 m. Helmer
warns at 80 % of the radius before it raises the full alarm.

### Why is my speed slightly different from my chartplotter?

Helmer reads speed over ground from the device GPS. Consumer GPS drifts by a few
tenths of a km/h, so Helmer applies a 1 km/h tolerance before flagging you as
over the limit in a shore zone. Waves, canopies and hardtops also degrade GPS
reception; the app shows the current GPS accuracy so you can judge it.

### Does Helmer work without mobile signal?

Yes. The chart, zones, position, speed and the anchor watch are computed
entirely on the device and need no connection. Only the wind data requires a
network — with no signal, Helmer keeps showing the last reading it fetched, with
a timestamp so you know how old it is.

### Where do the shore zones come from?

They are drawn from Art. 53 of the Swiss Inland Navigation Ordinance
(SR 747.201.1):

> **Outer shore zone (150–300 m)** — max 10 km/h for motorized vessels.

> **Inner shore zone (150 m)** — enter only to berth, moor or pass a narrows, by
> the shortest route, and never travel parallel to the shore.

The lines are computed from the OpenStreetMap shoreline at 150 m and 300 m.

### Where does the wind data come from?

From MeteoSwiss 10-minute wind and gust measurements, published as Swiss Open
Government Data (© MeteoSwiss). It is a measurement network, not a forecast.

### How accurate are harbours, fuel stations and restricted zones?

They come from OpenStreetMap community data and may be incomplete or out of
date. Verify locally before relying on them — especially fuel.

### Are scheduled-ship routes live positions?

No. They are timetabled, indicative lines. Scheduled ships are priority vessels:
give way, keep their course clear, and don't anchor on the line.

### How do I switch between km/h and knots?

In the Settings tab. The choice applies to the speedometer, the Watch app and
CarPlay.

### Is my position sent anywhere?

No. See the [privacy policy](/privacy/) — your position never leaves your
device.

## Safety notice

> Helmer is an aid, not an official navigational chart. The skipper remains
> responsible for complying with the law. Zone overlays are a best-effort
> rendering of the legal geometry and may deviate from the authoritative
> sources. Never rely on the anchor alarm alone in dangerous conditions.

## Feature requests and bugs

Ideas are welcome at [support@iperka.com](mailto:support@iperka.com) — tell me
which lake you sail and what would make Helmer more useful.
