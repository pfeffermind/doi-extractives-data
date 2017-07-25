---
title: Anfallende Zahlungen
layout: default
permalink: /explore/how-it-work/anfallende-zahlungen/
breadcrumb:
  - title: Deutscher Rohstoffsektor
    permalink: /explore/how-it-work/
---
<link rel="stylesheet" type="text/css" href="{{ site.baseurl_root }}/css/slick-theme.css"/>
<link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/jquery.slick/1.6.0/slick.css"/>

<main class="container-page-wrapper layout-state-pages">
  <section class="container" style="position: relative;">

    {% include breadcrumb.html %}
    <h1 id="title">{% t anfallende_zahlungen.title %}</h1>

    <div class="container-left-9">
      <section id="anfallende_zahlungen" style="position: relative;">
        <section id="einnahmen" style="position: relative;">
          <h2>{% t anfallende_zahlungen.einnahmen.title %}</h2>
          <p>
            {% t anfallende_zahlungen.einnahmen.p %}
          </p>
        </section>
      </section>
      <br/>
      <section id="zuständigkeit-für-die-einnahmen" style="position: relative;">
        <h2>{% t anfallende_zahlungen.zuständigkeit-für-die-einnahmen.title %}</h2>
        <p>
          {% t anfallende_zahlungen.zuständigkeit-für-die-einnahmen.p %}
        </p>
      </section>
      <br/>
      <section id="zahlungen-industrie" style="position: relative;">
        <h2>{% t anfallende_zahlungen.zahlungen-industrie.title %}</h2>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.p %}
        </p>
        <h3 id="körperschaftsteuer">
          {% t anfallende_zahlungen.zahlungen-industrie.körperschaftsteuer.title %}
        </h3>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.körperschaftsteuer.p %}
        </p>

        <h3 id="feldes-und-förderabgaben">
          {% t anfallende_zahlungen.zahlungen-industrie.feldes-und-förderabgaben.title %}
        </h3>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.feldes-und-förderabgaben.p1 %}
        </p>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.feldes-und-förderabgaben.p2 %}
        </p>

        <h3 id="gewerbesteuer">
          {% t anfallende_zahlungen.zahlungen-industrie.gewerbesteuer.title %}
        </h3>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.gewerbesteuer.p1 %}
        </p>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.gewerbesteuer.p2 %}
        </p>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.gewerbesteuer.p3 %}
        </p>

        <h3 id="pachtzahlungen">
          {% t anfallende_zahlungen.zahlungen-industrie.pachtzahlungen.title %}
        </h3>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.pachtzahlungen.p1 %}
        </p>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.pachtzahlungen.p2 %}
        </p>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.pachtzahlungen.p3 %}
        </p>

        <h3 id="verbrauchsteuern">
          {% t anfallende_zahlungen.zahlungen-industrie.verbrauchsteuern.title %}
        </h3>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.verbrauchsteuern.p1 %}
        </p>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.verbrauchsteuern.p2 %}
        </p>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.verbrauchsteuern.p3 %}
        </p>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.verbrauchsteuern.p4 %}
        </p>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.verbrauchsteuern.p5 %}
        </p>
        <p>
          {% t anfallende_zahlungen.zahlungen-industrie.verbrauchsteuern.p6 %}
        </p>

      </section>
    </div>

    <div class="sticky sticky_nav container-right-3">
      <h3 class="state-page-nav-title container">
        <div class="nav-title">{% t anfallende_zahlungen.title %}</div>
      </h3>
      <nav>
        {% assign nav_items = site.translations[site.lang]['anfallende_zahlungen'].nav_items %}
        {% include case-studies/_nav-list.html nav_items=nav_items %}
      </nav>
    </div>
  </section>
</main>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script type="text/javascript" src="//cdn.jsdelivr.net/jquery.slick/1.6.0/slick.min.js"></script>
<script type="text/javascript" src="{{ site.baseurl_root }}/js/lib/static.min.js" charset="utf-8"></script>