---
title: Welcome to the Middle-earth API
description: A fictional, LOTR inspired API that demonstrates how Mordoc renders OpenAPI specifications.
---

This site is a **demo of Mordoc's API reference rendering**. The API is fictional and inspired by Middle-earth. Every operation page is generated at build time from an OpenAPI 3.1 spec, then enriched with prose written in Markdown.

## What's in here

{% table %}
* API
* What it covers
* Features on show
---
* [Fellowship](/api/fellowship)
* Members, fellowships, quests
* Query parameters, pagination, `oneOf`, recursive schema, deprecated operation
---
* [Rings of Power](/api/rings)
* Forging, bearing and destroying rings
* Conditional fields, badges, authored examples, response-scoped notes
---
* [Middle-earth Watch](/api/watch)
* Beacons, routes, sightings
* Webhooks, array query parameters, `allOf`, spec and authored examples
{% /table %}

## Base URL

```
https://api.middle-earth.example/v3
```

Use the sandbox at `https://sandbox.middle-earth.example/v3` while you experiment. None of these servers exist.

