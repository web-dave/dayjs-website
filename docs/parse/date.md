---
id: date
title: Date
---

Create a Day.js object with a pre-existing native Javascript `Date` object.

```js
const d = new Date(2018, 8, 18)
const day = dayjs(d)
```

This clones the `Date` object. Further changes to the `Date` won't affect the Day.js object, and vice-versa.
