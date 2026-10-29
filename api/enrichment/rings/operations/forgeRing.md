Forges a new ring of the requested kind and metal. Elven, dwarven and human rings only need a smith and a metal. The **One Ring** is different: it needs the Dark Lord's approval and a binding inscription.

{% callout type="warning" title="Handle with care" %}
Once a ring of kind `one` is forged, it starts corrupting every bearer. There is no undo; see [Destroy a ring](/api/rings/destroy-ring).
{% /callout %}

{% params %}
### smith_id
Must belong to a smith registered with the guild of the requested `kind`.

### dark_lord_approval {% badge="conditional" %}
Required only when `kind` is `one`. Obtain the token from Mount Doom before forging; rings of any other kind ignore this field.
{% /params %}

{% params in="response" status="403" %}
### message
Explains which guild rule was broken, for example `smith is not licensed for elven rings`.
{% /params %}
