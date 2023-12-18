---
layout: ../../layouts/BlogLayout.astro
image: /images/post3.jpg
tag: mdi:airplane
createAt: December 15
title: Spinner
author: Daniel Bustos
description: Aprendi como hacer un spinner por medio de css
---

# Mi primer spinner

---

```js
<div
  className="spinner"
  style={{
    border: "4px solid rgba(0, 0, 0, .1)",
    width: "36px",
    height: "36px",
    borderRadius: "50%",
    borderLeftColor: "transparent",

    animation: "spin 1s linear infinite",
  }}
></div>
```
