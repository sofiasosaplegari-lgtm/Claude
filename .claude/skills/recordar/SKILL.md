---
name: recordar
description: Guarda una regla o preferencia durable con su porqué y cómo se aplica. Usar con /recordar, "acordate de esto", "de ahora en más" o cuando corrijo algo que vale para siempre.
---
# /recordar

Las memorias locales no las ven las rutinas en la nube; una regla importante debe vivir también en el repo.

1. ¿Es una regla sobre CÓMO trabajar? Un dato va a `WIKI/`, un entregable a `OUTPUTS/`. Si ya existe una parecida, actualizarla con fecha; no duplicar.
2. Escribir `MEMORIA/<nombre-corto>.md` con frontmatter (`name`, `description`, `type`, fecha), la regla en 1-2 frases, **Por qué** y **Cómo se aplica**.
3. Sumar una línea al índice `MEMORIA/README.md`. Si choca con otra regla, mostrar ambas y preguntar cuál manda.
4. Anotar en `changelog.md`. Nunca guardar valores de claves: solo dónde están.
