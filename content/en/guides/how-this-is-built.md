---
title: How This Demo Is Built
description: The files behind every page of this demo.
---

Everything you see comes from files in the `mordoc-api-demo` project.

```
config/api.yaml          registers the three specs
api/specs/               OpenAPI 3.1 specs, never hand-edited
api/enrichment/<id>/     Markdown prose for operations and schemas
api/examples/<id>/       authored request and response examples
config/navigation/       sidenav with operation: entries
```

## What to look at

{% table %}
* Feature
* See it in
---
* Spec-only page, no enrichment
* [Retrieve a member](/api/fellowship/get-member)
---
* Conditional badge and response-scoped note
* [Forge a ring](/api/rings/forge-ring)
---
* Free badges (`Read-only`, `Beta`)
* [Retrieve a ring](/api/rings/get-ring)
---
* `oneOf` and recursive schemas
* [List members](/api/fellowship/list-members)
---
* Authored examples next to spec examples
* [Light a beacon](/api/watch/light-beacon)
---
* Webhooks
* [Beacon lit](/api/watch/beacon-lit-event)
---
* Deprecated operation
* [Dismiss a member](/api/fellowship/dismiss-member)
{% /table %}

Learn more in the [Mordoc documentation](https://mordoc.dev).
