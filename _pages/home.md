---
layout: splash
permalink: /
specials:
  - title: "Lachgas"
    excerpt: "Viele Erwachsene und Kinder haben Angst vor dem Zahnarztbesuch oder sind sehr angespannt und verkrampft während der Behandlung. Eine Sedierung (Beruhigung bei vollem Bewusstsein) auf der Basis von Lachgas hilft Ihnen beim Entspannen, ebenso gegen Schmerz und Würgereiz."
    url: "#lachgas"
    btn_label: "Mehr …"
    btn_class: "btn--primary"
  - title: "Mundhygiene"
    excerpt: "Ihr individuelles Risiko, Zahn- und Zahnfleischerkrankungen zu entwickeln, wird im Rahmen des Prophylaxe - Check-ups erfasst. Mit schonenden Verfahren werden hartnäckige Zahnbeläge, Zahnstein und Verfärbungen gründlich entfernt ..."
    url: "#mundhygiene"
    btn_label: "Mehr …"
    btn_class: "btn--primary"
  - title: "Weitere Leistungen"
    excerpt: "Einene Überblick über alle unsere Leistungen finden sie hier ..."
    url: "#leistungen"
    btn_label: "Mehr …"
    btn_class: "btn--primary"
---
<br/>
<div class="intro">
<img class="logo" alt="Dr. Sandra Oppeneiger" src="/assets/images/logo.svg">Herzlich Willkommen.<br />
Liebe Patientinnen und Patienten, ich freue mich ..... bla bla bla
</div>

<div class="clear"></div>

## Aktuelles
<!--{% for post in site.posts limit: 3 %}
  {% include archive-single.html %}
{% endfor %}-->
{% include archive-multi.html %}

## Leistungen
{% include feature_row id="specials" %}

## Öffnungszeiten
Montag
:   9:00 – 12:00

Dienstag, Donnerstag, Samstag, Sonntag
:   Geschlossen

Mittwoch
:   16:00 – 19:00

Freitag
:   8:00 – 12:00

<br />
Termine nach telefonischer Vereinbarung.
:   Telefon: {{ site.telefon }}