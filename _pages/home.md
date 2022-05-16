---
layout: splash
permalink: /
date: "2022-02-01"
last_modified_at: 2022-05-16 17:54
title: Zahnarzt Dr. med. dent. Sandra Daller
willkommen:
  - image_path: /assets/images/logo2.svg
    image_class: logo
    alt: "Zahnarzt Dr. med. dent. Sandra Daller"
    title: "Herzlich Willkommen."
    excerpt: >-
      Ich freue mich Sie auf meiner Homepage begrüßen zu dürfen.
about-me:
  - image_path: /assets/images/sandra2.jpg
    image_class: profile-img
    alt: "Zahnarzt Dr. med. dent. Sandra Daller"
    title: "Dr. med. dent. Sandra&nbsp;Daller"
    excerpt: >-
      Nach meinem Zahnmedizinstudium an der medizinischen Universität Innsbruck habe ich von 2010 bis 2021 als selbstständige Zahnärztin in Telfs / Tirol gearbeitet. Ab Juni 2022 bin ich in meiner ursprünglichen Heimat Altenmarkt als Wahlzahnärztin in der Ordination von Dr. Elisabeth Pöttler tätig.
leistungen:
  - excerpt: "Mundhygiene / Professionelle Zahnreinigung"
  - excerpt: "Weiße Füllungen"
  - excerpt: "Kronen / Brücken"
  - excerpt: "Abnehmbarer Zahnersatz"
  - excerpt: "Implantatversorgungen"
  - excerpt: "Wurzelbehandlungen"
  - excerpt: "Ästhetische Zahnheilkunde - Veneers, Bleaching"
---
<h1 class="hide">{{ site.title }}</h1>
<br/>
{% include feature_row id="willkommen" type="left" %}

## Über mich
{% include feature_row id="about-me" type="left" %}

## Leistungen
{% include feature_row id="leistungen" %}

## Kontakt
Familydent<br />
Oberndorferstra&szlig;e&nbsp;46<br />
5541 Altenmarkt im Pongau / Salzburg

Tel.: {{ site.telefon }}

### Telefonische Sprechzeiten
Montag, Dienstag
:   8:00 – 12:00 und 13:00 – 16:00

Mittwoch, Freitag
:   8:00 - 12:00 und 13:00 – 17:00

Donnerstag
:   8:00 – 12:00


### Ordinationszeiten

Montag, Freitag
:   8:00 – 12:00

Dienstag
:   14:30 – 17:30


### Anfahrt

{% include google-map.html %}
