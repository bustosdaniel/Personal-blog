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

Para hacer un spinner necesitamos la etiqueta `div` que este vacia, además se debe establecer `keyframes` con sus respectivos estilos para que asi se haga visible el estado en el que esta el spinner.

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

---

```css
@keyframes spin {
  0% {
    transform: rotate(0deg);
  }

  100% {
    transform: rotate(360deg);
  }
}
```
