# Los 3 niveles: de hablar a automatizar

| Nivel | Qué es | Quién aprueba | Ejemplo |
|---|---|---|---|
| **N1** | Hablar con Claude, cada vez desde cero | La persona, siempre | "Resumime este documento" |
| **N2** | **Skill**: un método guardado en `.claude/skills/<nombre>/SKILL.md` | La persona revisa lo que sale | `/guardar-cierre` |
| **N3** | **Rutina**: corre sola con reglas "si X, hacé Y" | Nadie en cada corrida; la persona define las reglas y límites | Resumen diario enviado por aviso |

## Cómo ubicar una tarea

1. ¿Se repite 2-3 veces por semana o más? Si no, queda en N1.
2. ¿Hay que ver el resultado antes de que salga? Si sí, es N2.
3. ¿Se puede escribir como "si pasa X, hacé Y" con una condición medible? Si sí, puede ser N3.

## Reglas de oro

- **Delegar la ejecución, nunca el criterio.**
- No subir de nivel sin la aprobación de la persona.
- Si algo se explica por tercera vez: proponer `/crear-skill`.
- Si una skill ya corre igual cada vez y no necesita revisión: proponer `/crear-rutina`.
- Una rutina creada en un archivo **no está activa** hasta que se programa y se verifica con una primera ejecución. Estados: solo diseñada → programada → verificada.
- Un error (401, timeout) jamás se reporta como "todo bien".
