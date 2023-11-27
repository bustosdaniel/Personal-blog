---
layout: ../../layouts/BlogLayout.astro
image: /images/post2.jpg
tag: mdi:airplane
createAt: November 28
title: Covid-19
author: Daniel Bustos
description: Python + pandas + matplotlib to visualize COVID-19 data in Colombia. Simple and useful graphs deaths by department, featured cities, percentages of cases, and monthly evolution.
---

# Hi !

---

```py
import pandas as pd;
import matplotlib.pyplot as plt;

ciudades = ['Bogotá D.C', 'Medellin', 'Cali', 'Barranquilla', 'Bucaramanga']
indice_muertes = [17775, 6390, 5041, 4723, 2302]

plt.figure(figsize=(10, 6))
plt.barh(ciudades, indice_muertes, color='green')

plt.title('Top 5 Ciudades con Mayor Índice de Muertes por Casos Confirmados (2021)')
plt.xlabel('Índice de Muertes por Casos Confirmados')
plt.ylabel('Ciudades')

plt.tight_layout()
plt.savefig('indice_muertes.png')
plt.show()
```
