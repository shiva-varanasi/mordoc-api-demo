---
title: Errors
description: How the API reports problems.
---

The API uses standard HTTP status codes. Error responses share one shape.

```json
{
  "code": "you_shall_not_pass",
  "message": "token lacks the required scope",
  "request_id": "req_9a1"
}
```

{% table %}
* Status
* Meaning
---
* `401`
* Missing or invalid token
---
* `403`
* You shall not pass: your token lacks permission
---
* `404`
* Not found. The thing may not want to be found
---
* `409`
* A conflict, such as a member already in another fellowship
---
* `422`
* Well formed but could not be processed
---
* `429`
* Too many requests, for example a beacon lit twice in an hour
{% /table %}

Quote the `request_id` when you contact support.
