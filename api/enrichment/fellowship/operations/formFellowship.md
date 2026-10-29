{% params %}
### member_ids
Every member must be `active` and not already part of another fellowship, or the request fails with `409`.
{% /params %}

{% params in="response" status="409" %}
### message
Names the member who is already committed elsewhere.
{% /params %}
