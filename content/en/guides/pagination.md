---
title: Pagination
description: Page through lists with cursors.
---

List operations return a page of results with `has_more` and `next_cursor`. Pass the cursor as `cursor` on the next request.

```bash
curl "https://api.middle-earth.example/v3/members?limit=2&cursor=cur_samwise" \
  -H "Authorization: Bearer mellon_live_example"
```

Stop when `has_more` is `false`. See [List members](/api/fellowship/list-members) for a live example.
