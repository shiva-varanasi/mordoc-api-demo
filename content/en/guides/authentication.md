---
title: Authentication
description: Get a bearer token and send it with every request.
---

Every request needs a bearer token in the `Authorization` header.

```bash
curl https://api.middle-earth.example/v3/members \
  -H "Authorization: Bearer mellon_live_example"
```

## Getting a token

Tokens are issued in the Council of Elrond dashboard. Speak the word _mellon_ at the gate and one is generated for you.

{% table %}
* Token prefix
* Environment
---
* `mellon_live_`
* Production (Rivendell, Eregion, Minas Tirith)
---
* `mellon_test_`
* Sandbox (The Shire, Mount Doom, Weathertop)
{% /table %}

{% callout type="warning" title="Keep tokens secret" %}
Anyone with your token can light your beacons. Never commit it to a repository or send it to a Ringwraith.
{% /callout %}
