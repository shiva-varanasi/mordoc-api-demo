---
title: Home
layout: landing
---

{% hero
  title="One API reference"
  titleAccent="to rule them all."
  description="A fictional Middle-earth API, rendered by Mordoc straight from OpenAPI. Browse operations, field trees, examples, cURL samples and webhooks."
  background="/images/hero-images/contour-map.png"
%}
{% button path="/api/fellowship" %}Explore the API{% /button %}
{% /hero %}

{% section title="Three APIs, one site" %}
{% cardGrid cols="3" %}
{% card title="Fellowship" path="/api/fellowship" icon="/icons/card-icons/getting-started.svg" %}
Members, fellowships and quests. Shows pagination, a `oneOf` field and a recursive schema.
{% /card %}
{% card title="Rings of Power" path="/api/rings" icon="/icons/card-icons/configuration.svg" %}
Forge, bear and destroy rings. Shows conditional fields, badges and authored examples.
{% /card %}
{% card title="Middle-earth Watch" path="/api/watch" icon="/icons/card-icons/writing.svg" %}
Beacons, routes, sightings and webhooks, with no cURL sample on the webhook pages.
{% /card %}
{% /cardGrid %}
{% /section %}

{% section title="Before you start" %}
{% cardGrid cols="2" %}
{% card title="Authentication" path="/guides/authentication" icon="/icons/card-icons/deploy.svg" %}
Speak friend and enter: get a token and send it with every request.
{% /card %}
{% card title="How this demo is built" path="/guides/how-this-is-built" icon="/icons/card-icons/preview.svg" %}
The spec, enrichment and example files behind every page.
{% /card %}
{% /cardGrid %}
{% /section %}
