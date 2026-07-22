---
ref: support
lang: it
permalink: /it/support/
title: Assistenza
description: Aiuto, contatto e domande frequenti su Helmer.
---

<p class="lede">Helmer è un'app per i proprietari di barche sui laghi svizzeri:
le zone rivierasche legali sulla mappa, un tachimetro GPS, una guardia
all'ancora con allarme di deriva e i dati del vento di MeteoSvizzera.</p>

## Contatto

E-mail **[support@iperka.com](mailto:support@iperka.com)** — di solito rispondo
entro pochi giorni. Helmer è sviluppata da una sola persona, quindi ti chiedo un
po' di pazienza.

Per aiutarmi a risolvere un problema in fretta, indica:

- il tuo dispositivo (p. es. iPhone 15 Pro, Apple Watch Series 9) e la versione di iOS
- la versione di Helmer (scheda Impostazioni, in fondo)
- cosa hai fatto, cosa ti aspettavi e cosa è successo invece
- uno screenshot, se il problema è visibile

## Requisiti

<div class="table-scroll" markdown="1">

| Piattaforma | Versione minima |
|---|---|
| iPhone / iPad | iOS 17.0 |
| Mac | macOS 14.0 |
| Apple Watch | watchOS 10.0 |
| CarPlay | veicoli compatibili |

</div>

Disponibile in italiano, tedesco, francese e inglese.

## Domande frequenti

### Perché Helmer chiede la posizione in background?

Solo per la guardia all'ancora. Per avvisarti che la barca sta arando l'ancora
mentre dormi, l'app deve continuare a leggere il GPS a schermo spento. Se
rifiuti l'accesso «Sempre», tutto il resto — mappa, zone, tachimetro — funziona
normalmente.

### L'allarme dell'ancora non è suonato

Controlla tre cose:

1. L'**autorizzazione alle notifiche**, inclusi gli *avvisi critici*, è
   concessa in Impostazioni → Notifiche → Helmer. Sono gli avvisi critici a
   permettere all'allarme di superare la modalità silenziosa e Full Immersion.
2. La posizione è impostata su **«Sempre»**, non su «Mentre usi l'app».
3. La **guardia è attiva** — il banner diventa verde quando sta sorvegliando.

### Che raggio devo impostare per la guardia all'ancora?

Regola pratica: lunghezza della cima + lunghezza della barca + un margine GPS di
circa 15 m. Helmer avvisa già all'80 % del raggio prima di far scattare
l'allarme completo.

### Perché la mia velocità differisce leggermente dal chartplotter?

Helmer legge la velocità rispetto al fondo dal GPS del dispositivo. Il GPS di
consumo oscilla di qualche decimo di km/h, perciò Helmer applica una tolleranza
di 1 km/h prima di segnalare un superamento in zona rivierasca. Anche onde,
tendalini e hard-top peggiorano la ricezione; l'app mostra la precisione GPS
attuale per permetterti di valutarla.

### Helmer funziona senza copertura mobile?

Sì. Mappa, zone, posizione, velocità e guardia all'ancora sono calcolate
interamente sul dispositivo e non richiedono connessione. Solo i dati del vento
necessitano di rete — senza segnale Helmer continua a mostrare l'ultima
misurazione scaricata, con l'orario, così sai quanto è vecchia.

### Da dove provengono le zone rivierasche?

Derivano dall'art. 53 dell'ordinanza sulla navigazione interna (RS 747.201.1):

> **Zona rivierasca esterna (150–300 m)** — max. 10 km/h per i natanti
> motorizzati.

> **Zona rivierasca interna (150 m)** — percorribile solo per attraccare,
> ormeggiare o superare un passaggio stretto, per la via più breve e mai
> parallelamente alla riva.

Le linee sono calcolate a 150 m e 300 m dalla riva di OpenStreetMap.

### Da dove provengono i dati del vento?

Dalle misurazioni di vento e raffiche a 10 minuti di MeteoSvizzera, pubblicate
come dati aperti (© MeteoSvizzera). È una rete di misurazione, non una
previsione.

### Quanto sono affidabili porti, distributori e zone vietate?

Provengono dai dati della comunità OpenStreetMap e possono essere incompleti o
non aggiornati. Verifica sul posto prima di farci affidamento — soprattutto per
il carburante.

### Le rotte dei battelli sono posizioni in tempo reale?

No. Sono tracciati indicativi basati sull'orario. I battelli di linea sono
prioritari: dare la precedenza, tenere libera la rotta e non ancorare sulla
linea.

### Come passo da km/h a nodi?

Nella scheda Impostazioni. La scelta vale per il tachimetro, l'app per Watch e
CarPlay.

### La mia posizione viene inviata da qualche parte?

No. Vedi l'[informativa sulla privacy](/it/privacy/) — la tua posizione non
lascia il dispositivo.

## Avviso di sicurezza

> Helmer è un ausilio, non una carta nautica ufficiale. Il conduttore resta
> responsabile del rispetto delle prescrizioni. Le zone visualizzate sono una
> rappresentazione al meglio della geometria legale e possono discostarsi dalle
> fonti determinanti. In condizioni pericolose non affidarti mai al solo
> allarme dell'ancora.

## Suggerimenti e problemi

Le idee sono benvenute a [support@iperka.com](mailto:support@iperka.com) —
scrivimi su quale lago navighi e cosa renderebbe Helmer più utile.
