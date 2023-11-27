---
layout: ../../layouts/BlogLayout.astro
image: /images/ing.jpg
tag: mdi:airplane
createAt: November 28
title: View Transition
author: Daniel Bustos
description: Transitions can be used with astro in a simpler way than in some other programming languages.
---

# Hi!

---

```js
import { ViewTransitions } from "astro:transitions";
<html lang="en">
  <head>
    <title>My Homepage</title>
    <ViewTransitions />
  </head>
  <body>
    <h1>Welcome to my website!</h1>
  </body>
</html>;
```
