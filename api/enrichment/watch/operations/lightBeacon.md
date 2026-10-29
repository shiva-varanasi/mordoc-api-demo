Lights one beacon and starts the relay: each beacon lights the next within minutes. A beacon that was lit in the last hour returns `429`.

{% callout type="note" title="Webhooks" %}
Every lit beacon also sends a [Beacon lit](/api/watch/beacon-lit-event) webhook to your subscribers.
{% /callout %}
